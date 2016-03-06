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

<<<<<<< Updated upstream
*  _**date**_ : pulls the current date from the system.
*  _**outputFile**_ : is set to be called "metrics.json", this can be changed here.
*  _**usr**_ : put your user-name for basis account in here
*  _**psw**_ : put your password for basis account in here
*  _**access_token**_ : code response from server for authorizing data from internal API
*  _**freq**_ : is the amount of in between loops of the script run... Basis only updates metric data once per minute so although you can set it to be updated more frequently it is not necessary at this point in time.
*  _**conString**_ : insert your postgres database info here to connect
*  _**requestDate**_ : 
*  _**heartArray**_ : 
*  _**caloriesArray**_ : 
*  _**stepsArray**_ : 
*  _**gsrArray**_ : 
*  _**skin _ tempArray**_ : 
*  _**metricData**_ : 
=======
*  _**date**_ pulls the current date from the system.
*  _**outputFile**_ is set to be called "metrics.json", this can be changed here.
*  _**usr**_ put your user-name for basis account in here
*  _**psw**_ put your password for basis account in here
*  _**access_token**_ code response from server for authorizing data from internal API
*  _**freq**_ is the amount of in between loops of the script run... Basis only updates metric data once per minute so although you can set it to be updated more frequently it is not necessary at this point in time.
*  _**conString**_ insert your postgres database info here to connect
*  _**requestDate**_
*  _**heartArray**_
*  _**caloriesArray**_
*  _**stepsArray**_
*  _**gsrArray**_
*  _**skin_tempArray**_
*  _**metricData**_
>>>>>>> Stashed changes
