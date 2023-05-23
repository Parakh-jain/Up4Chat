# Up4Chat

- Up4Chat is a Real-time Firebase Chat Application with Social Authentication including Google using firebase, online statuses,image support, sound notification and ability to create multiple rooms.
- Developed using React, chatEngine.io and Firebase.

## Features
    1. Google User Authentication: Users should be able to log in and log out using their Google accounts via Firebase Authentication.

    2. Chat Rooms: Users should be able to create, join, and leave chat rooms.

    3. Real-Time Messaging: Messages sent by users should appear in the chat room in real time.

    4. Message History: The chat application should store the history of messages for each chat room, which should be visible to users when they join the room.

    5. Private Messaging: Users should be able to send private messages to other users.

## Instructions to Run in your local machine
Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Go to https://chatengine.io/ and create one app and copy your app id and private key to .env file 

```
REACT_APP_CHAT_ENGINE_KEY = "Your chat engine app key"
REACT_APP_CHAT_ENGINE_ID = "Your chat engine app ID"
```

Also create a https://console.firebase.google.com/ firebase app and copy the app config details to .env file

```
REACT_APP_FIREBASE_API_KEY = "Your Firebase config details"
REACT_APP_FIREBASE_AUTH_DOMAIN = "Your Firebase config details"
REACT_APP_FIREBASE_PROJECT_ID = "Your Firebase config details"
REACT_APP_FIREBASE_STORAGE_BUCKET = "Your Firebase config details"
REACT_APP_FIREBASE_MESS_SEND_ID = "Your Firebase config details"
REACT_APP_FIREBASE_APP_ID = "Your Firebase config details"
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

## Instructions for Deployment
- After following all Instructions to Run in your local machine, follow below steps for Deployment
- Run `npm run build`
- Go to netlify.com --> Login --> Sites --> manually upload build folder of our react app --> change site name from site settings
- Go to Firebase --> Authentication --> Authorized Domains --> add <site_name_from_netlify> there