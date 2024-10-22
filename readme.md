mkdir basic-crud-app
cd basic-crud-app
npm init -y
npm install express mongoose dotenv joi swagger-jsdoc swagger-ui-express
touch .env
touch server.js

Setup mongodb connecting string
MONGO_URI=mongodb://localhost:27017/
PORT=27017


 Start the Server
Once you have MongoDB set up, run the following command to start your Node.js server:
node server.js


If you want to run it in development mode and automatically restart the server on changes, install and use nodemon:

npm install -g nodemon
nodemon server.js

Run following in browser:
http://localhost:8082/api-docs/