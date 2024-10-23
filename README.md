# Customer Segmentation Using K-Means Based on RFM Model
![image](https://github.com/user-attachments/assets/ccdd5c0f-2585-4d19-9875-f7c5f072ac9d)

This project provides a step-by-step guide on applying the K-Means clustering algorithm and the RFM (Recency, Frequency, Monetary) model to segment customers and identify their behaviors. The project includes code examples in Python, using popular libraries like Pandas, NumPy, Scikit-learn, and Plotly

![image](https://github.com/user-attachments/assets/5b4208f1-6ac6-470c-84e4-93cd4798fbed)


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

## Cluster Distribution
![image](https://github.com/user-attachments/assets/da7c0212-330d-48ce-8c64-f026903e502e)

## Segment Description: Name of each cluster and Interpret as BCG Matrix
1. Steady Average Spenders (Cow)
2. Loyal High Spenders (Star)
3. High Potential NewComers (Question)
4. At-Risk Churners (Dog): 

![image](https://github.com/user-attachments/assets/dc8ff0e1-8945-4d5e-81ca-a4d05e0409ba)

## Outliers Analysis
Although 5% of outlier customers have a much higher value than the typical customer, it's important not to overlook them and miss out on understanding high-value customer behavior.

## Marketing Target
![image](https://github.com/user-attachments/assets/f22d297f-67aa-43f5-a8d8-ac525f3c930d)

