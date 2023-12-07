# Predicting Hotel Booking Cancellations 😌

# Motivation 🫶🏼 
Maximising hotel revenue while preventing the pitfalls of overbooking is a complex yet critical challenge in the hospitality industry. The aim of the project is to develop an advanced classification model that accurately predicts hotel reservation cancellations. The model will enable the establishment to strategically manage reservations, effectively allocate resources, and enhance overall revenue generation :-)

# Exploratory Data Analysis (EDA) ✍🏻
1. Data Cleaning
- Null values:
  a. Fill null values with its median in the "Children" column
  b. Remove rows with Nan values in the "Country" column
  c. Create a new binary (0 or 1) column **'agent_encoded'** & **'company_encoded'** indicating whether the reservation was done through **an agent or not (1 for without agent, 0 for with agent)** & **a company (1 for without company, 0 for through company)**

2. Identifying Relationships
- 


# Models ranked based on Precision Score 🕵🏻‍♀️
1. Decision Tree: 0.99
2. Feedforward Neural Network (FNN): 0.88
3. Extreme Gradient Boosting (XGBoost): 0.81
4. Logistic Regression: 0.81
5. Random Forest: 0.77


# Findings & Justifications 🔎
- Based on my findings, Feedforward Neural Network seems to be the most appropriate model to use to predict hotel booking cancellations!
- Even though Decision Tree produced the highest precicion score, it is worth noting that the model is extremely prone to overfitting. And that probably resulted in the almost perfect precision score as well.

# Finding unseen data (if possible?)


# Dataset(s) / Resource(s)
1. Hotel Booking Demand Dataset: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/
