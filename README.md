# 🏏 IPL Match Win Probability Predictor

Predict the probability of a team winning an IPL match based on real-time match data using machine learning.

## 📁 Project Structure

- `IPL_Probability_Predictor.ipynb`: Jupyter Notebook for data analysis, feature engineering, and model training.
- `app.py`: Flask application to serve the model for real-time predictions.
- `city.pkl`, `team.pkl`, `model.pkl`, `pipe.pkl`: Serialized models and encoders.
- `Data/`: Contains datasets related to IPL matches and player statistics.

## 🏏 Data Sources
- IPL match data including ball-by-ball deliveries, match results, team statistics, and player stats.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Flask
- Jupyter Notebook
- Pickle
- 
## 📈 Features
- Predicts win probability during a live IPL match based on match context.
- Built using Machine Learning classification techniques.
- Deployable using Flask backend.


## 📸 Usage

1. Open the application in your browser.
2. Enter the match details (e.g., batting team, bowling team, overs, runs).
3. Click "Predict" to see the win probability.

```bash
python app.py



### Prerequisites

- Python 3.x
- Install dependencies:

