# Exploring Google Vertex AI's AutoML

This repository was created to explore and experiment with Google Vertex AI's AutoML capabilities.

After evaluating both Azure Machine Learning and Vertex AI, I chose to focus on Vertex AI, drawing inspiration from Mike Henderson's excellent [tutorial](https://www.youtube.com/playlist?list=PLgxF613RsGoUuEjJJxJW2JYyZ8g1qOUou).

The project consists of two notebooks documenting my experiences and observations while working with Vertex AI:

1. **AutoML-python-client.ipynb**  
   In this notebook, I used a different dataset from the one in the tutorial to gain hands-on experience with AutoML using the Python Client. The primary focus here is on understanding Vertex AI's tools and features rather than conducting an in-depth analysis of the dataset. Consequently, the model evaluation and optimization aspects were not emphasized.  
   *Dataset link*: **[Bank Customer Churn Dataset](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn?resource=download)**

2. **AutoML-kubeflow-pipeline.ipynb**  
   In this notebook, I used the same dataset as Mike's tutorial to interact with Kubeflow. I decided to switch datasets because the previous one I selected led to higher costs, likely due to its smaller size but greater number of categorical features, which may have increased the training volume.  
   I sourced the dataset from a public BigQuery table created by Mike, but you can also access it here: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

### Challenges Encountered:
1. Navigating between different Google Cloud services, such as BigQuery, Cloud Storage, and Vertex AI, while understanding what is stored where and its purpose.
2. Granting the necessary permissions.
3. Budget management for using cloud services.