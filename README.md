# Admission Prediction Flask App

This project is a basic Flask application that predicts admission chances for graduate programs based on academic metrics. Using a linear regression model, the app provides insights into the likelihood of being admitted to a graduate school.

## Project Overview

### What We Analyze

Our model considers the following crucial factors to predict your admission chances:

- **GRE Score**: Your performance on the Graduate Record Examination.
- **TOEFL Score**: Your proficiency in English as indicated by your Test of English as a Foreign Language score.
- **University Rating**: The prestige and rating of the university you attended.
- **SOP**: The strength of your Statement of Purpose.
- **LOR**: The quantity of your Letters of Recommendation.
- **CGPA**: Your Cumulative Grade Point Average.
- **Research**: Your experience in the research field.

By analyzing these factors, the model provides a prediction of your admission chances, giving valuable insights into your graduate school application based on key academic parameters.

---

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Flask
- Waitress (for deployment)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/admission-prediction
    cd admission-prediction
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the app locally**:
    ```bash
    python application.py
    ```

4. **Access the app**:
   Open [http://localhost:8080](http://localhost:8080) in your browser to access the app.

---

## Deployment on Render

This project is hosted on Render, allowing for seamless deployment and scalability.

### How to Deploy on Render

1. **Create a Render account** at [render.com](https://render.com) and link your GitHub repository.
2. **Create a new Web Service** and configure the following settings:
    - **Environment**: Python
    - **Build Command**: `pip install -r requirements.txt`
    - **Start Command**: `python application.py` (or `waitress-serve --port 10000 application:app` if using Waitress directly)
3. **Specify the Python version** in your environment settings, if necessary.
4. Render will build and deploy your app, making it accessible via the provided URL.

### Live Project Link

[View the deployed project on Render](https://admissionprediction-7.onrender.com/)

---

## Acknowledgments

- Flask: Python micro web framework
- Render: Hosting platform for web applications

