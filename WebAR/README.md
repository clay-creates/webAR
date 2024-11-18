# **WebXR AR Project**

## **Overview**
This project demonstrates a basic Augmented Reality (AR) application using WebXR and Three.js. It allows users to interact with AR by placing a 3D model (a cat statue) in their environment. The application is accessible directly from a web browser on WebXR-compatible devices, without the need for downloading or installing additional apps.

## **Features**
- Interactive AR experience using WebXR.
- Reticle visualization to position the 3D model in the real world.
- 3D model placement with user interaction (tap-to-place).
- Lightweight and accessible via a web browser.

## **Technologies Used**
- **[WebXR API](https://immersive-web.github.io/webxr/):** Provides AR functionality in the browser.
- **[Three.js](https://threejs.org/):** A JavaScript library for rendering 3D objects.
- **GLTFLoader:** For loading 3D models in `.gltf` or `.glb` format.

## **How It Works**
1. **Initialization:**
   - A canvas is created to render the 3D scene using WebGL.
   - A reticle is displayed to guide where the 3D model can be placed.

2. **Model Placement:**
   - The user interacts with the AR environment by tapping on the screen.
   - The selected 3D model (cat statue) is placed at the reticle's position.

3. **Rendering:**
   - The application continuously updates the scene and camera view to match the user's movements.

Find the live version of this project here:
[WebAR](https://clay-creates.github.io/webAR/)
