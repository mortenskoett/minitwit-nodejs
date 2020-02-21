# minitwit-nodejs
Test.
An example of a basic structure for the minitwit application using Node.js

## How to setup server: (all from app root) (this is only done once)
0. Install the node package manager npm. (probably `apt install npm`)
1. First time run `npm init` to setup dependencies
2. Setup database directory: `mkdir -p /data/minitwit_db`.

## How to run server: (all from app root)
2. Start local database using `mongod -dbpath=./data/minitwit_db`. (if you want to use local db)
3. Run server using `npm start`.
4. Test-queries can be made e.g. using Postman (probably `apt install postman`)
