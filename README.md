# Dynamic Demand Forecasting for CitiBike: Improving Urban Bike-Sharing Efficiency

Welcome to the repository for the **Dynamic Demand Forecasting for CitiBike** project! 🚴‍♂️🚴‍♀️ This project is aimed at optimizing the CitiBike system in New York City by predicting bike availability dynamically, thereby improving overall service reliability and user experience.

## 🚀 Project Overview

The CitiBike system, the largest bike-share program in the United States, faces challenges with bike availability across its numerous stations. Users often encounter issues with empty docks or overloaded stations, impacting their experience. This project develops a predictive model to forecast bike demand and optimize bike redistributions, ensuring a smoother and more reliable service for all users.

### Key Objectives:
- **Predict Bike Demand:** Forecast bike availability and demand at different stations using machine learning techniques.
- **Optimize Redistribution:** Enhance bike allocation strategies to prevent imbalances and improve station management.
- **Improve User Experience:** Minimize the inconvenience caused by overloaded or empty stations, facilitating smoother transitions for users.

## 📊 Dataset and Features

The dataset used in this project is sourced from the CitiBike system and includes:
- **Ride Identifier (ride_id):** Unique ID for each trip.
- **Type of Bike (rideable_type):** Indicates whether the bike is classic or electric.
- **Timestamps (started_at, ended_at):** Times when rides start and end.
- **Station Information (start_station_name, end_station_name, start_station_id, end_station_id):** Identifies the stations involved.
- **Geographical Coordinates (start_lat, start_lng, end_lat, end_lng):** Latitude and longitude for mapping rides.
- **Member or Casual (member_casual):** Distinguishes between regular members and casual users.

## 🔍 Exploratory Data Analysis (EDA)

We conducted extensive EDA to uncover patterns and trends in bike usage:
- **Peak Usage Hours:** Identified times with highest bike demand.
- **Weather Impact:** Analyzed how weather conditions affect bike rentals.
- **Local Events:** Examined the influence of local events on station usage.

![Distribution of Rides by Hour](https://github.com/user-attachments/assets/59cd5abf-1556-4acc-8608-f9c054c53e8d)

*Figure 1: Distribution of Rides by Hour of the Day*

## 🤖 Machine Learning Model

### Model Selection

We employed the **Random Forest Regressor** due to its robustness and accuracy in handling complex regression tasks. The model predicts both incoming and outgoing bike traffic at each station.

### Evaluation Metrics

- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared (R²)**
- **Accuracy**

#### Results:
- **Initial Model:**

![Performance Metrics1](https://github.com/user-attachments/assets/c6e9e48a-57d7-411b-89c3-4dbedbecb780)
- **Hyperparameter Tuned Model:**

![Performance Metrics2](https://github.com/user-attachments/assets/806071fc-5020-4bf4-b0f7-ab55dd9ea27e)

*Figure 2: Comparison of Model Performance Metrics*

## 📈 Results and Insights

The tuned Random Forest model demonstrates improved accuracy in predicting bike demand, allowing for more effective bike redistribution. This advancement promises a more balanced and user-friendly bike-sharing experience.

<!-- ## 📹 Video Explanation

For a detailed walkthrough of the project, check out the [Video Explanation](https://github.com/dhruvmojila/Dynamic-Demand-Forecasting-for-CitiBike-Improving-Urban-Bike-Sharing-Efficiency/raw/main/Video%20Explanation/Dynamic%20Demand%20Forecasting%20for%20CitiBike%20Improving%20Urban%20Bike-Sharing%20Efficiency.mp4) embedded below:

[![Watch the video](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://github.com/dhruvmojila/Dynamic-Demand-Forecasting-for-CitiBike-Improving-Urban-Bike-Sharing-Efficiency/raw/main/Video%20Explanation/Dynamic%20Demand%20Forecasting%20for%20CitiBike%20Improving%20Urban%20Bike-Sharing%20Efficiency.mp4) -->

## 📚 References

- [Citi Bike System Data](https://citibikenyc.com/system-data)
- [Azeem Halim's Project on Medium](https://businesscode.medium.com/python-practice-analyzing-new-york-city-bike-sharing-data-using-pandas-3badfd6ab026)
- [NYC Data Science Blog](https://nycdatascience.com/blog/student-works/capstone/solving-the-citibike-station-rebalancing-issue-with-python-machine-learning/)

## 💬 Contact

For any questions or further discussion, feel free to reach out to:

- Dhruv Mojila: [dmojila@stevens.edu](mailto:dmojila@stevens.edu)
- Sreram Vasudev: [svasudev@stevens.edu](mailto:svasudev@stevens.edu)
- Vrushali Khatane: [vkhatane@stevens.edu](mailto:vkhatane@stevens.edu)
- Vidhi Patel: [vpatel40@stevens.edu](mailto:vpatel40@stevens.edu)

Thank you for visiting our project repository! We hope you find the insights and tools useful for enhancing bike-sharing systems and urban mobility. 🚲
