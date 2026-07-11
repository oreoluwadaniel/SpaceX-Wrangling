# SpaceX Falcon 9: Data Wrangling for Landing Prediction

Data wrangling and label preparation for a Falcon 9 first-stage landing-outcome prediction model.

## Overview

This project prepares SpaceX Falcon 9 launch data for supervised machine learning by cleaning the data and deriving training labels from landing outcomes.

## Objectives

- Perform exploratory data analysis to uncover patterns in the data
- Derive training labels for supervised models from landing outcome data

## Dataset

Key fields include flight number, date, booster version, payload mass, orbit, launch site, landing outcome, and booster reuse history.

## Landing outcome categories

True/False Ocean, True/False RTLS (ground pad), True/False ASDS (drone ship), and no landing attempt.

## Tech stack

Python, pandas

## Status

EDA and labeling are complete. Next step is training and evaluating a classification model on the prepared dataset.

## Related project

See [Falcon-9-Landing-Prediction-EDA](https://github.com/oreoluwadaniel/Falcon-9-Landing-Prediction-EDA) for the exploratory analysis and visualization of the same launch data.

## Contact

oluwafikayore@gmail.com
