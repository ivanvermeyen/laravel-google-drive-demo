# Laravel & Google Drive Storage

## Getting your Client ID and Secret

Log in to your Google Account and go to this website:

https://console.developers.google.com/

### Create a Project

Create a new project using the dropdown at the top.

<img width="463" alt="Create a new project" src="https://cloud.githubusercontent.com/assets/3598622/22397261/060eac9e-e56e-11e6-907c-717932605569.png">

After you enter a name, it takes a few seconds before the project is successfully created on the server.

### Enable Drive API

Make sure you have the project selected at the top.

Then go to Library and click on "Drive API" under "G Suite APIs".

<img width="1168" alt="Add Drive API" src="https://user-images.githubusercontent.com/3598622/28462245-a13b3d9c-6e1a-11e7-8cf8-0082ac8a9141.png">

And then Enable it.

<img width="383" alt="Enable Google Drive API" src="https://cloud.githubusercontent.com/assets/3598622/22397290/a858c6d8-e56e-11e6-9154-0052d7ecd0eb.png">

### Create Credentials

Go to "Credentials" and click on the tab "OAuth Consent Screen". Fill in a "Product name shown to users" and Save it. Don't worry about the other fields.

<img width="896" alt="Consent Screen" src="https://cloud.githubusercontent.com/assets/3598622/22397326/549fb3c0-e56f-11e6-9b0a-8771b0ba72b4.png">

Then go back to Credentials, click the button that says "Create Credentials" and select "OAuth Client ID".

<img width="435" alt="Create Credentials" src="https://cloud.githubusercontent.com/assets/3598622/22397368/33f8bd0a-e570-11e6-859c-34d112c772e4.png">

Choose "Web Application" and give it a name.

Add https://developers.google.com/oauthplayground in "Authorized redirect URIs". You will need to use this in the next step to get your refresh token. Once you have the token, you can remove the URI.

<img width="910" alt="Credentials" src="https://user-images.githubusercontent.com/3598622/28473452-e675826c-6e44-11e7-8ff0-bea423b0cff7.png">

Click Create and take note of your **Client ID** and **Client Secret**.

---

Next: [Getting your Refresh Token](2-getting-your-refresh-token.md) | [Back to README](../README.md)