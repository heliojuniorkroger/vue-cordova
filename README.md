# vue-cordova
> A Vue template integrated with Cordova for creating hybrid apps.
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
You still have to add the Cordova things on the project (like the platform, or the plugins).
**e.g**: Adding the Android platform:
```bash
cordova platform add android
```
## Testing your app
If you want to test your app in the browser, you can just run:
```bash
npm start
```
Or if you want to test in a device or even in a emulator, you gonna need to build first:
```bash
npm run build
```
Now, you can run:
```bash
cordova run
```
## Building the app
To build the app, you'll need to first run:
```bash
npm run build
```
And then, you can finally run:
```bash
cordova build
```