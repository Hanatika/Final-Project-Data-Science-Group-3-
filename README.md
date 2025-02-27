Documentation for Final Project – Data Science Group 3  
Project Title: Marketing Campaign Analysis  

1. Overview
This project aims to analyze marketing campaign data to understand customer behavior and improve campaign effectiveness. The dataset contains customer demographics, purchasing behavior, and campaign responses. Our goal is to identify key factors influencing customer engagement and provide data-driven recommendations for better targeting.  

2. Team Members
- M. Haidar – Lead and Data Analyst  
- Kirana – Data Collection & Cleaning
- Muhana Atikah – Project Documentation & Exploratory Data Analysis (EDA) 
- M. Kresna – Feature Engineering & Model Development  
- Gladina – Model Evaluation & Interpretation  
- Furqan Faiqdan – Report & Presentation  

3. Tools & Technologies Used  
- Programming Language: Python (Jupyter Notebook)  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- Version Control: GitHub  
- Documentation: Read.me/Google Docs  

4. Dataset Description  
The dataset contains the following features:  
ID - unique number of each cutomer
Year_Birth - year birth of customer
Education - customer’s level of education
Marital - customer’s marital status
Income - customer’s yearly household income
Kidhome - number of small children in customer’s household
Teenhome - number of teenagers in customer’s household
DtCustomer - date of customer’s enrolment with the company
Recency - number of days since the last purchase
MntWines - amount spent on wine products in the last 2 years
MntFruits - amount spent on fruits products in the last 2 years
MntMeatProducts - amount spent on meat products in the last 2 years
MntFishProducts - amount spent on fish products in the last 2 years
MntSweetProducts - amount spent on sweet products in the last 2 years
MntGoldProds - amount spent on gold products in the last 2 years
NumDealsPurchases - number of purchases made with discount
NumCatalogPurchases - number of purchases made using catalogue
NumStorePurchases - number of purchases made directly in stores
NumWebPurchases - number of purchases made through company’s web site
NumWebVisitsMonth - number of visits to company’s web site in the last month
AcceptedCmp1 - 1 if customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2 - 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
AcceptedCmp3 - 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
AcceptedCmp4 - 1 if customer accepted the offer in the 4th campaign, 0 otherwise
AcceptedCmp5 - 1 if customer accepted the offer in the 5th campaign, 0 otherwise
Complain - 1 if customer complained in the last 2 years
Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise

5. Data Processing Steps  
1. Data Collection – Import dataset into Jupyter Notebook.  
2. Data Cleaning – Handle missing values, duplicate records, and incorrect data types.  
3. Exploratory Data Analysis (EDA) – Visualize customer distribution, spending patterns, and campaign response rates.  
4. Feature Engineering – Create new variables for deeper insights, such as customer segmentation.  
5. Model Development – Train classification models to predict customer responses.  
6. Model Evaluation – Use metrics such as accuracy and recall. 
7. Insights & Recommendations – Provide business recommendations based on findings.  

6. Results & Key Findings  
- Customers with higher incomes and frequent purchases are more likely to respond.  
- Married customers with children tend to have lower engagement rates.  
- Personalized promotions and targeted email campaigns improve customer retention.  

7. Challenges & Improvements  
- Data Imbalance: The dataset had more non-responders than responders, requiring resampling techniques.  
- Feature Selection: Some variables were not significant in model performance and had to be removed.  
- Future Improvements: Test different machine learning models and optimize hyperparameters for better accuracy.  

8. Conclusion  
Our analysis provides actionable insights for marketing teams to enhance campaign strategies. By targeting high-potential customers, businesses can increase engagement and sales effectively.  

9. References  
- Dataset Source: [Kaggle / UCI Repository]  
- Python Libraries Documentation: [Pandas, Scikit-learn, Matplotlib]
