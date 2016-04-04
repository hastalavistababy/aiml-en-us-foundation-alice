AIML utilizes a preprocessing step called Normalization.

This AIML set is designed to work with the default AIML preprocessor supplied with Pandorabots.com.

> The preprocessor

  * Corrects some spelling errors and colloquialisms (e.g. "wanna" --> "want to")
  * Substitutes words for common emoticons (e.g. ":-)" --> "SMILE")
  * Expands contractions (e.g. "isn't" --> "is not")
  * Removes intra-sentence punctuation (e.g. "Dr. Wallace lives on St. John St. --> "Dr Wallace lives on St John St.")

We refer to the above substitution steps as _Normalization_.

The last preprocessing step

  * Splits sentences based on predefined punctuation characters ".", "!", ";" and "?"

All of these preprocessing steps are defined in the configuration file.  In addition the configuration file

  * Defines substitutions for `<gender>`, `<person>` and `<person2>`

The preprocessor normalizes the inputs to the bot by running through a series of substitutions, then splits the input into sentences and feeds these one at a time to the bot.