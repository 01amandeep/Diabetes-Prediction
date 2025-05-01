# 🩺 Diabetes Prediction Website

A web application that uses machine learning to predict the likelihood of diabetes in a patient based on medical data inputs.

## 🚀 Features

- Predict diabetes using user input health metrics.
- Clean and user-friendly interface.
- Machine Learning model trained on real healthcare data (e.g., PIMA Indian Diabetes Dataset).
- Real-time predictions via web interface.
- Deployed and accessible online.

## 🧠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript / React (optional)
- **Backend**: Flask / Django / Node.js
- **Machine Learning**: Scikit-learn / TensorFlow / XGBoost
- **Model**: Trained using [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Deployment**: Heroku / Render / AWS / Azure

## 📊 Inputs for Prediction

The model takes the following health parameters as input:

- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-webapp.git
   cd diabetes-prediction-webapp
   ```

2. **Create a virtual environment and activate it**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scriptsctivate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

   Open [http://localhost:5000](http://localhost:5000) in your browser.

## 📁 Project Structure

```
├── app.py                 # Main Flask/Django app
├── model.pkl              # Trained ML model
├── templates/
│   └── index.html         # Web page template
├── static/
│   └── style.css          # Styling (if used)
├── requirements.txt       # Python dependencies
└── README.md              # Project overview
```

## 📷 Screenshots

_Add a few screenshots of the web interface here if available._

## 📚 Acknowledgements

- [Kaggle PIMA Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Scikit-learn
- Flask / Django Documentation

## ⚖️ License

This project is open source under the [MIT License](LICENSE).
