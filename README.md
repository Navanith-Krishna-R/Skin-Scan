# SkinScan 

Developed in December 2024, **SkinScan ** is an **AI-powered dermatology assistant** with a web interface and machine learning module. The platform allows users to diagnose skin conditions, learn about them, and contact doctors if needed — making it an accessible tool for early skin disease detection and awareness.

The **CNN-based deep learning model**, trained on the **HAM10000 dataset** from Harvard, classifies uploaded skin images into **seven skin disease categories** with probability scores. The system applies advanced preprocessing techniques to boost accuracy, achieving **86–87%** performance on test data.

---

## 🩺 Features

### 📷 Core Functionality
- Upload a **skin image** for instant AI-based diagnosis.
- Classifies into **7 common skin disease categories**.
- Displays **confidence percentage** for each prediction.

### 📚 Educational Resources
- Detailed info about each skin condition: **symptoms, causes, and precautions**.
- Links to trusted medical resources.

### 👩‍⚕️ Consultation
- Option to **connect with dermatologists** for expert guidance.

### ⚡ Performance
- Achieves **86–87% accuracy** on test data.
- Powered by **TensorFlow & Keras** with a streamlined preprocessing pipeline.

---

## 🛠 Tech Stack

**Frontend:** HTML, Bootstrap, JavaScript  
**Dataset:** HAM10000 (Harvard University)  
**Machine Learning:** Python, Pandas, NumPy, TensorFlow, Keras, Streamlit  

![Python](https://img.shields.io/badge/Language-Python-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap-7952B3?logo=bootstrap&logoColor=white)
![HTML](https://img.shields.io/badge/Markup-HTML-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/Script-JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 📊 Model Details
- **Dataset:** HAM10000 (Harvard University)
- **Model:** CNN architecture with data augmentation
- **Accuracy:** 86–87%
- **Preprocessing:** Image resizing, normalization, augmentation

---

## 📸 Screenshots

### Home Page
![Image](https://github.com/user-attachments/assets/9a5f31f1-7700-4f27-b4bf-2945c6e2dc19)

### Diagnosis Page
![Image](https://github.com/user-attachments/assets/9e1230ef-5e31-4595-bef4-18afe7c0e7dd)
![Image](https://github.com/user-attachments/assets/24eef6bd-4bad-43b7-b250-065dfeb15c28)

### Other Sections of Website
![Image](https://github.com/user-attachments/assets/5dc3d0e7-ffee-4d77-9858-ac8df448db6f)
![Image](https://github.com/user-attachments/assets/56cf77f4-b98b-49b9-9071-de2bc5cd864c)
![Image](https://github.com/user-attachments/assets/8c2e9ca3-5d55-4bf6-ada2-335a0b4873f3)

---

## 🚀 How to Run
```bash
git clone https://github.com/username/skinscan-ai.git
cd skinscan-ai
pip install -r requirements.txt
streamlit run app.py
