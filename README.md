# Spanish Wine Dataset Insight
## Helping a Small Wine Distributor Bring Spanish Wines to a New Market

A small wine distributor is looking to expand their business by bringing Spanish wines to a new market. They face challenges in understanding the market trends and consumer preferences. Machine learning, specifically regression models, can help address these challenges by analyzing historical data to predict wine ratings, which is our target vector. These predictions can offer valuable insights to make informed decisions when selecting wines to introduce to the new market.

## Data Dictionary and Description
The dataset is a collection of information about various Spanish wines

Source: https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset

Data Dictionary

![datadictionary](https://user-images.githubusercontent.com/110209769/231904639-38a2f519-a09b-4b3f-8446-69766a39d3a7.png)



## Expoloratory Analysis
![explorary_analysis_1](https://user-images.githubusercontent.com/110209769/231904659-e8e288cf-fd86-421a-89a3-712b9849b130.png)

Insight: The limited number of wine reviews before 2003 could indicate different factors, such as a growing interest in the Spanish wine industry after 2003. This intriguing trend is worth further investigation, as understanding the reasons behind this surge could help our stakeholders make informed decisions when selecting wines to introduce to the new market and capitalize on emerging trends.

![exploratory_analysis_2](https://user-images.githubusercontent.com/110209769/231904684-4b20b71e-497e-4027-b883-a65782393d6f.png)

Insight: The wine ratings in this dataset exhibit a significant imbalance, with the vast majority of wines scoring 4.5 and below. This skewed distribution emphasizes the overrepresentation of lower-rated wines, highlighting the need for caution when drawing conclusions or making predictions based on this dataset.

Best Metrics
Model Name: XGBoost Regressor	
RMSE: 0.088178	
MAE: 0.071941	
R^2: 0.5709

Although the XGBoost Regressor's R2 score is relatively low, indicating a limited ability to capture the underlying non-linear relationships in the data, it still provides some insights that can be useful for the business. To improve model performance, it is recommended to gather more data to help the machine learning algorithm better understand the complex relationships within the dataset.

In the meantime, leveraging the current insights can help the distributor begin with a small, focused portfolio of Spanish wines that are more likely to succeed in the new market. As more data is collected over time, the model's performance can be improved, and the distributor can confidently expand their portfolio by introducing a broader range of Spanish wines. This data-driven approach will ensure a better understanding of market preferences and trends, ultimately leading to higher sales and customer satisfaction.

