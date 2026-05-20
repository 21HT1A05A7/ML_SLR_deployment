# ML_SLR_deployment
# Salary Prediction System 💰

A Machine Learning web application that predicts salary/GPA values based on SAT scores using a trained predictive model.

---

## Overview

This project allows users to enter an SAT score and predicts the corresponding value using a Machine Learning model integrated with Flask.

The application provides a simple web interface where users can input SAT values and instantly receive prediction results.

---

## Features

✅ User-friendly interface

✅ SAT score input

✅ Real-time prediction

✅ Flask integration

✅ Bootstrap-based responsive design

✅ Machine Learning model prediction

---

## Project Preview

### Home Page

![Home Page](images/home.png)

### Input Form

![Input Form](images/input_form.png)

### Prediction Result

![Prediction Result](images/result.png)

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

---

## Input Feature

| Feature | Description |
|-----------|-------------|
| SAT | Student SAT score |

---

## Project Structure

```bash
Salary-Prediction/
│
├── app.py
├── model.pkl
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── images/
│       ├── home.png
│       ├── input_form.png
│       └── result.png
│
├── README.md
└── requirements.txt
```

---

## How to Run

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/salary-prediction.git
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run Flask Application

```bash
python app.py
```

### Step 4: Open Browser

```bash
http://127.0.0.1:5000/
```

---

## Workflow

1. User enters SAT score
2. Input is sent to Flask backend
3. Backend processes the data
4. Machine Learning model predicts output
5. Prediction result is displayed

---

## Output Example

```text
SAT Score: 1200

Predicted Value: 3.7
```

---

## Future Improvements

- Add multiple input features
- Add visualization charts
- Improve UI design
- Deploy to cloud platforms
- Store prediction history

---

## Author

Project by Kamal  
Data Scientist and NLP Engineer
