# Firebase Codelab: FriendlyChat FOR ASSIGNMENT 2 in CSC4360

Following the codelab instructions listed here: https://firebase.google.com/codelabs/firebase-android


## How to run it

First you need to clone the repository using ssh:

$ git clone git@github.com:dhartman5/codelab-friendlychat-android.git

Next you need to ensure that you have npm installed and using that, install firebase-tools by using the command: 

$ npm install -g firebase-tools@latest

Once that is installed you can run:

$ firebase emulators:start --project=codelab-friendlychat-android

This starts the emulator and you visit http://localhost:4000 to see the dashboard. 
Within the dashboard, you need to manually drag and drop the initial_messages.json file from your local copy of the codelab repository into the data viewer, the local copy should be called "demo-friendlychat-android".

This is where you can see the authentication and real-time database where you can manually add messages and also see other user's messages.
Everything updated in the app talks to the database and vice versa. 

You should use Android Studio to launch the emulator. I am using a Pixel 4 XL on Android version 30. 
