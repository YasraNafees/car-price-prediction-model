Car Price Prediction Model

📌 Project Overview
This project is a machine learning model that predicts car prices based on various features like make, model, mileage, condition, and year. It uses **Scikit-Learn** for training and **Streamlit** for deployment, allowing users to interactively input car details and get estimated prices.

 🚀 Features
- Predicts car prices based on input features.
- Uses Random Forest Regressor for accurate predictions.
- Encodes categorical variables like car make & model.
- Interactive Streamlit web app for user-friendly predictions.

 🔧 Installation
To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/YasraNafees/car-price-prediction-model.git
   ```
2. Navigate to the project folder:
   ```bash
   cd car-price-prediction-model
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

 📝 Usage
1. Open the Streamlit web app.
2. Enter details like car make, model, year, mileage, and condition.
3. Click Predict to get the estimated price.

 📂 Project Structure
```
car-price-prediction-model/
│── model/                # Trained ML model
│── data/                 # Dataset used for training
│── app.py                # Streamlit web app
│── requirements.txt       # Required dependencies
│── README.md             # Project documentation
```

 📊 Model Training
- Dataset: Preprocessed CSV dataset with car details.
- Encoding: Label Encoding for categorical features.
- Model: Random Forest Regressor trained using Scikit-Learn.

🛠 Technologies Used
- Python
- Scikit-Learn (Machine Learning)
- Streamlit (Web App)
- NumPy & Pandas (Data Processing)
- Matplotlib & Seaborn (Visualization)

🤝 Contributing
Feel free to contribute! Fork this repository, create a feature branch, and submit a pull request.

 📜 License
This project is open-source under the MIT License.

---


