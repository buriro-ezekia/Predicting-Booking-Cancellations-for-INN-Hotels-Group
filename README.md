# Predicting-Booking-Cancellations-for-INN-Hotels-Group
The goal of this project was to develop a predictive model that forecasts the likelihood of booking cancellations. This model would enable INN Hotels Group to take proactive measures to reduce revenue loss due to inventory vacancies.
# Project Overview
# 1. Data Preparation
The dataset used for this project includes various features related to hotel bookings. The following steps were taken to prepare the data:

- Loading Data:The dataset was loaded from a CSV file.
- Feature Engineering: New features were created, such as total_nights (combining no_of_weekend_nights and no_of_week_nights) and lead_time_x_market_segment_Online (interaction term).
- Date Processing: The arrival_date feature was converted to a numerical format using ordinal encoding.
- Standardisation: Features were standardised to ensure they contributed equally to the model.
# 3. Model Evaluation
The models were evaluated using cross-validation and various metrics, including accuracy, precision, recall, and F1-score. The Random Forest Classifier showed the best performance.

# 4. Hyperparameter Tuning
Hyperparameter tuning was performed on the Random Forest and Gradient Boosting models to enhance their performance further. Grid Search was used to find the optimal parameters.

# 5. Prediction and Proactive Measures
The trained model was used to predict the likelihood of cancellations for new bookings. High-risk bookings were identified, and proactive measures were suggested to reduce cancellations, such as sending reminders, offering incentives, or adjusting booking policies.

# Results
The Random Forest Classifier demonstrated the best performance with a test accuracy of 81.02%. The model identified high-risk bookings, allowing INN Hotels Group to implement targeted strategies to reduce cancellations and mitigate revenue loss.

# Feature Importance
The most important features identified by the model were arrival_date and lead_time. These features provide valuable insights into customer behaviour, demand patterns, and operational planning. Their high importance scores indicate that they play a significant role in predicting booking cancellations, helping to drive more informed and effective decision-making.

# Contributing
Contributions are welcome!

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Contact
For any questions or suggestions, please contact Buriro Ezekia at ezekia.buriro@aims.ac.rw.

