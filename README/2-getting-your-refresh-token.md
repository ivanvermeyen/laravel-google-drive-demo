# Laravel & Google Drive Storage

## Getting your Refresh Token

Go to https://developers.google.com/oauthplayground.

> Make sure you added this URL to your Authorized redirect URIs in the [previous step](1-getting-your-dlient-id-and-secret.md).

In the top right corner, click the settings icon, check "Use your own OAuth credentials" and paste your Client ID and Client Secret.

<img width="463" alt="Use your own OAuth credentials" src="https://cloud.githubusercontent.com/assets/3598622/22397216/24fe7d88-e56d-11e6-82cf-2d75365d8800.png">

In step 1 on the left, scroll to "Drive API v3", expand it and check the first drive scope.

<img width="488" alt="Check Scopes" src="https://user-images.githubusercontent.com/3598622/28462312-fa4397ea-6e1a-11e7-93ad-365b891052a6.png">

Click "Authorize APIs" and allow access to your account when prompted.
There will be a few warning prompts, just proceed.

When you get to step 2, check "Auto-refresh the token before it expires" and click "Exchange authorization code for tokens".

<img width="493" alt="Exchange authorization code for tokens" src="https://cloud.githubusercontent.com/assets/3598622/22397183/8472095c-e56c-11e6-85be-83adf00837c7.png">

When you get to step 3, click on step 2 again and you should see your **refresh token**.

<img width="487" alt="Refresh Token" src="https://cloud.githubusercontent.com/assets/3598622/22397176/2cef7a98-e56c-11e6-83b9-b4653850dbca.png">

---

Next: [Getting your Root Folder ID](3-getting-your-root-folder-id.md) | [Back to README](../README.md)