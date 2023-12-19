# Webcam Easy JS
This is a javascript library for accessing webcam stream and taking photos.

You can easily add it as a module to your own app.

- Streaming webcam on desktop computer or mobile
- Switch back or front cameras on mobile
- Take pictures and be able to download.

## Live Demo

https://drive.google.com/file/d/179ZhkvRtpyRy2yd1kaqs4SOorlLiw8mc/view?usp=sharing

## Functions
- start(startStream) : start streaming webcam 
  - get permission from user
  - get all video input devices info
  - select camera based on facingMode 
  - start stream
  
  startStream is optional parameter, default value is true
      
- stop() : stop streaming webcam
  
- stream() : start streaming webcam to video element
  
- snap() : take photo from webcam
  
- flip() : change Facing mode and selected camera

## Properties

- facingMode : 'user' or 'enviroment'
- webcamList : all available camera device
- webcamCount : number of available camera device
