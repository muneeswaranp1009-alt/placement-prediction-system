# placement-prediction-system
A Machine Learning project that predicts whether a student is likely to get placed based on academic performance, aptitude score, communication skills, project experience, and internship status using Logistic Regression. The project also includes data visualization, model evaluation, and probability-based predictions.


# 🎓 Student Placement Prediction System

A Machine Learning project built with Python and Scikit-learn that predicts whether a student is likely to get placed based on their academic and skill-related attributes.

## 🚀 Features

- Predicts student placement status
- Uses Logistic Regression algorithm
- Displays placement probability
- Model evaluation with:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix
- Data visualization using Matplotlib
- Saves trained model using Joblib

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Joblib

---

## 📊 Input Features

The model uses the following features:

- CGPA
- Aptitude Score
- Communication Skill
- Number of Projects
- Internship Status (Yes/No)

---

## 📂 Project Structure

```
project/
│
├── students_data.csv
├── placement_model.pkl
├── placement_prediction.py
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/muneeswaranp1009-alt/placement-prediction-system.git
```

Install dependencies:

```bash
pip install pandas matplotlib scikit-learn joblib
```

Run the project:

```bash
python placement_prediction.py
```

---

## 📈 Model Performance

The project evaluates the model using:

- Accuracy Score
- Classification Report
- Confusion Matrix

It also generates visualizations for:

- Placement Count Distribution
- CGPA vs Placement

---

## 💡 Example Input

```
8.5,85,90,4,1
```

Where:

- CGPA = 8.5
- Aptitude = 85
- Communication = 90
- Projects = 4
- Internship = Yes (1)

---

## 🎯 Future Improvements

- Add Streamlit/Flask web interface
- Support multiple ML algorithms
- Hyperparameter tuning
- Feature engineering
- Deploy on cloud

---

## 👨‍💻 Author

Developed as a Machine Learning project for student placement prediction using Logistic Regression.

If you found this project useful, don't forget to ⭐ the repository.
