

![Python](https://img.shields.io/badge/Python-ML%20%26%20API-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Object%20Detection-orange)
![Flask](https://img.shields.io/badge/Flask-Backend%20API-green)
![React](https://img.shields.io/badge/React-Vite%20Frontend-61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-Styling-lightblue)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Disease%20Detection-red)
![Web App](https://img.shields.io/badge/Web%20App-ML%20Interface-brightgreen)
![Portfolio Project](https://img.shields.io/badge/Type-Portfolio%20Project-important)



# 🌿 AI-Powered Tea Leaf Disease Detection System

A machine learning-based web application designed to detect tea leaf diseases and provide actionable fertilizer/remedy recommendations in both **Sinhala** and **English**. This project aims to help tea planters identify diseases early and treat them effectively using both organic and chemical methods.

##  Here How It Looks!!!

<img width="827" height="969" alt="image" src="https://github.com/user-attachments/assets/acd81e2b-6cea-4ee9-a2b7-4cb7d5dac1ae" />


## 🚀 Features

* **Real-time Disease Detection:** Identifies diseases like Blister Blight, Red Rust, Gray Blight, Brown Blight, and Healthy leaves.
* **High Accuracy:** Powered by the **YOLOv8** object detection model trained on a dataset of 1,494 images.
* **Intelligent Recommendations:** Provides specific treatments based on the detected disease.
    * 🌱 **Organic Remedies** (Home-made/Natural solutions)
    * 🧪 **Chemical Solutions** (Fungicides/Fertilizers)
* **Bilingual Support:** Advice is displayed in both **Sinhala** and **English**.
* **Responsive UI:** User-friendly interface built with **React** and **Tailwind CSS**.

## 🛠️ Tech Stack

### Machine Learning & Data
* **Model:** [YOLOv8](https://github.com/ultralytics/ultralytics) (Nano version for speed)
* **Training Platform:** Google Colab (T4 GPU)
* **Dataset Tool:** Roboflow (Annotation & Augmentation)
* **Preprocessing:** Auto-orientation, Resizing (640x640), Augmentation (Flip, Rotation, Brightness, Noise).

### Backend
* **Framework:** Flask (Python)
* **Libraries:** `ultralytics`, `flask-cors`, `pillow`
* **Functionality:** Loads the custom trained `.pt` model and serves predictions via a REST API.

### Frontend
* **Framework:** React.js (via Vite)
* **Styling:** Tailwind CSS
* **Functionality:** Image upload, preview, and displaying structured advice.


