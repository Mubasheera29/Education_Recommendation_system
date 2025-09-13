Student Study Recommendation System 🎓📊

This project is a Machine Learning + Flask web application that recommends suitable study areas and professions for students based on their academic performance, study habits, and other personal factors.

The workflow starts from data analysis in Jupyter Notebook (model training) and then transitions into a Flask web app for interactive use.


Workflow

1. Dataset Collection

   * Source: Kaggle Dataset (Student Performance dataset).
   * The dataset includes details like gender, part-time job, study hours, subject scores, extracurricular activities, etc.

2. Model Training in Jupyter Notebook

   * Loaded dataset in Jupyter Notebook.
   * Performed preprocessing (handling categorical values, scaling).
   * Trained multiple ML models and selected the best one.
   * Saved final model and scaler as:
     model.pkl
     scaler.pkl

3. Flask Web App (PyCharm)

   * Built a Flask application (app.py).
   * Created home.html, recommend.html, and result.html for user interaction.
   * Integrated ML model to give real-time predictions based on user inputs.

4. Deployment

   * Can be deployed to Heroku / Render / PythonAnywhere.
   * Local testing supported with flask run.



Features

* Student data input form (gender, part-time job, study hours, scores, etc.)
* Auto-calculates Total Score and Average Score.
* Predicts top recommended studies/profession with probabilities.
* Clean and simple UI using Bootstrap 4.
* "Go Back" navigation between pages.



Project Structure

project-folder/
│
├── app.py                  → Flask app entry point
├── Models/                 → Saved ML model and scaler
│   ├── model.pkl
│   └── scaler.pkl
├── templates/              → HTML templates
│   ├── home.html
│   ├── recommend.html
│   └── result.html
├── static/                 → Static files (images, css, etc.)
├── notebook/               → Jupyter notebook used for training
│   └── student\_model.ipynb
├── requirements.txt        → Python dependencies
└── README.md               → Project documentation

Author
Mubasheera Fatima ✨


