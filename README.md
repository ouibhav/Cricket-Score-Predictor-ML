# A XgBoost based Cricket Score Predictor

Dataset: Uploaded in this repository : t20i_info.csv.

## Overview
This project is a Cricket Score Predictor that leverages machine learning techniques to forecast the final score a batting team is likely to achieve in a cricket match. It is trained on historical cricket match data, and the prediction model is built using the XGBoost algorithm.

### Inputs required:

- Any two International Cricket Teams.
- Stadium in which the match is being played.
- Current Score.
- Overs delivered (Works for Overs > 5).
- Wickets Out.
- Runs scored in last 5 overs.

## Features
- **Feature Engineering:** The code employs extensive feature engineering, including cumulative scores, over details, wicket-related features, and a rolling sum of runs in the last five overs.
- **Data Cleaning:** Missing city values are handled by extracting information from the venue column, and the dataset is filtered to include only matches in cities with substantial occurrences.
- **Model Construction:** A machine learning pipeline is utilized, incorporating one-hot encoding, standard scaling, and an XGBoost Regressor for accurate score predictions.
- **Model Persistence:** The trained model is saved using Pickle for future use, allowing for quick deployment without the need for retraining on historical data.


## Snaps of the project
![Screenshot (4652)](https://github.com/user-attachments/assets/dba98d27-6d34-45a2-a7e5-12703a1ec497)

![Screenshot (4653)](https://github.com/user-attachments/assets/2d4ced04-9281-436b-b6f7-e935d14f736f)

