# **💸 Predicting the premium for insurance using Machine Learning**

In this notebook, we are going through a machine learning project with the goal of predicting the premium to be paid for insurance.

# **1. Problem Defination**
> The objectives of this project is to predict insurance premiums based on various factors.

# **2. Data**

> The data is downloaded from the kaggle playground prediction competition:
https://www.kaggle.com/competitions/playground-series-s4e12

> For this competition, you are predicting the premium of insurance for customers.

# **3. Evaluation**
> The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted premiums.

For more on the evaluation for the project check the below link.

https://www.kaggle.com/competitions/playground-series-s4e12/overview/evaluation

**Note:** The goal for most regression evaluation metrics is to minimize the error.

# **4. Features**

1. **id**
2. **Age**: The age of the individual.
3. **Gender**: The gender of the individual (`Male` or `Female`).
4. **Annual Income**: Income of the individual.
5. **Marital Status**: Whether the person is `Single`,`Married` or `Divorced`.
6. **Number of Dependents**: Number of dependent members on an indivisual.
7. **Education Level**: Qualification level of an indivisual.
8. **Occupation**: Whether the person is `Employed`, `Unemployed` or `self-employed`.
9. **Health Score**
10. **Location**: Whether the indivisual stays in `Urban`, `Suburban` or `Rural` area.
11. **Policy Type**: Whether theperson opted for `Premium`, `Comprehensive` or `Basic`.
12. **Previous Claims**: Number of claims made previously.
13. **Vehicle Age**: Age of the vehicle.
14. **Credit Score**: Credit score of an indivisual in range (300 - 900).
15. **Insurance Duration**: Number of years for the policy to mature.
16. **Policy Start Date**
17. **Customer Feedback**: Feedback of customer can be `Good`, `Average` or `Poor`.
18. **Smoking Status**: Whether the person smokes or not.
19. **Exercise Frequency**: How frequently an indivisual exercises.
20. **Property Type**: Type of property.
21. **Premium Amount**: Outcome variable.

# **5. Exploratory Data Analysis**

**5.1 Age group distribution**

![image](https://github.com/user-attachments/assets/206b8e12-6681-4cea-84d3-785710d74141)

**5.2 Marital Status distribution**

![image](https://github.com/user-attachments/assets/e75eec9a-4fec-4816-be14-571e9fea32a0)

**5.3 Premium amount VS Number of indivisuals**

![image](https://github.com/user-attachments/assets/7de805cc-5e84-4099-8963-2485b7060d96)

**5.4 Gender based smoking status of different indivisuals**

![image](https://github.com/user-attachments/assets/4c4e1b56-c438-4653-9a0a-46f9cfa27465)

**5.5 Gender based marital status distribution**

![image](https://github.com/user-attachments/assets/f97102a4-cb59-49a9-a5e9-122ed81a9ff1)

**5.6 Gender Based Education Levels distribution**

![image](https://github.com/user-attachments/assets/b5eaa752-895c-4ccb-9767-32a7eb087deb)

**5.7 Premium amount distribution (Yearly)**

![image](https://github.com/user-attachments/assets/d14c0d1a-08be-4b36-aac1-9cf475898fa1)

**5.8 Gender based Exercise status distribution**

![image](https://github.com/user-attachments/assets/229442a5-1160-433f-a6ab-b548ea46932f)

**5.9 Age VS Premium amount**

![image](https://github.com/user-attachments/assets/e9f2797b-144a-460f-8e8d-5c685f1e8695)

**5.10 Credit Score VS Premium amount**

![image](https://github.com/user-attachments/assets/05299a06-497f-4078-b2ae-7fb1cb10b99d)

**6. Modelling**

- 6.1 Baseline models:-
  - RandomForestRegressor()
  - LinearRegression()
- 6.2 RandomizedSearchCV for Hyperparameter Tuning
- 6.3 Training the Best ideal model(RandomForestRegressor)

**7. Feature Importance**

![image](https://github.com/user-attachments/assets/60de78c3-1eb8-494b-bff8-723486992046)
