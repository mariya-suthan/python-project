# python-project

🎓 Student Performance Prediction System

📌 Overview

This project is a Student Performance Prediction System built using Python and Machine Learning. It predicts a student's total marks, grade, and estimated CGPA based on input subject marks or grade.

The system uses:

Linear Regression → to predict total marks
Logistic Regression → to predict grade

🚀 Features

Predict total marks from subject inputs
Predict grade (A/B/C/D/F)
Estimate CGPA based on predicted total
Grade-based performance estimation
Simple and interactive console interface

🛠️ Technologies Used

Python 
Pandas
NumPy
Matplotlib
Scikit-learn

📂 Project Structure
📁 Student-Performance-Prediction
│── data.csv
│── main.py
│── model_training.py
│── README.md

📊 Dataset

The dataset contains student academic details such as:
Maths
Physics
Other subjects
Total marks
Grade

⚙️ How It Works

1. Data Preprocessing
Load dataset
Drop irrelevant columns
Split features (X) and target (y)
2. Model Training
Train Linear Regression model for total marks
Train Logistic Regression model for grade prediction
3. Prediction System
User can choose:
"marks" → Enter subject marks
"grade" → Enter grade

▶️ Usage

Run the program:
python main.py
Option 1: Marks Prediction
Enter 'marks' or 'grade': marks
Maths: 85
Computer_Science: 90
...

Predicted Total: 450.25
Predicted Grade: A
Estimated CGPA: 9.2
Option 2: Grade-Based Prediction
Enter 'marks' or 'grade': grade
Enter Grade (A/B/C/D/F): A

Estimated Total: 460.00
Estimated CGPA: 9.4

📈 Visualization

The project includes a scatter plot:
plt.scatter(df['Maths'], df['Computer_Science'])
This helps analyze the relationship between subjects.

❗ Common Errors

Error: NameError: name 'X' is not defined

✔ Fix: Make sure you define X before using it:

X = df.drop(['Total', 'Grade'], axis=1)

🔮 Future Improvements

Add GUI using Tkinter / Web App
Integrate real-time student database
Improve model accuracy
Add more subjects and features

👨‍💻 Author

Mariya Suthan
AI & Data Science Student
