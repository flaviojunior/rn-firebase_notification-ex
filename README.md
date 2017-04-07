# rn-firebase_notification-ex
Sample project for Firebase notifications with react native

You have to copy google-services.json and GoogleService-Info.plist from Firebase Console.

You have to configure Firebase in the file /src/firebase/firebase.js

Then use the command below to don't commit the local changes

git update-index --skip-worktree firebase.js

Dependencies:
    
    "firebase": "^3.7.5",
    
    "native-base": "^2.1.1",
    
    "react": "16.0.0-alpha.6",
    
    "react-native": "0.43.2",
    
    "react-native-fcm": "^6.2.0"
