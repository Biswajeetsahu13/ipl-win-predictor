# 🏏 IPL Win Predictor

The IPL Win Predictor is a Machine Learning project that predicts the winning probability of a team during an IPL match based on current match conditions such as score, overs, wickets remaining, and target.

## 📊 Features

- Predicts real-time win probability
- Uses IPL historical match data
- Interactive Streamlit dashboard
- Match progression analysis
- Machine learning pipeline

## 🧠 Machine Learning Model

Algorithm used: Logistic Regression

Workflow:
1. Data preprocessing
2. Feature engineering
3. OneHotEncoding
4. Model training
5. Probability prediction

Model Accuracy: ~80%

## 📂 Project Structure

ipl-win-predictor
│
├── app.py
├── pipe.pkl
├── matches.csv
├── Untitled.ipynb
├── match_progression.py
└── README.md

## ⚙️ Installation

git clone https://github.com/Biswajeetsahu13/ipl-win-predictor.git  
cd ipl-win-predictor  
pip install streamlit==1.25.0
pip install pandas==1.5.3
pip install scikit-learn==1.2.2

streamlit run app.py

## ▶️ Run the Application

streamlit run app.py

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Matplotlib

## 🚀 Future Improvements

- Add more IPL seasons
- Improve prediction accuracy
- Add live match API
- Deploy the app online

## 👨‍💻 Author

Biswajeet Sahu  
BCA Student | Aspiring Data Analyst  
GitHub: https://github.com/Biswajeetsahu13
