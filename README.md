# Object-Detection
A Flask web app that performs real-time person detection using a pre-trained YOLOv5 model. Users can upload images, and the app returns results with detected persons highlighted using OpenCV. Built with PyTorch, Flask, and HTML/CSS. Simple UI and REST API for integration.

Object-Detection
Object Detection Web App using YOLOv5 and Flask
This project is a web-based object detection system that identifies persons in uploaded images using the pre-trained yolov5s model from Ultralytics. Built with Flask, PyTorch, and OpenCV, the application processes uploaded images, detects persons, draws bounding boxes, and returns the result to the user.

🔧 Features
Upload image via a simple web interface
Detects and highlights persons in the image using YOLOv5
Returns a processed image with bounding boxes
Backend built with Flask and PyTorch Hub
Frontend styled using HTML and custom CSS
🧪 Tech Stack
Python 3
Flask – Web framework
YOLOv5 (torch.hub) – Object detection model
OpenCV – Image processing and annotation
Pandas – Parsing detection results
HTML/CSS – Frontend styling
🗂 Project Structure
object-detection-web/ ├── app.py # Flask backend and YOLOv5 integration ├── templates/ │ └── index.html # Frontend upload form ├── static/ │ ├── style.css # General UI styles │ └── owner.css # Additional form styling ├── uploads/ # Stores uploaded & processed images ├── README.md # Project documentation
