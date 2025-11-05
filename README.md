

🎓 AI-Based Student Dropout Risk Prediction

This project uses machine learning to predict whether a student is at risk of dropping out based on their academic, demographic, and behavioral data.
The model helps educational institutions identify at-risk students early and take preventive actions.

🚀 Features

Data preprocessing and encoding of categorical variables

Model training using Random Forest Classifier

Accuracy and classification report evaluation

Visualization of confusion matrix and feature importance



---

🧠 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (sklearn)



---

⚙️ Installation

1. Clone this repository:

git clone https://github.com/jerripothulalahari/student-dropout-prediction
cd student-dropout-prediction


2. Install dependencies:

pip install -r requirements.txt


3. Add your dataset:

Place your dataset file (student_data.csv) in the project folder.

Ensure it contains a Dropout column (values like Yes or No).





---

🧾 Usage

Run the script using:

python dropout_prediction.py

The script will:

1. Load and preprocess the dataset


2. Train a Random Forest model


3. Predict dropout risks


4. Display evaluation metrics and visualizations




---

📊 Output Examples

✅ Model Evaluation

Accuracy: 0.89

Classification Report:
              precision    recall  f1-score   support
           0       0.90      0.92      0.91        50
           1       0.87      0.85      0.86        40
    accuracy                           0.89        90

🔵 Confusion Matrix

A heatmap showing actual vs predicted dropout outcomes.

⭐ Feature Importance

A bar chart highlighting the top 5 most influential features contributing to dropout prediction.


---

📈 Future Improvements

Integrate with a Flask/Django web dashboard

Use Deep Learning models (e.g., Neural Networks)

Add real-time prediction API

Expand dataset for better generalization



---

🤝 Contributing

Contributions are welcome!
Feel free to fork this repo, make improvements, and submit a pull request.


---

📜 License

This project is licensed under the MIT License.
