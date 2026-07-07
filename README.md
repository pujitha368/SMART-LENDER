# 🏦 SmartLender - Loan Prediction Web Application

SmartLender is a Machine Learning-driven web application designed to predict whether a loan application will be approved or not. By analyzing user inputs such as gender, income, credit history, and education level, the system provides an instant, automated assessment.

---

## 🚀 Features
* *Data Cleaning & Preprocessing:* Handles missing values (null values) and optimizes skewed distributions using Python's Pandas library.
* *Robust ML Model:* Utilizes a trained GradientBoostingClassifier optimized for accurate tabular data classification.
* *User-Friendly UI:* Built an intuitive front-end interface using HTML/CSS that interacts seamlessly with the Flask backend.

---

## 🛠️ Technologies Used
* *Backend:* Python, Flask
* *Machine Learning:* Scikit-learn, Pandas, NumPy
* *Data Visualization:* Seaborn, Matplotlib
* *Frontend:* HTML5, CSS3

---

## 📂 Project Structure
```text
SmartLender-Application/
│
├── Flask/
│   ├── appy1.py              # Main Flask web server code
│   └── templates/
│       ├── home.html         # Landing/Home page UI
│       ├── input.html        # Form page for user feature input
│       └── output.html       # Result page displaying the final prediction
│
├── Dataset/
│   └── loan prediction using ml.ipynb   # Jupyter Notebook containing model training
│
├── rdf.pkl                   # Serialized/Saved Machine Learning model file
└── scaler.pkl                # Serialized Data Scaler file for normalization

💻 How to Run Locally
1. Clone or Download the Project:
git clone [[https://github.com/your-username/SmartLender-Application.git](https://github.com/pujitha368/SMART-LENDER.git)]
cd SmartLender-Application/Flask

2. Install Dependencies:
pip install flask numpy pandas scikit-learn

3. Start the Flask Server:
python appy1.py

4. Access the App:
Open your preferred web browser and navigate to:
[http://127.0.0.1:5000/](http://127.0.0.1:5000/)

🔮 Future Enhancements
 * Implementing additional algorithms (like XGBoost or Random Forest) to further boost prediction accuracy.
 * Integrating a persistent relational database (MySQL/PostgreSQL) to store user history and application profiles.
 * Deploying the application live onto cloud environments like Render or AWS for public accessibility.

C:\Users\welcome\Pictures\website\web1 (2).png

C:\Users\welcome\Pictures\website\form.png

C:\Users\welcome\Pictures\website\web2.png

C:\Users\welcome\Pictures\website\form 2.png

C:\Users\welcome\Pictures\website\web 3.png























