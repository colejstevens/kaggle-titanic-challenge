# Titanic: Machine Learning from Disaster

This repository contains my solution to the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition hosted on Kaggle. The task is to build a binary classifier that predicts whether a given passenger survived the Titanic shipwreck based on personal and socioeconomic features.

## Project Overview

This project includes:

- Exploratory Analysis
- Data preprocessing
- Model development and optimization
- Generation of submission file

## Approach

For my first attempt I decided to go with a relatively straightforward process:

- Dropped irrelevant columns (`Name`, `Ticket`, `Cabin`).
- Handled missing values by removing incomplete rows.
- Applied one-hot encoding to categorical variables.
- Normalized/standardized numerical features.
- Trained and tuned a Decision Tree classifier using GridSearchCV.

## Data

- The dataset is available from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data).
- Place `train.csv` and `test.csv` in the `data/` directory if you plan on running `titanic_model.ipynb` locally.

## Results

After uploading the [`submission.csv`](data/submission.csv) the model received a score of <u>0.76076</u>. There is definitely room for improvement but this is a good start.

## License

MIT License — see `LICENSE` for details.