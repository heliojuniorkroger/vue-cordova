# vue-cordova
> A Vue template integrated with Cordova for creating hybrid apps
## Pre-requisites
You need to have *vue-cli* installed globally:
```bash
npm install -g vue-cli
```
## Creating
```bash
vue init heliojuniorkroger/vue-cordova my-app
```
After this, you'll need to answer some questions so the template can perform all files fine.
## Installing
To install all the dependencies, you need to run:
```bash
npm install
```
## Cordova things
You still have to add the Cordova things on the project (like the platform, or the plugins), **e.g** adding the Android platform:
```bash
cordova platform add android
```
## Testing your app
If you want to test your app in the browser, you can run:
```bash
npm start
```
Or if you want wanna test in a device or even an emulator, just run:
```bash
npm run android
npm run ios
```
(This will automaticly build the Vue application and run using the Cordova CLI)
## Building the app
To build the app, run:
```bash
npm run build
```
