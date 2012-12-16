
# Express-chat

Express chat is a node.js multi-server chat application with file exchange capabilities.
Messages are sent with Socket-IO and saved in MongoDB.


## Requirements
* Node.js >= v0.6.2
* MongoDB and Redis installed and running.

## Installation
* git clone git://github.com/Tug/express-chat.git
* cd express-chat
* npm install .

## Configuring
The config.json file will overwrite properties definied in config.js. Edit it to set your configuration properties such as database host, port, username, password, etc.


## Running
* node app
or
* node app myconfig.js

