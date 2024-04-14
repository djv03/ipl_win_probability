# IPL Win Probability Predictor

## Introduction
The IPL Win Probability Predictor is a machine learning project designed to determine the win probability of a team in an IPL match based on historical data. This project utilizes data from IPL matches from the years 2009 to 2017, including both per delivery and per match information.

## Data
This project uses the following datasets:
1. Per delivery data from IPL matches from 2009 to 2017.
2. Per match data for the same period.

These datasets encompass a wide range of match situations, providing a robust foundation for predictive modeling.

## Hosted Application
This project is hosted on Streamlit, which allows users to interact with the predictive model in a web-based interface. You can access the Streamlit app [here](https://iplwinningpredictor.streamlit.app/).

## Installation and Usage
Follow these steps to set up and run the project locally:

### Step 1: Clone the Repository
Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/djv03/ipl_win_probability.git
cd ipl-win-probability-predictor
pip install -r requirements.txt
streamlit run app.py
