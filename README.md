# Ionic2 Push Notifications

To work with this project just clone the repository or download the zip. Navigate to the project directory in you terminal and execute the following commands:
- npm install 
- ionic platform add android (For Android)
- ionic platform add ios (For iOS)

Now generate you app id either by using ionic apps Dashboard or by executing following command:
-ionic io init

Now open your Firebase Console, create a project and generate your SENDER ID & SERVER KEY. The SENDER_ID will be needed in your APP while the SERVER_KEY will be required in your app's cloud dashboard.

## Plugin Installation

Execute the following command to install the push notification plugin.
-cordova plugin add phonegap-plugin-push --variable SENDER_ID=YOUR_SENDER_ID --save

## Send Notification

Open your [Ionic Account](https://apps.ionic.io/). Add your key in the settings. Use the Push option to send the notification.

## Code

The code for push notifications resides in the foolowing files:
- ./src/app/app.module.ts
- ./src/pages/home/home.ts

Keep Calm and Keep Coding!
