# 🛸 UFO Appearance Prediction Web App 👽

This project is a **machine learning-powered web app** that predicts the likely country where a UFO sighting was reported, based on:

- The number of **seconds** of the sighting  
- The **latitude**  
- The **longitude**  

The app is built with **Flask** and integrates a trained **Scikit-learn model** for predictions.

---

## 🚀 Inspiration & Source
This project was created as part of the [**Machine Learning for Beginners Curriculum**](https://microsoft.github.io/ML-For-Beginners/#/3-Web-App/1-Web-App/README) by Microsoft.  

I followed their lesson on **"Build a Web App"**, where I learned how to:
- Train and save a ML model with Scikit-learn  
- Use the saved model inside a Flask application  
- Build a simple web interface to make predictions  

---

## 🛠️ Tech Stack
- **Python** (Flask, NumPy, Scikit-learn, Pickle)  
- **HTML, CSS** for the frontend  
- **Flask** for the backend web server  

---

## 📂 Project Structure
```bash
ufo-prediction-app/
│── Notebook.ipynb          # Jupyter Notebook for training the model
│── ufo-model.pkl           # Trained ML model
│── ufos.csv                # Dataset
│── README.md               # Documentation
│
└── web-app/
    │── app.py              # Flask web app
    │── requirements.txt    # Dependencies
    │
    ├── templates/
    │   └── index.html      # Web interface
    │
    └── static/
        └── css/
            └── styles.css  # Styling
```

---

## 🎯 How It Works
1. User enters:
   - Duration in seconds (integer)  
   - Latitude (integer)  
   - Longitude (integer)  

2. Flask passes the inputs to the ML model.  
3. The model predicts the **country** most likely to have reported the UFO sighting.  

---

## 🖼️ Demo Screenshot
![Demo Screenshot](ufos.jpg)

---

## 📊 Dataset
The dataset comes from [Kaggle UFO Sightings Dataset](https://www.kaggle.com/NUFORC/ufo-sightings).

---

## 🙏 Credits
- **Curriculum:** [Machine Learning for Beginners](https://microsoft.github.io/ML-For-Beginners/) by Microsoft  
- **Lesson Author:** Jen Looper ♥️  
- **Quiz Author:** Rohan Raj  
- **Dataset Source:** Kaggle (NUFORC UFO Sightings)  
- **App Deployment Inspiration:** [Towards Data Science article](https://towardsdatascience.com/how-to-easily-deploy-machine-learning-models-using-flask-b95af8fe34d4) by Abhinav Sagar  

---

## 👨‍💻 Author
Built with ♥️ by **Gandharv Kulkarni**  
