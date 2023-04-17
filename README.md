# Spanish Wine Dataset Insight
## Helping a Small Wine Distributor Bring Spanish Wines to a New Market

**Business Problem**
A small wine distributor is looking to expand their business by bringing Spanish wines to a new market. They face challenges in understanding the market trends and consumer preferences. Machine learning, specifically regression models, can help address these challenges by analyzing historical data to predict wine ratings, which is our target vector. These predictions can offer valuable insights to make informed decisions when selecting wines to introduce to the new market.

## Data Dictionary and Description
The dataset is a collection of information about various Spanish wines

Source: https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset

Data Dictionary

![datadictionary](https://user-images.githubusercontent.com/110209769/231904639-38a2f519-a09b-4b3f-8446-69766a39d3a7.png)

## Expoloratory Analysis
![explorary_analysis_1](https://user-images.githubusercontent.com/110209769/231904659-e8e288cf-fd86-421a-89a3-712b9849b130.png)

Insight: The limited number of wine reviews before 2003 could indicate different factors, such as a growing interest in the Spanish wine industry after 2003. This intriguing trend is worth further investigation, as understanding the reasons behind this surge could help our stakeholders make informed decisions when selecting wines to introduce to the new market and capitalize on emerging trends.

![exploratory_analysis_2](https://user-images.githubusercontent.com/110209769/232350222-23a0b432-0df1-4778-a9e3-63497ef96c2a.png)

Insight: The data reveals that there is generally an inverse relationship between the mean body and mean acidity scores across wine ratings. For example, at a rating of 4.2, the mean body score is low while the mean acidity score is high, whereas at a rating of 4.9, the mean body score is high and the mean acidity score is low.

# **Model Selection, Justification, and Conclusion**

![model_selection](https://user-images.githubusercontent.com/110209769/232350625-d278c8ae-6b6a-4281-842b-0cca81e20644.png)

When deciding which model to choose, the goal is to select the one that best predicts the wine ratings (low, medium, or high) for Spanish wines entering a new market. By accurately predicting the wine ratings, your business can make more informed decisions about which wines to invest in and promote, potentially (and hopefully) leading to increased sales and customer satisfaction.

The Tuned GradientBoost model outperforms the original Gradient Boosting Classifier in all metrics, making it the better choice. The improvements in Precision, Recall, F1 Score, and Accuracy indicate that the Tuned GradientBoost model will provide more reliable predictions.

Benefits of using the Tuned GradientBoost Classifier:

*Higher Precision:* With an increase in Precision from 0.645 to 0.667, the Tuned GradientBoost model is more accurate in predicting wines that will receive positive ratings. This helps your business focus on the wines that are most likely to succeed in the new market, reducing the risk of investing in poorly received wines.

*Improved Recall:* The increase in Recall from 0.566 to 0.637 means that the Tuned GradientBoost model is better at identifying wines with true positive ratings. This allows your business to capture a larger share of the high-quality wines, which can result in increased demand and customer satisfaction.

*Better F1 Score:* The F1 Score, a measure that balances Precision and Recall, increased from 0.595 to 0.643. This indicates that the Tuned GradientBoost model provides a better overall performance in predicting wine ratings, ensuring that your business can make more accurate and informed decisions.

*Increased Accuracy:* The Accuracy of the Tuned GradientBoost model increased from 0.778 to 0.788, meaning that a higher percentage of its predictions are correct. This can lead to more effective marketing strategies and inventory management for your wine distribution business.

**Business Solution:** In conclusion, selecting the Tuned GradientBoost model will enable the business to make more accurate predictions. This can help your business optimize marketing efforts, inventory management, and investments in the most promising wines, ultimately leading to higher sales, better customer satisfaction, and increased profitability.

For any additional questions, please contact: 
- [Contact Me](mailto:rynedaniels@gmail.com)
