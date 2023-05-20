# Up4Chat

- Up4Chat is a Real-time Chat App.
- Developed using React, chatEngine.io and Firebase.

## Features
1. Google User Authentication: Users should be able to log in and log out using their Google accounts via Firebase Authentication.

2. Chat Rooms: Users should be able to create, join, and leave chat rooms.

3. Real-Time Messaging: Messages sent by users should appear in the chat room in real time.

4. Message History: The chat application should store the history of messages for each chat room, which should be visible to users when they join the room.

5. Private Messaging: Users should be able to send private messages to other users.

## Instructions to Run in your local machine
- Run `git clone <git_url>` in terminal
- Go to https://chatengine.io/ and create one app and copy your app id and private key to .env file and also create a https://console.firebase.google.com/ firebase app and copy the app config details to .env file
- Create a `.env` file with following values and paste the details you got from above step

```
REACT_APP_CHAT_ENGINE_KEY = "Your chat engine app key"
REACT_APP_CHAT_ENGINE_ID = "Your chat engine app ID"
REACT_APP_FIREBASE_API_KEY = "Your Firebase config details"
REACT_APP_FIREBASE_AUTH_DOMAIN = "Your Firebase config details"
REACT_APP_FIREBASE_PROJECT_ID = "Your Firebase config details"
REACT_APP_FIREBASE_STORAGE_BUCKET = "Your Firebase config details"
REACT_APP_FIREBASE_MESS_SEND_ID = "Your Firebase config details"
REACT_APP_FIREBASE_APP_ID = "Your Firebase config details"
```

- Run `npm install` in terminal for installing all the dependencies
- Run `npm run start` in terminal for starting the Web App 

## Instructions for Deployment
- After following all Instructions to Run in your local machine, follow below steps for Deployment
- Run `npm run build` in your terminal
- Go to netlify then sites then manually upload a folder and then  Paste the build folder which was created after running `npm run build` 
- You'll get the deployed site for your Web App