# cordovaCameraPlugin Projects

Both project needs cordova , cordova-camera-plugin .  if your android version is above 10 you will not need whitelist plugin as it is already provided in android v10 platform 
*************************
cordova build android  
cordova run android  
*************************
V7 is a project that opens up the camera and allows taking a photo ,it also opens up gallery
![v7](https://user-images.githubusercontent.com/96186474/148524741-5472789a-20f0-4174-929c-6f9568abf179.jpeg)


![v7ss](https://user-images.githubusercontent.com/96186474/148524614-b3b88eeb-d9cb-46a1-bc52-c01e82dca13d.jpeg)
v8 is obsolete and app is not connecting to the camera 
v9 is a project that opens up camera and gallery 
the necessary steps to run on your machine 
*********************************************
npm i
npm run cordova-prepare
npm run build-for-android
npm run emulate-for-android
*********************************************

![v9ss](https://user-images.githubusercontent.com/96186474/148524546-3eab186b-c7a7-4cf2-ad9a-96e9aab09a46.jpeg)

Here there is a live demo

https://user-images.githubusercontent.com/96186474/148524823-521d5f54-33ff-42ea-8e9e-b0a6a58b929d.mp4

I have tested both apps on vm and real device .Both opens up camera ,takes photo ,views photo in gallery with the help of cordova-camera-plugin
