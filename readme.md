Follow the steps

Generate VAPID Keys using -

npm install web-push -g

web-push generate-vapid-keys

Copy the displayed keys in .env file of backend and frontend folders

To start backend server - node app.js

To start frontend application - npm start

Make sure service worker is registered.

Copy the subscription object generated in API and hit via POSTMAN

You will recive the notification as per data pass from backend
