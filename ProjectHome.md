# Free A.L.I.C.E. AIML Set #

We have released an updated version of the free ALICE AIML set and made it available on <a href='http://code.google.com/p/aiml-en-us-foundation-alice/'>Google Code</a>.

The Free ALICE AIML set is optimized for use with <a href='http://www.pandorabots.com'>Pandorabots.com</a>.   You will need to create an account on Pandorabots.com and then create a bot.  Use the option of creating a bot with "No Initial Content" before uploading these AIML files.

The release is called <a href='http://code.google.com/p/aiml-en-us-foundation-alice/'>AIML-en-us-foundation-ALICE</a> (a free AIML set, in the English Language as spoken in the United States, authored by the AI Foundation, and the bot name is ALICE). The AIML contains some significant changes and improvements:

  * The <a href='http://alicebot.blogspot.com/2009/03/safe-aiml-reductions.html'>AIML Safe Reductions</a> have been included and released as open source free software. This is a generic set of &lt;srai> reductions that are useful for any English language bot.

  * The <a href='https://code.google.com/p/mindpix/'>GAC-80K</a> data collected by the late Chris Mc Kinstry, translated into AIML, is now included. The AIML consist of about 54,000 questions and statements with truth values varying from Yes ("Is violet a color"?) to No ("Are fish mammals?") with all sorts of gradations of Maybe in between ("Is the sky blue? Sometimes.")

  * Numerous duplicate categories have been removed or merged. The AIML being available on Google Code makes it much easier for anyone in the community to clone and make modifications and correct errors themselves. These can then be submitted back for inclusion in the main branch of ALICE AIML. We are working on some documentation for this process.

This release deprecates the <a href='http://alicebot.org/aiml/aaa'>ALICE AAA Set</a> and the test project to host free AIML on <a href='http://alicebot.wikidot.com/'>wikidot.com</a>. Most of AIML-en-us-foundation is compatible with any AIML 1.0.1 compliant interpreter, however it contains some Pandorabots extensions that run on
<a href='http://pandorabots.com/'>Pandorabots</a>.

### Repository Organization ###

This project contains two types of repositories:

1. A **Development Snapshot Repository** that includes the latest changes to the AIML set

The development snapshot repository is the same as the project's default repository.

2. A set of **Official Production Repositories** that include earlier releases.

These repositories have names like v1-0, v1-7, v2-0 etc.



## AIML File Loading Order ##

The AIML files need to be loaded in a particular order.
[Notes on AIML file loading order](AIMLFileLoadingOrder.md)

## Custom HTML ##

Running this version of the A.L.I.C.E. bot on Pandorabots requires a custom HTML file called custom.html.

## Bot Properties ##

See this page for information about the A.L.I.C.E. Bot Properties: [List of Bot Properties](BotProperties.md)

## AIML Normalization ##

This AIML set is designed to work with the [preprocessor](PreProcessor.md) built into Pandorabots.

## Naming AIML Bot Projects ##

Why is this project called aiml-en-us-foundation-alice?  The answer may be found in our discussion of [AIML Namespaces](AIMLNameSpaces.md).

## Other Pandorabots AIML sets ##

There are several sets of free AIML available in Google Code repositories:


  * Foundation A.L.I.C.E. Bot: <a href='http://aiml-en-us-foundation-alice.googlecode.com'>AIML-en-us-Foundation-ALICE</a>


  * Foundation Fake Kirk Bot: <a href='http://aiml-en-us-foundation-fakekirk.googlecode.com'>AIML-en-us-Foundation-Fakekirk</a>

  * Reference Library Bot: <a href='http://aiml-en-us-ovrp-infotabby.googlecode.com'>AIML-en-us-OVRP-Infotabby</a>

  * Squarebear AIML Utilities and Games: <a href='http://aiml-en-uk-squarebear-utils.googlecode.com'>AIML-en-uk-Squarebear-Utils</a>

  * Japanese Language AIML: <a href='http://aiml-jp-jp-tristan-hikari.googlecode.com'>AIML-jp-jp-Tristan-Hikari</a>

  * CallMom AIML: <a href='http://code.google.com/p/aiml-en-us-pandorabots-callmom/'>AIML-en-us-pandorabots-CallMom</a>

  * AIML Encyclopedia: <a href='http://code.google.com/p/aiml-en-uk-plafferty-encyclopedia/'>AIML-en-uk-plafferty-Encyclopedia</a>

  * The Professor: <a href='http://code.google.com/p/aiml-en-uk-plafferty-professor/'>AIML-en-uk-plafferty-Professor</a>

  * Venus Portuguese AIML <a href='http://code.google.com/p/aiml-pt-pt-futuragora-venus/'>AIML-pt-pt-futurgora-Venus</a>

  * ALICE 2.0 AIML Bot [AIML Virtual Assistant Bot](https://code.google.com/p/aiml-en-us-foundation-alice2/)