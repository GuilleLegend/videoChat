# videoChat
webChat App using Angular, Firebase and WebRTC

##Firebase configuration
This project uses Firebase as its database and authentication provider. To use it, you need to add your Firebase configuration information to the environment.ts file located in the src/environments directory.

The environment.ts file should have the following structure:
```javascript
export const environment = {
  production: false,
  firebase: {
    apiKey: 'your_api_key',
    authDomain: 'your_auth_domain',
    databaseURL: 'your_database_url',
    projectId: 'your_project_id',
    storageBucket: 'your_storage_bucket',
    messagingSenderId: 'your_messaging_sender_id',
    appId: 'your_app_id'
  }
};
```
You can find your Firebase configuration information in the Firebase console under the "Project settings" section.

### Tutorial
Here is a step-by-step tutorial to configure Firebase in your project:

1. Go to the Firebase console (https://console.firebase.google.com/) and create a new project.

2. In the Firebase console, navigate to the "Project settings" section and find the "Firebase SDK snippet" card.

3. Click on the "Config" button and copy the configuration information provided.

4. Open the environment.ts file in your project's src/environments directory and paste the configuration information in the firebase object.

5. In the Firebase console, navigate to the "Database" section and create a new Cloud Firestore database.

6. In the "Rules" tab, set the read and write rules to allow access to the database. It is recommended to use specific rules for your project.

7. In the Firebase console, navigate to the "Authentication" section and enable the authentication methods you want to use.

8. In the "Web setup" tab, copy the initialization code and paste it in the index.html file of your project.

9. Make sure your computer has a webcam and microphone activated, it is needed for the project to work properly.

10. You're all set! Your project is now connected to Firebase and ready to use.

Please note that this tutorial is intended to serve as a general guide and your specific implementation may vary.

If you have any issues with configuring Firebase, please refer to the Firebase documentation or reach out to the community on Stack Overflow.

### Other recommendations
Include checking the proper functioning of your webcam and microphone.







