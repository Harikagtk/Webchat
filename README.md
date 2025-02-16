Realtime Webchat

Inside server folder, create a new file named .env which stores informations about server side such as ATLAS_URI, SECURITY_KEY and CLIENT_URL informations
store your database URI inside ATLAS_URI variable
store your security key inside SECURITY_KEY variable
store your client url inside CLIENT_URL variable

Inside client folder, create a new file called .env which stores your information about client side such as REACT_APP_SECURITY_KEY and REACT_APP_BACKEND_URL informations

store your security key inside REACT_APP_SECURITY_KEY variable, note that this value must same as SECURITY_KEY in server/.env file
store your server url inside REACT_APP_BACKEND_URL

Install all dependencies

Client side: on the client directory type npm install
Server side: on the server directory type npm install

Client side : on the client directory type npm install type

Client side: on the client directory type npm start
Server side: on the server directory type npm start
