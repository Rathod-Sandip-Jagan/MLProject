## End to End Machine Learning Project

# 📊 Student Performance Indicator

## 🧠 Problem Statement
This project aims to analyze how a student's academic performance (measured through test scores in math, reading, and writing) is influenced by various socio-demographic factors such as:
- Gender
- Ethnicity
- Parental level of education
- Lunch type
- Completion of a test preparation course

## 📥 Dataset Information

- **Source**: [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)
- **Size**: 1000 rows × 8 columns
- **Attributes**:
  - `gender`: Gender of student (Male/Female)
  - `race/ethnicity`: Student’s ethnic group (Group A–E)
  - `parental level of education`: Final education level of parents (e.g., Bachelor's, Master's)
  - `lunch`: Type of lunch before test (Standard or Free/Reduced)
  - `test preparation course`: Whether the test prep course was completed
  - `math score`: Score in the math test (0–100)
  - `reading score`: Score in the reading test (0–100)
  - `writing score`: Score in the writing test (0–100)

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Flask (for deployment)
- Jupyter Notebook

## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Rathod-Sandip-Jagan/MLProject.git
   cd MLProject

Create and Activate Virtual Environment
python -m venv venv
venv\Scripts\activate     # Windows
source venv/bin/activate  # macOS/Linux

Install Requirements
pip install -r requirements.txt

Run the Application
python app.py

💡 Features
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
ML Model for performance prediction
Flask Web App for prediction
Pickled model and preprocessor pipeline
Exception handling & logging

📁 Project Structure
student-performance-indicator/
│
├── artifacts/               # Saved models and preprocessors
├── data/                    # Raw or cleaned datasets
├── notebooks/               # Jupyter notebooks for EDA and modeling
├── src/
│   ├── components/          # Data ingestion, transformation, model trainer
│   ├── pipelines/           # Training and prediction pipeline
│   ├── utils.py             # Utility functions
│   └── exception.py         # Custom exception handling
│
├── templates/               # HTML templates for Flask
├── static/                  # Static files like CSS, JS
├── app.py                   # Flask application entry point
├── requirements.txt
└── README.md

📌 To-Do / Future Improvements
Add more evaluation metrics and visualizations
Deploy on cloud (e.g., Heroku, AWS)
Add a frontend form for user input
Use Streamlit for better UI experience

👨‍💻 Author
Sandip Rathod
GitHub: @Rathod-Sandip-Jagan