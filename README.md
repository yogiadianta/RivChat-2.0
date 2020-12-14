## Note

### Add Firebase Into Project
 https://firebase.google.com/docs/android/setup

### Create Authenticattion
 - Go to Project Fireabse Authentication
 - Sing-in method 
 - Enable Email/Password

### Create Realtime Database
 - Go to Project Firebase Realtime Database
 - Create Database
 - Add rule
 ```bash
 {
  "rules":{
   ".read": true,
   ".write": true
  }
 }
 ```
