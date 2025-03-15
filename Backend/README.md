# Backend - ANPR & ATCC System

## Overview
This is the backend of the **Automatic Number Plate Recognition (ANPR) & Automated Traffic Control & Compliance (ATCC) System**. It is built using **Flask and Python** to handle requests from the frontend, process images/videos, and run machine learning models for vehicle monitoring.

## Features
- **ANPR (Automatic Number Plate Recognition)**: Detects and extracts vehicle license plates using YOLOv8/YOLOv9 models.
- **Helmet Detection**: Identifies riders without helmets on two-wheelers.
- **Triple Riding Detection**: Detects cases where more than two riders are on a two-wheeler.
- **Accident Detection**: Recognizes accident scenarios using deep learning.
- **Emergency Vehicle Detection**: Detects emergency vehicles and prioritizes them.

## Technologies Used
- **Backend**: Flask, Python  
- **Machine Learning Models**: YOLOv8, YOLOv9, OpenCV, PyTesseract-OCR  
- **Database**: MySQL  

## Installation
### **Prerequisites**
Ensure you have the following installed:  
- **Python** (>=3.11)  
- **Flask**  
- **OpenCV**  
- **NumPy**  
- **TensorFlow/PyTorch**  
- **YOLOv8 & YOLOv9 (Ultralytics)**  
- **Pytesseract-OCR**  
- **MySQL Database**  

### **Steps to Run the Backend**
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo/Backend

