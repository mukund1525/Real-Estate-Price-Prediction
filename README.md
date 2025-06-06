

## 🏠 Real Estate Price Prediction Web App

A machine learning web application to predict house prices based on key property features such as location, area, number of rooms, and amenities. The project includes end-to-end development from data preprocessing to model deployment using Flask.

---

### 📂 Project Structure

```
├── app/                      # Flask app files (routes, templates, static files)
│   ├── templates/
│   ├── static/
│   └── app.py
├── models/                   # Trained ML models (pickle files)
├── notebooks/                # Jupyter notebooks for EDA and model building
├── data/                     # Raw and cleaned datasets
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation
```

---

### 🧰 Tech Stack

* **Python**
* **Pandas**, **NumPy**
* **Scikit-learn**
* **Matplotlib**, **Seaborn**
* **Flask (Web Framework)**
* **HTML/CSS/JavaScript** (Frontend)

---

### 📊 Problem Statement

To build a model that can accurately predict the price of real estate properties based on their features. The application allows users to input property details and receive an estimated price in real-time.

---

### 🔍 Key Features

* Data preprocessing (outlier removal, feature encoding, missing value handling)
* Feature selection and scaling
* Regression modeling (Linear Regression, Decision Tree, Random Forest)
* Model evaluation using MAE, RMSE, R²
* Interactive web interface with Flask
* Clean UI for user input and prediction display

---

### 📁 Dataset

* Source: [Kaggle](https://www.kaggle.com) or simulated data
* Features: Area, Location, BHK, Bathroom, Balcony, Parking, Age, etc.
* Target: Property Price (in Lakhs or INR)

---

### ⚙️ How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/real-estate-price-prediction.git
   cd real-estate-price-prediction
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask app:

   ```bash
   cd app
   python app.py
   ```

4. Visit `http://127.0.0.1:5000` in your browser.

---

### 📈 Model Performance

| Model             | R² Score | RMSE |
| ----------------- | -------- | ---- |
| Linear Regression | 0.82     | 2.3  |
| Decision Tree     | 0.89     | 1.7  |
| Random Forest     | 0.91     | 1.4  |

---

### 🚀 Future Enhancements

* Add location-based heatmap
* Integrate database for property storage
* Deploy the app on Render/Heroku
* Add user authentication and admin dashboard

---

### 📩 Contact

**Mukund Mane**
📧 [manemukund8112@gmail.com](mailto:manemukund8112@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/mukund-mane-43604220b/)

