# CustomerSegmentationByKMeans
This project provides a step-by-step guide on applying the K-Means clustering algorithm and the RFM (Recency, Frequency, Monetary) model to segment customers and identify their behaviors. The project includes code examples in Python, using popular libraries like Pandas, NumPy, Scikit-learn, and Plotly

Key Features:

1. Data preprocessing and cleaning
2. RFM model calculation
3. K-Means clustering implementation
4. Cluster analysis and interpretation
5. Visualization of results

## Data Set
To understand the overall customer trends for the entire year, we will use the transaction data from 2022 to segment customers.

## Portrait of customers

Before clustering customers, it's important to conduct exploratory data analysis to understand the customer profile. 

Most customers are from big cities, especially Ha Noi and Ho Chi Minh City. 

They have different preferences in ordering and channels based on their city: customers in the North prefer traditional ordering methods while those in the South prefer technology-based ordering. 

There are diverse demands such as everyday purchases, corporate buyers, event organizers, and bulk orders. 

Customer behaviors are strongly influenced by seasonal factors, and the sales amount is highly correlated with the number of customers.

## K-Means:
By using the RFM feature, we use the K-Means algorithm to perform customer segmentation

## Results from K-Means:
![image](https://github.com/user-attachments/assets/b22392db-f5c1-459a-ac6e-9c30035e8154)

## Segment Description: Name of each cluster and Interpret as BCG Matrix
Steady Average Spenders (Cow): Moderate frequency, steady but not high monetary value. Flexibility in technology-based and traditional ordering & channels.

Loyal High Spenders (Star): Very high frequency and monetary, low recency. Flexibility in technology-based and traditional ordering & channels.

High Potential NewComers (Question): Low frequency, medium recency, moderate spending. Traditional ordering preference.

At-Risk Churners (Dog): Low frequency, high recency, high spending in the past. Traditional ordering preference.
