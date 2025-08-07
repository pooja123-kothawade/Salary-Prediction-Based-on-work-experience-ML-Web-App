
Procedure--
Open command Prompt and go to given directory and then run python app.py
**WageWatcher - Flask Salary Predictor** project, based on the structure in your screenshot:

---

```md
# WageWatcher - Flask Salary Predictor

This project predicts the salary of an employee based on their years of experience using a machine learning model and serves predictions via a Flask web application.

## 🔧 Tech Stack

- **Language**: Python  
- **Framework**: Flask  
- **Machine Learning**: Linear Regression  
- **Libraries**: Pandas, NumPy, Scikit-learn, Pickle  
- **Frontend**: HTML, CSS  
- **Tools**: Git, Postman

---

## 📁 Project Structure

```

├── assets/                 # Image or style assets
├── static/                 # Static files (CSS, JS)
├── templates/              # HTML files (index.html, result.html, etc.)
├── Salary\_Data.csv         # Dataset used for training
├── model.py                # Model training and serialization
├── app.py                  # Flask app with routing and API logic
├── request.py              # Script to send API requests
├── requirements.txt        # List of dependencies

````

---

## 📊 Model

- **model.py**:  
  Trains a linear regression model using `Salary_Data.csv` and serializes it into a `.pkl` file using Pickle.

---

## 🌐 Web Application

- **app.py**:  
  The main Flask application file that handles routing, model loading, and prediction logic.
  
- **index.html**:  
  Frontend page where the user enters their years of experience.

- **Prediction Flow**:
  1. User inputs experience on the frontend.
  2. Flask receives the input and sends it to the model.
  3. Predicted salary is returned and displayed.

---

## ▶️ How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/pooja123-kothawade/WageWatcher-ML-Web-App.git
   cd WageWatcher-ML-Web-App
````

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model** (optional - already saved):

   ```bash
   python model.py
   ```

4. **Start the Flask server**:

   ```bash
   python app.py
   ```

5. **Visit the app** in your browser:

   ```
   http://127.0.0.1:5000/
   ```

---

## ✅ Features

* Simple and interactive UI.
* Real-time salary prediction.
* Clean API architecture.
* Easy to extend with new models or features.

---

## 📸 Screenshots

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/617d5e00-a9ef-4862-a121-3faeb2a90f8e" />


---

## 🙋‍♀️ Author

**Pooja Kothawade**
📧 [kothawadapooja25@gmail.com](mailto:kothawadapooja25@gmail.com)
🌐 [GitHub](https://github.com/pooja123-kothawade) | [LinkedIn](https://www.linkedin.com/in/pooja-kothawade/)

---


```

---

Let me know if you'd like this in a downloadable `.md` file or want to enhance it with a **live demo badge**, **API endpoints description**, or **Docker setup**.
```
