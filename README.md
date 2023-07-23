# firebase-get-to-know-flutter
https://firebase.google.com/codelabs/firebase-get-to-know-flutter#3  
we have committed step_02 folder after making all changes
to run - 
set flutter-firebase-codelab project in firebase 
add authentication email 
add users in auth module 
add database 
add web app 

from VS Code terminal in project root 
flutter pub add firebase_core
flutter pub add firebase_auth
flutter pub add cloud_firestore
flutter pub add provider
flutter pub add firebase_ui_auth

dart pub global activate flutterfire_cli
flutterfire configure

Issues - when running the UI , and logged in go to profile - and add user name .
otherwise null will be saved in user field in DB 
which will cause error and message will not show
