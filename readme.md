# AutoPlus Web Site

This is a simple web site used for AutoPlus, primarily it describes DivisiBill, for now at least. It is automatically deployed to azure [here](https://blue-mushroom-0194da510.azurestaticapps.net/) using GitHub actions whenever new changes are pushed to the 'main' branch.

The autopl.us domain is aliased to it as is www.autopl.us and that is how it's normally accessed. Because Azure knows about the aliases it genererates TLS certificates for them, thereby allowing HTTPS access as well, for example <https://www.autopl.us>.
