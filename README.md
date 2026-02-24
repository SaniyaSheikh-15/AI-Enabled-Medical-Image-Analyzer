**📌 Project Overview**

This project is an AI-powered Medical Image Analysis Web Application designed to detect Pneumonia from Chest X-ray images using a Convolutional Neural Network (CNN).
The trained deep learning model is integrated into a Flask-based web application that allows users to upload X-ray images and receive real-time predictions along with a downloadable medical report.

**🚀 Key Features**
🖼️ Upload and preview chest X-ray images
🧠 CNN-based Pneumonia detection
📊 Displays prediction result with confidence
📝 AI-generated diagnostic summary
📄 Downloadable PDF medical report
🕒 Maintains prediction history
🎨 Clean and responsive web interface

**🧠 Model Details**
Architecture: Convolutional Neural Network (CNN)
Task: Binary Classification (Pneumonia vs Normal)
Training Dataset: Chest X-ray Dataset
Accuracy: 98.28%
Test Loss: 0.0613
Framework: TensorFlow / Keras

**🛠️ Tech Stack**
*Machine Learning*
Python
TensorFlow / Keras
NumPy
OpenCV

*Web Development*
Flask
HTML
CSS
Jinja2 Templates

*Additional Features*
PDF generation
JSON-based prediction history tracking

**📂 Project Structure**
AI-Medical-Image-Analyzer/
│
├── app.py
├── model/
│   └── trained_model.h5
├── templates/
│   ├── index.html
│   ├── result.html
│   ├── history.html
│   └── error.html
├── static/
├── files/
├── requirements.txt
└── README.md

**⚙️ How to Run the Project**

1️⃣ Clone the Repository
git clone https://github.com/your-username/AI-Medical-Image-Analyzer.git
cd AI-Medical-Image-Analyzer
2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app.py
Open browser and go to:
http://127.0.0.1:5000/
