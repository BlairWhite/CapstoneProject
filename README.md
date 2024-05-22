# CapstoneProject
UCB AI/ML Capstone Project

My project displays the 

Customer Churn Analysis:
  I analyzed the Ecommerce Customer Churn Analysis and Prediction dataset found here: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction
  Based on the grid search optimization results, the best model achieved an accuracy of approximately 93.34%. The optimal hyperparameters for this performance were:
  Batch size: 40, Epochs: 50, Neurons in the first dense layer: 128, Optimizer: Adam, Dropout rate: 0.1, Learning rate: 0.01. These parameters were identified by evaluating various combinations using cross-validation, resulting in a highly accurate model for predicting customer churn.
  
Recency-Frequency-Money:
  I analyzed the RFM - Ecommerce dataset found here: https://www.kaggle.com/datasets/harshsingh2209/rfm-analysis
  RFM analysis involves assessing customer behavior based on three key metrics: Recency, Frequency, and Monetary Value. Recency measures how recently a customer made a purchase, Frequency tracks the number of transactions, and Monetary Value reflects the total amount spent. Clustering segmentation enables targeted marketing efforts tailored to each customer segment's preferences and needs. My analysis also provides insights into customer behavior, helps identify high-value customers, and guides retention strategies to minimize churn. Through RFM analysis and clustering, businesses can optimize their marketing strategies, enhance customer satisfaction, and drive revenue growth.

Recommender System:
  I analyzed the Amazon Book Review dataset found here: https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews
  Incorporating user book review scores and sentiment, I built a model to take in a user ID, and return a recommended list of books that they might find interesting. Recommender systems analyze user behavior, such as purchase history, browsing patterns, and demographic information, to suggest products that are likely to be of interest to each customer. By offering relevant and targeted recommendations, recommender systems enhance the shopping experience, increase customer engagement, and drive sales.
  

AB Testing:
  I analyzed the E-commerce A/B testing dataset found here: https://www.kaggle.com/datasets/ahmedmohameddawoud/ecommerce-ab-testing
  Based on the analysis, the conversion rates for the treatment and control groups are 11.89% and 12.04%, respectively. The 95% confidence intervals for these rates are [11.73%, 12.06%] for the treatment group and [11.87%, 12.21%] for the control group. The chi-squared test results show a chi-squared statistic of 1.52 with a p-  value of 0.218. Since the p-value is greater than the significance level of 0.05, we fail to reject the null hypothesis. This indicates that there is no significant  difference in conversion rates between the treatment and control groups.
