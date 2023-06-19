# Face Recognition HTML Application for Foscam FI9816V2 Using face-api.js

This is a one-page HTML application that allows you to perform face recognition using the Foscam FI9816V2 camera. It utilizes the face-api.js library for face detection and recognition.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Live%20Demo-blue)](https://yeerock.000webhostapp.com/foscam-api-face-recognition-demo/foscamFI9816PV2-api-face-recognition.html)

**Note:** For demo purposes, please run the application with `chrome.exe --disable-web-security` command, as it requires disabling web security to function properly.

## Usage Instructions

1. Enter your camera's IP, PORT, USERNAME, and PASSWORD.
2. Click the "Save Camera Info" button to save the camera information.
3. Look at the camera and smile to capture your face. You can save multiple faces.
4. The application will retrieve a camera screenshot snapshot every 1 second and automatically detect faces.
5. The application will display one of the following messages for each detected face:
   - "NO FACE DETECTED" if no face is detected in the snapshot.
   - "UNKNOWN FACE" if a face is detected but it doesn't match any saved faces.
   - The saved name of the detected face if it matches any of the saved faces.

Please ensure that you have a compatible Foscam FI9816V2 camera and the necessary camera credentials for the application to function correctly.

Feel free to explore the live demo and experience the face recognition capabilities using face-api.js.

**Author Information:**
This application is developed by Leong Yee Rock, a hobbyist software engineer. Leong Yee Rock works for VYROX.com IoT, an IoT solution R&D company.

**Note:** It is important to be aware of potential security risks when running applications with disabled web security. Exercise caution and use this feature only for testing purposes.

For any issues or further information, please refer to the [GitHub repository](https://github.com/your-repository-link) associated with this project.

Happy face recognition!
