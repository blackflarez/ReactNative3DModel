# ReactNative3DModel
A custom textured GLTF model with touch rotation controls in React Native.

## Description
![alt text](https://media4.giphy.com/media/HPdJ69z6iMvALGuZ9M/giphy.gif?cid=790b7611307099265b7743a501578a1202dd573a7ed8d739&rid=giphy.gif&ct=g "The app running on an iPhone")

This app was created as the foundation for a future project. Originally, this was made using Three.js on web. After realising my app idea would work better on mobile, I decided to migrate it to React Native using Expo, ExpoThree and ExpoGL. However, this turned out to be a lot more difficult than anticipated and required many hours of Googling to get it working properly, especially on mobile. This may be the only example online of a textured GLTF 3D model using ThreeJS with touch to rotate controls working properly on mobile devices. Feel free to use this as a foundation for your 3D mobile app.

## Getting Started

### Starting the app

1. Open a terminal window at `ExpoThreeModel`.
2. Start the server.
```
npm start
```
3. Metro Bunder window should open in your web browser. Scan the QR code to run using Expo Go on iOS/Android devices or Run in webbrowser.

### Notes for making changes

* If you want to import your own models, make sure to export your gltf/glb models without textures, then reference the texture file seperately. Also watch out for scaling. My example coke can is quite small, so adjust the FOV of the Perspective Camera.

## Author
Ruben Gueorguiev - [GitHub](https://github.com/blackflarez) - [LinkedIn](https://www.linkedin.com/in/ruben-gueorguiev-1bb0151b8/)
