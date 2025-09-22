# project
📘 Student Performance Prediction (xAPI-Edu-Data)
📌 Overview

This project uses the xAPI-Edu-Data dataset to analyze and predict student academic performance.
The dataset contains demographic, social, and academic features of students and their corresponding performance labels.
By applying data analysis and machine learning techniques, this project aims to identify key factors affecting performance and build predictive models.

📂 Dataset

File: xAPI-Edu-Data.csv

Source: UCI Machine Learning Repository
.

Size: ~480 student records.

Target Variable: Class (performance level: High, Medium, Low).

Key Features

gender – Male/Female

NationalITy – Nationality of student

PlaceofBirth – Student's place of birth

StageID – Educational level (Lower, Middle, High school)

GradeID – Grade classification

SectionID – Class section

Topic – Course subject (Math, Biology, etc.)

Semester – First/Second

ParentAnsweringSurvey, ParentschoolSatisfaction – Parent feedback

StudentAbsenceDays – Number of absence days

Class – Performance level (target variable)

⚙️ Installation & Setup

Clone the repo and install required libraries:

git clone https://github.com/your-username/student-performance-prediction.git
cd student-performance-prediction
pip install -r requirements.txt

Requirements

Python 3.8+

pandas

numpy

matplotlib

seaborn

scikit-learn

🚀 Usage

Upload the dataset into your Google Colab or project folder.

Run the notebook/script:

python main.py


Or open the Jupyter/Colab notebook and run all cells.

📊 Project Workflow

Data Exploration

Load dataset

Handle missing values

Explore categorical distributions

Data Preprocessing

Encode categorical variables

Normalize/scale features if needed

Train-test split

Visualization

Distribution plots of features

Correlation heatmaps

Class imbalance check

Model Building

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

Compare accuracy, precision, recall, F1-score

Results

Model evaluation metrics

Feature importance analysis

Insights & recommendations

📈 Expected Output

Student performance predictions: High / Medium / Low

Accuracy ~70–85% (depending on model)

Feature importance insights (e.g., absences & parental satisfaction strongly affect performance).

🏆 Applications

Identify at-risk students early

Help educators/parents improve academic outcomes

Provide data-driven strategies for better learning

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to improve.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
