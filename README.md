etmc-postman
============

The files in this repository are meant to be leveraged with the Google Chrome application Postman. Postman can be installed from here: https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm?hl=en

The current files are the following:

ETMC.json.postman_collection: This file needs to be imported into Postman. It builds the actual REST calls to the ETMC API.

globals.postman_globals: This file needs to be imported into Postman. It contains all of the global environment variables needed to setup API calls. You should add variables in here that apply to all sub-environments/profiles. 

useraccount.postman_environment: This file needs to be imported into Postman. It contains environment variables specific to the application you have setup in the Code@ site. Things like clientId, clientSecrect, etc. need to be completed in this file before it is imported into Postman, or if you do not, you will need to use the Postman UI to alter all of the value placeholders.
