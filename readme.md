# Freeing Basis Data With Node.js

## Information On Setup
Prior to running freeData.js the following install commands must be run in the directory that freeData.js resides.

*  cd/(freeDataDir) //changes directory to path specified in ()

*  npm install request //installs request module
*  npm install fs //installs fs module
*  npm install pg //installs pg module
*  npm install async //installs async module
*  npm install socket.io //installs socket.io module
*  npm install socket.io-client // installs socket.io-client module


## Information On Variables

*  _**date**_ pulls the current date from the system.
*  "outputFile" is set to be called "metrics.json", this can be changed here.
*  "usr" put your user-name for basis account in here
*  "psw" put your password for basis account in here
*  "access_token" code response from server for authorizing data from internal API
*  "freq" is the amount of in between loops of the script run... Basis only updates metric data once per minute so although you can set it to be updated more frequently it is not necessary at this point in time.
*  "conString" insert your postgres database info here to connect
*  "requestDate"
*  "heartArray"
*  "caloriesArray"
*  "stepsArray"
*  "gsrArray"
*  "skin_tempArray"
*  "metricData"
