# 🧠 Mental Health Prediction System

A machine learning web application that predicts a student's **mental health impact level** based on social media usage and lifestyle-related information.

Built with **Python, Scikit-learn, FastAPI, HTML, CSS, and JavaScript**.

## 📌 Features

* 🧠 Machine Learning prediction
* ⚡ FastAPI REST API
* 🌐 Interactive frontend
* ✅ Pydantic input validation
* 📦 Trained `.pkl` model
* 📓 Jupyter Notebook for ML workflow
* 🔗 Frontend–backend integration

## 🏗️ Project Structure

```text
Mental-Health-Score-Predictor/
│
├── .gitignore
├── README.md
├── requirements.txt
├── main.py
├── index.html
├── style.css
├── script.js
├── Mental_Health_Model.pkl
├── ml_project.ipynb
└── Student Social Media And Mental Health Impact.csv
```

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Nitinvariya28/Mental-Health-Score-Predictor.git
cd Mental-Health-Score-Predictor
```

### 2. Create Virtual Environment

**Windows PowerShell:**

```powershell
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```powershell
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## ▶️ Run the Backend

Start the FastAPI server:

```powershell
uvicorn main:app --reload
```

API:

```text
http://127.0.0.1:8000
```

### 📚 API Documentation

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

ReDoc:

```text
http://127.0.0.1:8000/redoc
```

## 🌐 Run the Frontend

The frontend contains:

```text
index.html
style.css
script.js
```

Open `index.html` using **VS Code Live Server** or another local web server.

Make sure the FastAPI backend is running before making predictions.

## 🔄 Workflow

```text
User
  ↓
Frontend
  ↓
JavaScript
  ↓
FastAPI API
  ↓
Pydantic Validation
  ↓
ML Model
  ↓
Prediction
  ↓
Frontend Result
```

## 🤖 Machine Learning

The trained model is stored in:

```text
Mental_Health_Model.pkl
```

The complete ML workflow is available in:

```text
ml_project.ipynb
```

The notebook covers data preprocessing, model training, evaluation, and model saving.

## 🛠️ Technologies

**Backend:** Python, FastAPI, Pydantic, Uvicorn

**Machine Learning:** Scikit-learn, Pandas, NumPy, Joblib

**Frontend:** HTML5, CSS3, JavaScript

**Tools:** Jupyter Notebook, VS Code, Git, GitHub

## 🔐 .gitignore

Do not upload the virtual environment or Python cache files.

```text
venv/
__pycache__/
*.pyc
```

## ⚠️ Disclaimer

This project is created for **educational and demonstration purposes only**. Predictions should not be considered a medical diagnosis or a replacement for professional mental-health assessment.

## 🔮 Future Improvements

* User authentication
* Prediction history
* Database integration
* Dashboard and visualizations
* Model performance monitoring
* Cloud deployment
* Improved mobile responsiveness

## 👨‍💻 Author

**Nitin Variya**

Machine Learning / Deep Learning Developer

GitHub: **Nitinvariya28**

## ⭐ Project Goal

To demonstrate the integration of a **Machine Learning model with FastAPI and a modern web frontend** for real-time prediction.
