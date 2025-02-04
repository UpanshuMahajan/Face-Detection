## Face Detection System (OpenCV & SQL Database)
Overview
This project implements a real-time face detection system using OpenCV's Haar Cascade Classifier inside a Jupyter Notebook (FaceDetection.ipynb). The system detects multiple faces in a video stream and assigns names to known individuals while integrating a SQL database for dynamic storage and retrieval.

## Features
✅ Real-time face detection using OpenCV
✅ Multiple face recognition in live video feed
✅ Name-tagging system to store known faces
✅ SQL database integration using XAMPP
✅ Runs inside Jupyter Notebook for easy experimentation

## Technologies Used
Python
Jupyter Notebook (FaceDetection.ipynb)
OpenCV (Haar Cascade Classifier for face detection)
SQL Database (XAMPP for local database management)
Pandas & NumPy for data processing

## Project Structure
📂 Major Project/
 ┣ 📂 dataset/                 # Stores images of recognized faces
 ┣ 📂 haarcascades/            # Contains the Haar Cascade XML files
 ┣ 📜 classifier.xml           # Trained Haar cascade classifier
 ┣ 📜 FaceDetection.ipynb      # Jupyter Notebook for face detection
 ┣ 📜 README.md                # Project documentation (this file)
 
## Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/UpanshuMahajan/Face-Detection.git
cd Face-Detection

2️⃣ Install Dependencies
Ensure you have Python 3.10.6 and Jupyter Notebook installed. Then, run:
pip install -r requirements.txt

3️⃣ Start Jupyter Notebook
jupyter notebook
Then, open FaceDetection.ipynb and run the cells.

4️⃣ Start XAMPP (For Database)
Open XAMPP Control Panel
Start Apache & MySQL
Import face_recognition.sql into phpMyAdmin
How It Works
The system detects faces in real-time using OpenCV.
If a new face is detected, it says UNKNOWN.
The name can be saved in an SQL database using Generate Database.
On future detections, the system automatically recognizes and labels faces.

Future Enhancements
🚀 Improve face recognition with deep learning models
🚀 Build a web interface using Flask
🚀 Enable cloud storage for dataset management
