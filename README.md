## Created with Capacitor Create App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
and comes with a very minimal shell for building an app.

### Running this example

This is an example of the file system request error.

This requires an android with API 29 or older.  If you use an older version, be sure to update the webview.

After running the test, you need to uninstall the App from the emulator or manually go into the app info and reject the storage permission to be able to trigger this test again.  Otherwise it will quickly resolve because the second time it runs, permission was already granted.

Newer API versions automatically grant file access, so you don't get the file access popup and thus when checked if you have permission, the promise is resolved.

Issue and solution noted in this git issue https://github.com/ionic-team/capacitor-plugins/issues/1839
