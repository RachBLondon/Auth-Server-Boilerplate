# Authenticated Server Boilerplate


Built using Stephen Grider's advanced redux tutorial.

Uses:
- Express
- Bcypt nodejs
- passport
- mongodb
- mongoose
- jwt simple


`npm i` to install, and `npm start` to launch. 

##Mongodb
To run the db you will need [mongodb](https://www.mongodb.org/) installed on your machine.

Once you have Mongodb installed create a data directory in inside the app directory with
`mkdir -p /data/db` 
you might need to use `sudo mkdir -p /data/db`

Set permissions using:
`sudo chown -R $USER /data/db`

Finally start the db in a new terminal tab/window with `mongod`

Remember to shut down mongod runing on local port  http://stackoverflow.com/questions/6478113/unable-to-start-mongodb-local-server

For more details see mongo docs at https://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/#run-mongodb

Visit the tutorial at https://www.udemy.com/react-redux-tutorial/learn/v4/overview
