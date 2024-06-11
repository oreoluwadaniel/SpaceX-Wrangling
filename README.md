# SpaceX Falcon 9 First Stage Landing Prediction
  This project focuses on predicting the landing outcome of the SpaceX Falcon 9 first stage using Exploratory Data Analysis (EDA) and supervised machine learning models.

## Objectives
* Perform Exploratory Data Analysis (EDA) to uncover patterns in the data.
* Determine training labels for supervised models.

## Data Description
The dataset includes various attributes of Falcon 9 launches, such as flight number, date, booster version, payload mass, orbit, launch site, and outcome. Here are the key variables:

* FlightNumber: Number of the flight
* Date: Launch date
* BoosterVersion: Version of the booster
* PayloadMass: Mass of the payload in kg
* Orbit: Target orbit
* LaunchSite: Site of the launch
* Outcome: Outcome of the landing (successful or not)
* Flights: Number of flights
* GridFins: Presence of grid fins
* Reused: Whether the booster was reused
* Legs: Presence of landing legs
* LandingPad: Landing pad used
* Block: Block number of the booster
* ReusedCount: Number of times the booster was reused
* Serial: Serial number of the booster
* Longitude: Longitude of the launch site
* Latitude: Latitude of the launch site


## Landing Outcomes
The landing outcomes are categorized as follows:
* True Ocean: Successfully landed in the ocean
* False Ocean: Unsuccessfully landed in the ocean
* True RTLS: Successfully landed on a ground pad
* False RTLS: Unsuccessfully landed on a ground pad
* True ASDS: Successfully landed on a drone ship
* False ASDS: Unsuccessfully landed on a drone ship
* None None: No landing attempt


Conclusion
This project successfully conducted EDA to understand the data and determined the training labels for supervised learning models. The next steps involve building and evaluating machine learning models to predict the landing outcomes of Falcon 9 first stages.

Future Work
Train machine learning models using the prepared dataset.
Evaluate model performance and optimize for better accuracy.
Implement the models to predict future landing outcomes.

## Contact

For any questions or suggestions, please reach out through [oluwafikayore@gmail.com].
