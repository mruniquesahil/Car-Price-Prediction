# 🚗 Car Price Prediction

This project predicts the price of a car based on various features using Machine Learning. It provides an interactive user interface built with Streamlit, making it easy for users to input details and get real-time predictions.

## 🛠️ Technologies & Libraries Used

- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical computations
- Matplotlib – Data visualization
- Scikit-learn – Model building and evaluation
- Joblib – Model saving/loading
- Streamlit – Web application framework

## 💡 Project Highlights

- Cleaned and preprocessed car dataset
- Trained regression model using Scikit-learn
- Model saved with Joblib for efficient loading
- Interactive Streamlit web app for prediction
- Simple and user-friendly interface
- Real-time price prediction based on input features

## 🚀 How to Run the Project Locally

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   cd car-price-prediction

2. Install the dependencies
   pip install -r requirements.txt

3. Run the Streamlit app
   streamlit run app.py


Project Structure ---

car-price-prediction/
│
├── app.py                  # Streamlit web app
├── model.pkl               # Trained ML model (saved using joblib)
├── data/
│   └── car_data.csv        # Car dataset
├── images/                 # Optional: Visualizations or screenshots
├── requirements.txt        # List of required Python packages
└── README.md               # Project documentation
