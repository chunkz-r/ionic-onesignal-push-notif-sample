Ionic 3 with OneSignal Plugin for push notification purpose
===================

Example Ionic project after following tutorial from : ```https://medium.com/appseed-io/how-to-integrate-onesignal-push-notifications-into-an-ionic-3-application-eb2fdc3e6176``` (skipped part Supermodular2)

***Note***

1. Change variable `sender_id` and `oneSignalAppId` at `<project_folder>/src/config.ts`
```
export const sender_id = 'XXXXXXXXXXXXX'; //Google Firebase Sender ID
export const oneSignalAppId = 'XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX'; //OneSignal App ID
```

2. Add Platform for Ionic, example: Android
```
ionic cordova platform add android
```

***Special Thanks***

Ionic 3 : ```https://socket.io/```

OneSignal : ```https://github.com/Wisembly/elephant.io```

Stavros Kounis : ```https://medium.com/@skounis```