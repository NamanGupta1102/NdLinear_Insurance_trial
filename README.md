# NdLinear_Insurance_trial

https://colab.research.google.com/drive/1iwn8Wk0jDaJuyOsUfSjsMsJnIAVEmi7a?usp=sharing
All the code is also availble on colab.

Dataset: Utilized the Medical Cost Personal Dataset from Kaggle, which includes features like age, sex, BMI, number of children, smoking status, and region: https://www.kaggle.com/datasets/mirichoi0218/insurance?select=insurance.csv

Objective: Predict the charges variable, representing individual medical insurance costs.​

Approach:

Preprocessed the data by scaling numerical features and one-hot encoding categorical variables.

Split the dataset into training and testing sets.

Built a regression model using NdLinear layers to capture complex interactions in the data.

Trained the model using Mean Squared Error loss and the Adam optimizer.

Evaluated the model's performance by comparing predicted charges against actual values.​

Results
A scatter plot comparing actual versus predicted charges was generated to visualize the model's performance.​
