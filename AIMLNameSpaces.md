## Naming AIML Bot Projects ##

We are experimenting with a name space convention for AIML sets. The AIML sets have several attributes including language, country, principal author, and bot name. I'm not a big fan of introducing a lot of complexity into namespaces. For example if there is only ever going to be one German AIML set, it might make sense to use a shallow convention like "AIML:de-de". But if there comes a time when we have multiple German AIML personalities, we may have to use "AIML:de-de:botmaster:bot-name".

For the time being, let us say that a fully qualified bot path name is "AIML:language-country:botmaster:bot-name". We do have some unusual cases that don't fit perfectly. There could be other attributes in the future such as version and branch.  For the original AIML wiki we proposed the following:


  * AIML:de-de:cdrossman:ALICE
  * AIML:pt-br:cybernet:Cybora
  * AIML:fr-fr:tsiewlan
  * AIML:es-es:xgargoyle:Sara
  * AIML:it-it:sandro:Maria
  * AIML:en-us:foundation:AAA
  * AIML:en-uk:Square-Bear:Mitsuku
  * AIML:en-us:foundation:ALICE
  * AIML:en-us:test

## Google Code ##

Google Code allows only digits, hyphens and lower case letters as valid characters in project names.

Hence this project is named

aiml-en-us-foundation-alice

We will also add a version number to last stable release.  The project without the version number will be the latest current updated release.

Google code also introduces the complexity of naming clones.