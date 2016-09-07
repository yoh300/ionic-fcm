# ionic-fcm
1. Run **_ionic start ionic-fcm https://github.com/yoh300/ionic-fcm_**
2. Go to project **_cd ionic-fcm_**
3. Add platforms: **_ionic platform add android_**
4. Install plugin **_ionic plugin add cordova-plugin-fcm_**
5. Create project on https://console.firebase.google.com
6. Add new apps for Android (Package name=widget id in config.xml)
7. Copy **google-service.json** file to **platforms/android** directory for Android.
8. **_ionic run android_** to run app on Android
9. Go to your project in https://console.firebase.google.com and select **Notifications** from menu -> **New message* -> select your app, add message and click send
