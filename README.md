# IPL Winning Team Predictor

## Project Overview

The IPL Winning Team Predictor is a machine learning project designed to estimate the probability of a team winning in the Indian Premier League (IPL) based on various match conditions. This project utilizes historical match data and a predictive model to provide insights into potential match outcomes.

## 🎯 Key Points from the IPL Win Predictor Project:

1. Data Preprocessing: The IPL dataset is loaded and cleaned, handling missing values, encoding categorical variables, and preparing the data for modeling.
2. Feature Engineering: The dataset is enriched with relevant features like current score, runs left, balls left, wickets remaining, current run rate, and required run rate to capture the dynamics of the match.
3. Machine Learning Model: A Logistic Regression model is trained using the Scikit-learn library to predict the probability of the batting team winning.
4. Streamlit App: A user-friendly web application is built using Streamlit, allowing users to input the current match situation and get the predicted probability of the batting team winning.
5. Deployment: The trained model is saved as a pickle file and the Streamlit app is packaged for easy deployment.



## 📚 Detailed Explanation:
The IPL Win Predictor is a comprehensive project that leverages machine learning techniques to predict the outcome of IPL (Indian Premier League) cricket matches. The goal of this project is to provide a user-friendly web application that can help cricket enthusiasts and analysts track the probability of a team winning a match based on the current game situation.

## 🗂️ Data Preprocessing:
The project starts with loading and cleaning the IPL dataset, which includes match details, team information, and performance statistics. The dataset is preprocessed to handle missing values, encode categorical variables, and prepare the data for modeling.

1. **Data Collection**:
   - The project uses two key datasets: `matches.csv` and `deliveries.csv`, which contain comprehensive records of IPL matches.
   - Key features include team names, match outcomes, scores, and additional performance metrics.

2. **Data Exploration**:
   - Conducted exploratory data analysis (EDA) to identify trends and patterns in match outcomes.
   - Analyzed factors such as total runs, wickets taken, and the impact of toss decisions on match results.


## 🧠 Feature Engineering:
To capture the dynamic nature of a cricket match, the project engineers several features from the dataset, such as the current score, runs left, balls left, wickets remaining, current run rate, and required run rate. These features are crucial in predicting the outcome of a match, as they reflect the evolving game situation.

## 🤖 Machine Learning Model:
The heart of the project is the Logistic Regression model trained using the Scikit-learn library. This model is chosen for its simplicity and interpretability, allowing for easy understanding of the factors contributing to the predicted probability of a team winning.
 **Model Development**:
   - Built a predictive model using a machine learning pipeline.
   - The model was trained on historical match data to learn patterns that affect match outcomes.
   - Key features used for prediction include:
     - Batting team
     - Bowling team
     - Host city
     - Runs left
     - Balls left
     - Wickets remaining
     - Current run rate (CRR)
     - Required run rate (RRR)


## 🖥️ Streamlit App:
To make the predictions accessible and user-friendly, a Streamlit web application is developed. The app allows users to input the current match situation, including the batting team, bowling team, target score, current score, overs, and wickets lost. The app then displays the predicted probability of the batting team winning.

1. **Streamlit Application**:
   - Developed an interactive web application using Streamlit, enabling users to input real-time match scenarios.
   - Users can select the batting and bowling teams, enter target scores, current scores, overs completed, and wickets lost.
   - The application outputs the predicted winning probabilities for both teams.

2. **User Interface**:
   - Designed a user-friendly interface that simplifies the prediction process.
   - The app provides instant feedback, displaying win probabilities in an easily digestible format.


## 🚀 Deployment:
The trained machine learning model is saved as a pickle file, and the Streamlit app is packaged for easy deployment. This ensures that the IPL Win Predictor can be accessed and used by cricket enthusiasts and analysts alike, providing real-time insights into the match dynamics.

## Getting Started

To run the application locally:

1. Clone the repository

2. Install the required packages using pip:
   cmd: pip install -r requirements.txt

3. Run the Streamlit app:
   cmd: streamlit run app.py
   

## 🌟 Conclusion:
The IPL Win Predictor project showcases the power of machine learning in sports analytics. By combining data preprocessing, feature engineering, and predictive modeling, this project offers a valuable tool for understanding and analyzing the outcomes of IPL matches. The Streamlit-based web application makes the predictions accessible and easy to use, empowering cricket fans and professionals to make more informed decisions and gain deeper insights into the game.
