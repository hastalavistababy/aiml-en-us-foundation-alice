# Using the A.L.I.C.E. AIML files #

The aiml-en-us-foundation-alice files contain a number of categories with duplicate patterns.  Depending on the AIML interpreter used, duplicates are handled differently.

On Pandorabots the rule is: The files are loaded in order from the top of the list (under the "AIML Files" section) to the bottom.  When a category is loaded that has the same pattern path (i.e. same input pattern, that pattern and topic pattern--remember that &lt;that> and &lt;topic> are set to **implicitly), then Pandorabots discards the earlier category and selects the response template from the most recently loaded category.**

To give an example: Suppose a file A.aiml has a category
```
<category>
<pattern>TEST</pattern>
<template>This is the response from file A.</template>
</category>
```
and a file B.aiml has a category
```
<category>
<pattern>TEST</pattern>
<template>This is the response from file B.</template>
</category>
```

Provided that the files are loaded in alphabetical order, the A.aiml loaded before the B.aiml, then the response to the input "Test" should be "This is the response from file B."

# A.L.I.C.E. AIML File Order #

The A.L.I.C.E. AIML files in aiml-en-us-foundation-alice should be loaded in the following order:

  * First load the Safe reduction files _reducation0.safe.aiml,...,reduction4.safe.aiml_ and _reductions.update.aiml_.
  * Second, load the Mindpixel files _mp0.aiml,...,mp6.aiml_.
  * Then load all remaining AIML files.
  * Pandorabots will always load the file _update.aiml_ as the last file.