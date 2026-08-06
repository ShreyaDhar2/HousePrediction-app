# HousePrediction-app
Predict house price based on the house size

Link : https://build-house-price-prediction-app.streamlit.app/



 🏡 House Price Prediction App

A Machine Learning web application designed to predict house prices based on various features such as location, total square footage and key property metrics.


 📌 Features

- Interactive User Interface: Simple and intuitive web interface for inputting property details.
- Accurate Machine Learning Model: Predicts estimated property prices based on trained historical real estate data.
- Data Preprocessing & Encoding: Automated handling of categorical features (e.g., location, property type) and missing values.



🛠️ Tech Stack

- Frontend / Web Framework: Streamlit 
- Programming Language: Python 
- Data Manipulation & Analysis: Pandas, NumPy
- Machine Learning Libraries: Scikit-Learn (Linear Regression, Decision Trees, Random Forest)
- Model Storage: Pickle 
- Visualization (Notebooks):Matplotlib, Seaborn


📂 Project Structure

```text
HousePrediction-app/
│
├── data/
│   └── housing_data.csv        # Dataset used for training and testing
│
├── models/
│   └── model.pkl               # Saved Machine Learning model
│
├── notebooks/
│   └── model_building.ipynb   # Exploratory Data Analysis & Model Training
│
├── app.py                      # Main application entry point (Flask/Streamlit)
├── requirements.txt            # Python dependencies
├── .gitignore                  # Files and folders to ignore in Git
└── README.md                   # Project documentation
```

 🚀 Getting Started

Follow these instructions to set up and run the project locally.

 Prerequisites

Ensure you have Python 3.8 or higher installed on your machine.

 Installation

1. Clone the Repository:
bash
git clone [https://github.com/ShreyaDhar2/HousePrediction-app.git](https://github.com/ShreyaDhar2/HousePrediction-app.git)
cd HousePrediction-app




2. Create a Virtual Environment (Recommended):
bash
 On Windows
python -m venv venv
venv\Scripts\activate

 On macOS/Linux
python3 -m venv venv
source venv/bin/activate


3. Install Dependencies:
bash
pip install -r requirements.txt





 🎯 Usage

1. Run the Application:
bash
streamlit run app.py




2. Open in Browser:
Navigate to http://localhost:8501 (for Streamlit) 
3. Predict: Enter the property metrics (square feet) and click Predict Price to view the estimated value.



 📊 Model & Workflow

1. Data Cleaning: Handled missing values, removed outliers, and formatted data types.
2. Feature Engineering: Performed One-Hot Encoding for location categorical features and feature scaling.
3. Model Selection: Evaluated multiple regression algorithms (Linear Regression, Lasso, Random Forest) using Cross-Validation.
4. Hyperparameter Tuning: Fine-tuned the best-performing model to achieve optimal $R^2$ score and low RMSE.








