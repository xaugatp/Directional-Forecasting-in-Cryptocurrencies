# Directional-Forecasting-in-Cryptocurrencies
Objective

The primary objective of this project is to predict short-term price movements of a cryptocurrency, specifically identifying whether the price will increase or not (indicated as 'up' or 'not up') for the next timestamp. This information can significantly aid traders in making informed decisions.

Data Source

The model utilizes historical OHLCV (Open, High, Low, Close, Volume) data recorded at a one-minute frequency. This granular data allows for a more detailed analysis of market trends and price fluctuations.
https://www.kaggle.com/competitions/directional-forecasting-in-cryptocurrencies 

Methodology

Data Preprocessing:

The initial step involves cleaning the dataset by handling missing values and scaling the data using Min-Max Scaling to normalize features.
Features are engineered from historical price data to capture trends, volatility, and momentum indicators.
Exploratory Data Analysis (EDA):

Conducting EDA to visualize trends and patterns in the data, understanding correlations, and identifying potential outliers.
Model Selection:

Several classification algorithms are tested, including logistic regression, decision trees, and other tree-based models, to identify the most effective approach for predicting price movements.
The performance of these models is evaluated using the Macro-Averaged F1 Score, ensuring a balanced measure of accuracy across classes.
Model Training and Evaluation:

The dataset is split into training and test sets, with models trained on the training data and evaluated based on their predictive accuracy and F1 scores.
Hyperparameter tuning is performed to optimize model performance further.
Results

The preliminary results have shown promise, with a Decision Tree model achieving an accuracy of 67.86% and a Macro-Averaged F1 Score of 67.66% on the training data. This indicates a relatively good performance in predicting price movements based on the features derived from historical data.

Challenges

One of the key challenges faced during the project was managing data loss during the preprocessing step, particularly when dropping rows with NaN values from rolling calculations. Strategies to mitigate this issue are being explored to retain as much relevant data as possible. I was facing the problem of overfitting.
The biggest issue is to handle the large dataset with low computiational power. 

Conclusion

The project is an ongoing effort to refine predictive modeling techniques in the cryptocurrency market. As the model continues to evolve, we anticipate improved accuracy and reliability in directional price forecasting, ultimately aiding traders in making more informed decisions.

Future Work

1) Improve feature engineering
2) Solving the problem using Time series based algorithms,  Using RNN and LSTM
3) Improving the quality of code  

