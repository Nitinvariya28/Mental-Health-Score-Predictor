# Mental Health Signal - Student Wellness Analytics

## Objective
The objective of this project is to provide a quick read on how a student's habits, screen time, and stress levels correlate with their mental health score. By analyzing daily rhythm rather than a clinical diagnosis, the application offers an estimated mental health signal. It features a predictive machine learning model and a web-based interactive UI to analyze and visualize the score based on various digital and lifestyle metrics.

## Project Details
This project contains two primary components:
1. **Backend**: A REST API built with FastAPI that exposes an endpoint (`/predict`) to run predictions using a pre-trained Machine Learning model (`Mental_Health_Model.pkl`).
2. **Frontend**: A responsive web interface built with HTML, CSS, and Vanilla JavaScript. The user can submit their profile, academic/digital habits, and lifestyle/stress details to get a predicted mental health score (0-10) visualized on an animated gauge.

## How to Install and Run Locally

### Prerequisites
- Python 3.8+ installed on your system.

### Installation
1. Open a terminal or command prompt and navigate to the project directory:
   ```bash
   cd "e:\Documents\Camera Roll\mlproject"
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
1. Start the FastAPI backend server using Uvicorn:
   ```bash
   uvicorn main:app --port 2200 --reload
   ```
   *Note: Ensure it runs on port 2200, as the frontend script currently points to `https://mansik-santulan-score.onrender.com` or local equivalent.* (You may need to update `API_BASE` in `script.js` to `http://localhost:2200` if you want to test fully locally without the deployed API).

2. Open the `index.html` file in your web browser. Alternatively, you can use a local static file server like Live Server (VS Code extension) or Python's HTTP server:
   ```bash
   python -m http.server 8000
   ```
   Then navigate to `http://localhost:8000` in your browser.

## Dataset
The project uses the `Student Social Media And Mental Health Impact.csv` dataset, which includes data on students' digital platform usage, academic habits, and lifestyle choices.
