# zomato-dataset-preprocessing
This project demonstrates data preprocessing and using different ML algorithms it predicts the rating of restaurants based on various features in the Zomato dataset.

Dataset
The dataset used contains the following columns:

restaurant name: Name of the restaurant.
restaurant type: Type of restaurant (e.g., Casual Dining, Quick Bites).
rate (out of 5): Rating of the restaurant.
num of ratings: Number of ratings received.
avg cost (two people): Average cost for two people.
online_order: Availability of online ordering.
table booking: Availability of table booking.
cuisines type: Type of cuisines offered.
area: Area where the restaurant is located.
local address: Local address of the restaurant.
Steps
Data Preprocessing:

Handle missing values in both numerical and categorical features.
Binarize the target variable (rate (out of 5)) for simplicity (ratings >= 3.5 are classified as 1, otherwise 0).
Use ColumnTransformer to apply different preprocessing steps to numerical and categorical columns.

To run the code, ensure you have the required libraries installed (pandas, numpy, matplotlib, scikit-learn).
