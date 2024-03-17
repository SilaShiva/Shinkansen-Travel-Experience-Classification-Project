# Shinkansen-Travel-Experience-Classification-Project

This project aims to classify the overall experience of Shinkansen (bullet train) travelers based on various factors using the XGBoost classifier model. The dataset used contains the following columns:

ID: Unique identifier for each record.

Gender: Gender of the traveler (e.g., Male, Female).

Customer_Type: Type of customer (e.g., Business Traveler, Leisure Traveler).

Age: Age of the traveler.

Type_Travel: Purpose of travel (e.g., Business, Personal).

Travel_Class: Class of travel (e.g., First Class, Economy).

Travel_Distance: Distance of travel.

Departure_Delay_in_Mins: Delay in departure time.

Arrival_Delay_in_Mins: Delay in arrival time.

Platform_Location: Location of the platform.

Seat_Class: Class of seating

Overall_Experience: Target variable indicating the overall experience

Seat_Comfort: Rating of seat comfort

Arrival_Time_Convenient: Rating of arrival time convenience.

Catering: Rating of catering services.

Onboard_Wifi_Service: Rating of onboard WiFi service.

Onboard_Entertainment: Rating of onboard entertainment.

Online_Support: Rating of online customer support.

Ease_of_Online_Booking: Rating of ease of online booking.

Onboard_Service: Rating of onboard service.

Legroom: Rating of legroom comfort.

Baggage_Handling: Rating of baggage handling.

CheckIn_Service: Rating of check-in service.

Cleanliness: Rating of cleanliness onboard.

Online_Boarding: Rating of online boarding process.

**Project Overview**

In this project, we performed a classification task to predict the overall experience of Shinkansen travelers. The XGBoost classifier was chosen as the model due to its effectiveness in handling complex datasets and achieving high accuracy.

**Model Accuracy**

The XGBoost classifier model achieved an accuracy of 94.7% in predicting the overall experience of travelers. This high accuracy indicates the model's capability to distinguish between positive and negative experiences based on the provided features.

**Dataset Source**

The dataset contains a comprehensive set of features related to the Shinkansen travel experience, allowing for a detailed analysis and prediction of customer satisfaction.

**Project Structure**

The project is structured as follows:

Data Preprocessing: Includes data cleaning, handling missing values, encoding categorical variables, and feature scaling if applicable.
Exploratory Data Analysis (EDA): Analyzes the relationships between different features and the target variable to gain insights into the dataset.
Feature Selection: Identifies the most relevant features for model training and prediction.
Model Training: Utilizes the XGBoost classifier to train the model on the preprocessed data.
Hyperparameter Tuning: Fine-tunes the model hyperparameters using techniques such as GridSearchCV or RandomizedSearchCV.
Model Evaluation: Evaluates the model's performance using metrics such as accuracy, precision, recall, and F1 score.
Results Interpretation: Interprets the model results and provides actionable insights for improving the overall travel experience.

**Conclusion**

The classification project on the Shinkansen travel experience demonstrates the effectiveness of machine learning in predicting customer satisfaction based on various factors. The XGBoost classifier, with its high accuracy of 94.7%, proves to be a valuable tool for analyzing and improving the quality of travel services.

For more details and code implementation, please refer to the project files in this repository.
