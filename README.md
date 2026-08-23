# 🧠 Mental Health Prediction System

A machine learning–based web application that predicts a student's **mental health impact level** using social media usage and lifestyle-related information.

The project includes a trained Machine Learning model, a **FastAPI backend**, and an interactive **HTML/CSS/JavaScript frontend**.

---

## 📌 Project Overview

Social media usage can have an impact on students' mental well-being. This project uses machine learning to analyze different student-related factors and predict the corresponding mental health impact.

The system provides:

* 🧠 Machine Learning–based prediction
* ⚡ FastAPI REST API backend
* 🌐 Interactive web frontend
* 📊 Trained `.pkl` model
* ✅ Input validation using Pydantic
* 🔗 Frontend and backend integration
* 📓 Jupyter Notebook containing the ML workflow

---

## 🏗️ Project Structure

```text
ML Project/
│
├── .gitignore
├── ML Project.html
├── Mental_Health_Model.pkl
├── README.md
├── Student Social Media And Mental Health Impact...
├── index.html
├── main.py
├── ml_project.ipynb
├── requirements.txt
├── script.js
└── style.css


# 🚀 Getting Started

## 1. Clone the Repository

Clone the GitHub repository to your local computer:

```bash
git clone https://github.com/Nitinvariya28/Mental-Health-Score-Predictor
```

Then move into the project directory:

```bash
cd "ML Project"
```

---

## 2. Create a Virtual Environment

It is recommended to use a virtual environment.

### Windows

```powershell
python -m venv venv
```

Activate the environment:

```powershell
venv\Scripts\activate
```

After activation, your terminal should look similar to:

```text
(venv) PS C:\...\ML Project>
```

---

## 3. Install Dependencies

Upgrade pip:

```powershell
python -m pip install --upgrade pip
```

Install all required packages:

```powershell
pip install -r requirements.txt
```

---

# ▶️ Run the Backend

The backend is implemented using **FastAPI**.

Start the development server:

```powershell
uvicorn main:app --reload
```

The API will normally be available at:

```text
http://127.0.0.1:8000
```

---

## 📚 API Documentation

FastAPI automatically provides interactive API documentation.

### Swagger UI

Open:

```text
http://127.0.0.1:8000/docs
```

### ReDoc

Open:

```text
http://127.0.0.1:8000/redoc
```

Swagger UI can be used to test the prediction API directly from the browser.

---

# 🌐 Run the Frontend

The frontend consists of:

```text
index.html
style.css
script.js
```

The JavaScript sends the user's input to the FastAPI backend and receives the machine learning prediction.

You can open the frontend using a local development server such as **VS Code Live Server**.

Make sure the FastAPI backend is running before submitting a prediction.

---

# 🔄 Application Workflow

```text
User
 │
 ▼
Frontend
 │
 │ Student Information
 ▼
JavaScript
 │
 │ HTTP Request
 ▼
FastAPI Backend
 │
 ▼
Input Validation
 │
 ▼
Machine Learning Model
 │
 ▼
Prediction
 │
 ▼
FastAPI Response
 │
 ▼
JavaScript
 │
 ▼
Prediction Displayed to User
```

---

# 🤖 Machine Learning Model

The trained model is stored in:

```text
Mental_Health_Model.pkl
```

The model is loaded by the FastAPI backend and used to generate predictions based on the input provided by the user.

The machine learning workflow is documented in:

```text
ml_project.ipynb
```

The notebook contains the development process used for the machine learning project, including data processing, model training, evaluation, and model saving.

---

# 📊 Dataset

The project uses a student social-media and mental-health-related dataset:

```text
Student Social Media And Mental Health Impact...
```

The dataset contains student-related information that can be used to study relationships between social media usage and mental health impact.

---

# 🛠️ Technologies Used

### Backend

* Python
* FastAPI
* Pydantic
* Uvicorn

### Machine Learning

* Scikit-learn
* Pandas
* NumPy
* Joblib

### Frontend

* HTML5
* CSS3
* JavaScript

### Development

* Jupyter Notebook
* VS Code
* Git
* GitHub

---

# 📦 Requirements

All required Python dependencies are listed in:

```text
requirements.txt
```

Install them using:

```powershell
pip install -r requirements.txt
```

---

# 🔐 Environment

The project uses a Python virtual environment.

The virtual environment should **not** be committed to GitHub.

Add the following to `.gitignore`:

```text
venv/
__pycache__/
*.pyc
```

---

# 🧪 Testing the API

After starting the FastAPI server:

```powershell
uvicorn main:app --reload
```

Open:

```text
http://127.0.0.1:8000/docs
```

Use the Swagger interface to:

1. Open the prediction endpoint.
2. Click **Try it out**.
3. Enter the required student information.
4. Click **Execute**.
5. Check the prediction returned by the model.

---

# ⚠️ Disclaimer

This project is intended for **educational and demonstration purposes**.

The prediction produced by this machine learning model should **not** be considered a medical diagnosis or a substitute for professional mental-health assessment.

---

# 🔮 Future Improvements

* Add user authentication
* Store prediction history
* Add visualization dashboards
* Improve model accuracy
* Add multiple machine learning models
* Deploy the FastAPI backend to a cloud platform
* Deploy the frontend separately
* Add database integration
* Add model performance monitoring
* Improve mobile responsiveness

---

# 👨‍💻 Author

**Nitin Variya**

Machine Learning / Deep Learning Project

GitHub: **Nitinvariya28**

---

## ⭐ Project Goal

The main goal of this project is to demonstrate how a trained machine learning model can be integrated with a modern web application using **FastAPI, HTML, CSS, and JavaScript** to provide real-time predictions.
