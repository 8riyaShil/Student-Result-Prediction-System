# 🎓 Student Result Prediction System

A Machine Learning project that predicts student academic performance based on study habits and historical academic data using Linear Regression.

## 📌 Overview

The Student Result Prediction System is designed to estimate a student's final marks by analyzing key performance indicators such as:

- Study Hours
- Attendance Percentage
- Previous Marks
- Assignment Scores

The project demonstrates the complete Machine Learning workflow, including data generation, preprocessing, visualization, model training, prediction, and evaluation.

## 🚀 Features

- Synthetic student dataset generation
- Data visualization using Matplotlib
- Student marks prediction using Linear Regression
- Model performance evaluation
- Error analysis and visualization
- CSV dataset export for future use

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## 📊 Machine Learning Workflow

### 1. Dataset Generation

A dataset of 250 student records is generated with the following attributes:

| Feature | Description |
|----------|-------------|
| StudyHours | Daily study hours |
| Attendance | Attendance percentage |
| PreviousMarks | Previous examination marks |
| AssignmentScore | Assignment performance score |
| Marks | Final predicted marks |

### 2. Data Visualization

Visualizations help understand relationships between features and student performance.

### 3. Model Training

A Linear Regression model is trained using the generated dataset.

### 4. Prediction

The model predicts student marks based on the input features.

### 5. Model Evaluation

Performance is measured using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 📈 Visualizations

### Study Hours vs Marks

Shows the relationship between study time and academic performance.

### Actual vs Predicted Marks

Compares model predictions with actual marks.

### Error Distribution

Displays the prediction errors across the test dataset.

## 📂 Project Structure

```text
Student-Result-Prediction-System/
│
├── Student_Result_Prediction_System.ipynb
├── student_data.csv
├── requirements.txt
├── README.md
└── images/
    ├── study_hours_vs_marks.png
    ├── actual_vs_predicted.png
    └── error_distribution.png
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Student-Result-Prediction-System.git
```

Move into the project directory:

```bash
cd Student-Result-Prediction-System
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Student_Result_Prediction_System.ipynb
```

Run all cells to execute the project.

## 📋 Requirements

```text
pandas
numpy
matplotlib
scikit-learn
jupyter
```

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Data Preprocessing
- Exploratory Data Analysis
- Machine Learning Fundamentals
- Linear Regression
- Model Evaluation
- Data Visualization
- Python Programming

## 🔮 Future Enhancements

- Support for real student datasets
- Multiple Machine Learning algorithms
- Feature engineering techniques
- Hyperparameter tuning
- Web-based prediction interface using Flask or Streamlit
- Advanced analytics dashboard

## 👩‍💻 Author

**Riya Shil**

BCA Student (3rd Year, 6th Semester)

DSMS College of Tourism and Management

### Connect with Me

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile

---

⭐ If you found this project useful, consider giving it a star on GitHub!
