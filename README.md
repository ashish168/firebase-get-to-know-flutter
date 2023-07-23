# firebase-get-to-know-flutter
https://firebase.google.com/codelabs/firebase-get-to-know-flutter#3  
we have committed step_02 folder after making all changes
to run - 
1. set flutter-firebase-codelab project in firebase 
2. add authentication email 
3. add users in auth module 
4. add database 
5. add web app 

from VS Code terminal in project root 
1. flutter pub add firebase_core
2. flutter pub add firebase_auth
3. flutter pub add cloud_firestore
4. flutter pub add provider
5. flutter pub add firebase_ui_auth

these first ran from windows cmd , but afterwards were running from VScode console 
6. dart pub global activate flutterfire_cli
7. flutterfire configure

to run locally , after doing above steps - 
1. open dart.main in vscode
2. click run from top right corner.

Build and Deploy - 
1. firebase build web 
2. flutter channel 
3. firebase deploy

Issues - when running the UI , and logged in go to profile - and add user name .
otherwise null will be saved in user field in DB 
which will cause error and message will not show
