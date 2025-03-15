# **ANPR & ATCC System**

## **Overview**
This project is an **Automatic Number Plate Recognition (ANPR)** and **Automated Traffic Control & Compliance (ATCC)** system leveraging **YOLOv8** and **YOLOv9** for real-time vehicle monitoring.  
It includes additional features such as:

- 🚴 **Helmet Detection**
- 🏍 **Triple Riding Detection**
- 🚧 **Accident Detection**
- 🚑 **Emergency Vehicle Detection**

The system is developed using **Flask** and **Python** for the backend, while **React.js** is used for the frontend.

---

## **Features**
- **ANPR (Automatic Number Plate Recognition):** Detects and extracts vehicle license plates using YOLOv8/YOLOv9 models.
- **ATCC (Automated Traffic Control & Compliance):** Monitors traffic violations and ensures compliance with regulations.
- **Helmet Detection:** Identifies riders without helmets on two-wheelers.
- **Triple Riding Detection:** Detects cases where more than two riders are on a two-wheeler.
- **Accident Detection:** Recognizes accident scenarios using deep learning models.
- **Emergency Vehicle Detection:** Detects emergency vehicles and prioritizes them.

---

## **Technologies Used**
- **Backend:** Flask, Python
- **Frontend:** React.js
- **Machine Learning Models:** YOLOv8, YOLOv9, PyTesseract-OCR, Computer Vision
- **Database:** MySQL

---

## **Installation**
### **Prerequisites**
Ensure you have the following installed:
- **Python (>=3.11)**
- **Node.js & npm** (for frontend)
- **Flask**
- **React.js**
- **OpenCV, NumPy, TensorFlow/PyTorch**
- **YOLOv8 & YOLOv9 (Ultralytics)**
- **Pytesseract-OCR**

---

## **Deployment**
Follow the steps below to successfully deploy this project:

### **Step 1: Clone the Repository**
Open your **VS Code terminal** and run:
```sh
git clone https://github.com/peacefularmaan/Smart_Traffix.git
cd Smart_Traffix
```

---

### **Step 2: Start the Backend**
Run the following command in the terminal:
```sh
python app.py
```
Alternatively, you can use the **"Run Python File"** option for `app.py` in VS Code.

✅ **Now the backend is ready to accept requests from the frontend.**

---

### **Step 3: Start the Frontend**
Open a **new terminal** (Click the **"+"** icon in the terminal) and run:
```sh
cd FrontEnd
npm install  # Run this only for first-time setup
npm run dev
```
This will start the **React frontend**.  
Click on the **host link** displayed in the terminal to open the application.

---

### **Step 4: Login**
Once the frontend starts, a **login page** will appear.  

Use the following credentials:  
- **Username:** `user`  
- **Password:** `pass`  

Upon successful login, the **main dashboard** will appear.

🎉 **And we are done!** 🙌  
Your ANPR & ATCC System is now up and running. 🚀
```

This README file is **well-structured, formatted, and easy to follow**.  
You can **directly copy and paste** it into your `README.md` file.  

Let me know if you need any modifications! 😊
