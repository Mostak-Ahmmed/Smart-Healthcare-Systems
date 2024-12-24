# Disease Prediction and Medical Recommendation System

This project is a machine learning-based web application designed to predict diseases based on symptoms provided by the user. It also provides medical recommendations, including precautions, medications, dietary suggestions, and workout routines to manage the predicted disease.

---

## Features

- **Symptom-Based Disease Prediction**:
  - Users can input symptoms to receive a predicted disease.
- **Medical Recommendations**:
  - Precautions, medications, diet plans, and workouts are provided for each predicted disease.
- **Error Handling**:
  - Handles misspelled symptoms using fuzzy matching.
  - Suggests alternative symptoms if the input is not found in the database.
- **Interactive User Interface**:
  - Clean and user-friendly interface powered by Flask and Bootstrap.
- **Pre-trained Random Forest Model**:
  - A machine learning model trained on a comprehensive dataset to provide accurate predictions.

---

## Technologies Used

- **Backend**:
  - Flask (Python)
- **Frontend**:
  - HTML, CSS, Bootstrap
- **Machine Learning**:
  - Random Forest Classifier
- **Libraries**:
  - Pandas, NumPy, FuzzyWuzzy, Scikit-learn, Matplotlib, Seaborn
- **Data**:
  - Kaggle datasets for symptoms, diseases, precautions, medications, diets, and workouts.

---

## Installation

### Prerequisites

- Python 3.8 or above
- Virtual environment (optional but recommended)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/disease-prediction.git
   cd disease-prediction
