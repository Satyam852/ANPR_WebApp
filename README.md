# ANPR_WebApp
Automatic Number Plate Detection and Web App Project

![project_architecture](https://github.com/Satyam852/ANPR_WebApp/assets/83311648/deda8c61-8fe4-42d2-8537-8ca14382ff72)

**ANPR_WebApp
Automatic Number Plate Detection and Web App Project**

**Project Overview**
This project involves the development of an Automatic Number Plate Recognition (ANPR) system and its deployment as a web application. The ANPR system is designed to detect and recognize vehicle number plates from images using advanced image processing and deep learning techniques.

**Tech Stack**
Development Environment: Anaconda / Jupyter Notebook

Model Training: Google Colab for YOLOv5 (due to high GPU requirements)

Web Framework: Flask for the web application

Optical Character Recognition: Pytesseract


**Data Sources**
![Roboflow](https://universe.roboflow.com/)
![Kaggle Dataset: Kaggle]( https://www.kaggle.com/datasets )

**Total Images Trained**
More than 900 images


**Project Description**
Image Processing and Object Detection are crucial areas in Data Science with various industrial applications. This project demonstrates the full cycle of developing an ANPR system, including data preprocessing, model building, evaluation, and deployment.

**Key Components:**
Project Architecture: Detailed steps to develop the ANPR system in Python.

Data Gathering and Labeling: Using an Image Annotation Tool developed in pyQT for labeling license plates.

Data Preprocessing: Techniques for preparing the data for model training.

Model Building: Training a deep learning object detection model (InceptionResNet V2) in TensorFlow 2.

Model Evaluation: Calculating Intersection Over Union (IoU) and model precision.

Optical Character Recognition (OCR): Using Tesseract OCR to extract text from detected license plates.

Pipeline Development: Combining object detection and OCR into a cohesive pipeline.

Web App Development: Creating a Flask web app with HTML, Bootstrap, and Python to deploy the ANPR system.


**Project Architecture**


Data Collection and Labeling: Collect images and label the license plates using an Image Annotation Tool.
Data Preprocessing: Normalize and augment the data to improve model performance.


Model Training:
YOLOv5: Train on Google Colab for better GPU support.
InceptionResNet V2: Train using TensorFlow 2.x for object detection.
Model Evaluation: Validate the model using metrics like IoU and precision.
Region of Interest (ROI) Extraction: Crop the license plate area from the image.
OCR with Pytesseract: Extract the number plate text from the cropped image.


Flask Web Application:
API Development: Create RESTful APIs using Flask.
Web Development: Develop the frontend using HTML and Bootstrap.


Integration: Integrate the trained model into the web application and deploy.



![Web-App](https://github.com/Satyam852/ANPR_WebApp/assets/83311648/bd8f1f4c-34ec-4bda-bade-a223a36b40e7)

![image](https://github.com/Satyam852/ANPR_WebApp/assets/83311648/d60d0d68-bc7c-4a97-8595-106444fbab0e)



**AFTER Using YOLOv5**

![image](https://github.com/Satyam852/ANPR_WebApp/assets/83311648/bc8b4651-1ab0-466b-b631-3bbde3babf01)


