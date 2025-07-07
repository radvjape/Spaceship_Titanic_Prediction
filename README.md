# Speceship Titanic Prediction

## Introduction
Project Summary: The Spaceship Titanic was an interstellar passenger liner carrying nearly 13 000 people to newly discovered exoplanets. During its maiden voyage in 2912, it collided with a spacetime anomaly near Alpha Centauri. While the ship remained intact, nearly half of the passengers mysteriously vanished into another dimension.

Goal: Analyze the passenger data and apply machine learning techniques to predict which individuals were transported by the anomaly. Help uncover the mystery and assist in the rescue mission.

Source of Data: [Spaceship Titanic Data](https://www.kaggle.com/competitions/spaceship-titanic/data)

Project Objectives:
* Perform Exploratory Data Analysis (EDA),
* Conduct Statistical Inference,
* Develop Predictive Models,
* Optimize Model Performance,
* Communicate Findings Clearly,
* Propose Improvements.

## Dataset
* PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
* HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.
* CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
* Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
* Destination - The planet the passenger will be debarking to.
* Age - The age of the passenger.
* VIP - Whether the passenger has paid for special VIP service during the voyage.
* RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
* Name - The first and last names of the passenger.
* Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.

## Project Structor
* Data Cleaning
* Preforming Exploratory Data Analysis
* Perform statistical inference
* Apply various machine learning models
* Final Model

## Conclusion
## Conclusion

### Statistical Analysis
* CryoSleep do have impact on if passenger is trasnported or not.

### Machine Learning Models Preformance
* On raw data best preformining model - Gradient Boosting with accuracy 78.43%,
* On feature engineered data best preforming model - LightGBM with accuracy 80.62%,
* After tuning best model was still LightGBM and even better than model ensebled model with accuracy 81.48 %.

### Kaggle Score for Test Data
[Kaggle Score](https://github.com/user-attachments/assets/6d893217-6c29-48a2-b884-7b7bf7c27e00)

## Suggestions for Improvement
* Do more data preperation and feature enigineering to help improve models predictions.
