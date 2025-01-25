# **Face Detection App**

An face detection application using Python, OpenCV, and Tkinter. This app provides functionalities for detecting faces in images and live video streams, with customizable settings for fine-tuning the detection process.

---

## **Features**

### **Image Processing**
- Upload an image.
- Detect faces in the image using OpenCV's Haar Cascade classifier.
- Save the processed image with detected faces.

### **Video Processing**
- Process live video from a webcam or a video file.
- Detect faces in real-time.
- Start and stop video processing with ease.

### **Settings Tab**
- Customize detection parameters:
  - **Scale Factor**
  - **Minimum Neighbors**
  - **Minimum Size** for face detection.
- Save and load settings for personalized configurations.

---

## **Application Tabs**

### **Image Processing**
- Upload an image (`.jpg`, `.png`, `.jpeg`) using the "Upload Image" button.
- Click "Detect Faces" to process the image.
- Save the processed image by clicking "Save Image."

### **Video Processing**
- Enter a video source (e.g., `0` for the default webcam, or a file path).
- Click "Start Video Processing" to begin real-time face detection.
- Stop the video processing with the "Stop Video Processing" button.

### **Settings**
- Adjust the following detection parameters:
  - **Scale Factor**: Controls the image scaling for face detection (default: 1.1).
  - **Min Neighbors**: The number of neighbors a rectangle should have to be considered a face (default: 5).
  - **Min Size**: The minimum size (in pixels) for detecting faces (default: 30).
- Save settings to `face_detection_settings.json` for future use.

---
