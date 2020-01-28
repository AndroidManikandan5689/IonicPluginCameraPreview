# IonicPluginCameraPreview 

---
title: Ionic Camera Preview 
description: Open device camera with preview
---

# cordova-plugin-raqmiyat-camerapreview


## Installation
    ionic cordova plugin add cordova-plugin-raqmiyat-camerapreview (or)
    ionic cordova plugin add https://github.com/GMuthuraja/IonicPluginCameraPreview.git

## Supported Platforms
- Android

### How to Use
```
declare var CameraPreview: any; //paste it below the import section

//button onclick function 
openCam() { 
CameraPreview.openCamera("", (response) => {
      console.log(response); //captured image file path
    }, (error => {
      console.log(error);
})
}
```