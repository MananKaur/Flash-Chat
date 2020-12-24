# Flash Chat

A cross-platform multi-screen group chat application that uses FirebaseAuth for authentication and Firebase Cloud Firestore to store and sync data. 
The application is implemented using Flutter and Dart. 

<img src="https://raw.githubusercontent.com/MananKaur/Flash-Chat/master/images/threed_mockup%20(1).png" width="100" height="140">

## How to run the app 
1. Clone the repository and open on Android Studio.
2. Get the dependencies by clicking on the highlighted prompt on the Android Studio.
3. Run the app either on an android virtual device or your very physical device.

## User Stories
- A user can register himself.
- A user can login.
- A user can group chat with other users of the app.

## Features
- Register
   - user can register himself/herself once by entering in a valid email id and password.
   - authentication is implemented using Firebase Authentication
   
- Log In
   - user can log in with the same credentials once he has registered.
   
- Chat
   - user can type a message in the chat box and click on send to send the message.
   - the chats of all users are stored and synced using Firebase Cloud Firestore.
   
## Future Features
- showing error messages when user logs in with invalid credentials.
- showing error messages when user registers himself more than once.
- showing error messages when user registers himself with an invalid email id.
- sharing media (images, videos, gifs) in chat.
- one-to-one chats
- private group chats

##  Dependencies
- Flutter
- Dart
- Firebase Authentication
- Firebase Cloud Firestore
- animated_text_kit 3.1.0
- modal_progress_hud 0.1.3

## What the app looks like
<img src="https://raw.githubusercontent.com/MananKaur/Flash-Chat/master/images/threed_mockup%20(1).png" width="400" height="560"> <img src="https://raw.githubusercontent.com/MananKaur/Flash-Chat/master/images/threed_mockup%20(2).png" width="400" height="560">

<img src="https://raw.githubusercontent.com/MananKaur/Flash-Chat/master/images/threed_mockup%20(3).png" width="400" height="560"> <img src="https://raw.githubusercontent.com/MananKaur/Flash-Chat/master/images/threed_mockup.png" width="400" height="560">






   


