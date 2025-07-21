# 🏥 Health Insurance Cost Prediction Web App

A Machine Learning-based web application to predict health insurance costs using real-world user inputs such as age, BMI, region, smoker status, etc. Built using **Python**, **Streamlit**, and **Scikit-learn**, this project showcases end-to-end development from data preprocessing to deployment of a predictive model.

---

## 🔧 Features

- Real-time health insurance cost prediction
- Streamlit-powered interactive web interface
- Trained on real insurance dataset (`insurance.csv`)
- Gradient Boosting Regression Model used for accurate predictions
- Clean, responsive user interface

---

## 📌 Input Parameters

- **Age** – Age of the applicant
- **Sex** – Male / Female
- **BMI** – Body Mass Index
- **Children** – Number of children covered by health insurance
- **Smoker** – Yes / No
- **Region** – One of ['northeast', 'northwest', 'southeast', 'southwest']

---

## 💻 Technologies Used

- **Python**
- **Streamlit**
- **Pandas**, **NumPy**
- **Scikit-learn** (GradientBoostingRegressor)
- **Joblib** (Model serialization)

---

## 🚀 How to Run the Project Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/health-insurance-cost-predictor.git
   cd health-insurance-cost-predictor
2 .pip install -r requirements.txt

3. streamlit run Insurancecost_streamlit.py


📁 Project Structure

├── insurance.csv                  # Dataset
├── model_joblib_gb               # Trained ML model
├── Insurancecost_streamlit.py    # Streamlit UI for prediction
├── Health Insurance cost prediction.py  # Model training and preprocessing
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation

