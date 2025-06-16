
## 📊 Project Overview
This project implements an advanced customer segmentation analysis using RFM (Recency, Frequency, Monetary) methodology and machine learning techniques to identify distinct customer groups in an e-commerce dataset.

## 🌟 Defining the project using STAR Approach

### Situation
- Dataset: E-commerce transaction data containing 541,909 records
- Key Challenge: Understanding customer behavior patterns and creating meaningful segments
- Data Scope: 8 key features including InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country

### Task
- Perform comprehensive customer segmentation
- Implement RFM analysis
- Create actionable customer segments
- Develop predictive models for customer classification
- Generate insights for targeted marketing strategies

### Action
1. **Data Preprocessing**
   - Removed negative quantities and cancelled transactions
   - Handled missing values
   - Created TotalPrice feature
   - Processed 530,693 valid records after cleaning

2. **RFM Analysis Implementation**
   - Recency: Days since last purchase
   - Frequency: Number of unique invoices
   - Monetary: Total amount spent
   - Created RFM scores (1-5 scale)

3. **Customer Segmentation**
   - Implemented 7 distinct segments:
     - Best Customers
     - Faithful Customers
     - Highest Paying Customers
     - Most Loyal Customers
     - Needs Attention
     - Good Customers
     - Average Customers

4. **Machine Learning Models**
   - Implemented multiple classifiers:
     - Logistic Regression
     - Support Vector Machine
     - Decision Tree
     - Random Forest
   - Used RandomizedSearchCV for hyperparameter tuning

### Results
- **Data Quality**: Improved from 541,909 to 530,693 clean records
- **Segmentation**: Successfully categorized customers into 7 distinct groups
- **Model Performance**: Multiple classification models implemented for customer behavior prediction
- **Business Impact**: Actionable insights for targeted marketing strategies

## 🛠️ Technical Stack
- Python 3.x
- Key Libraries:
  - Pandas & NumPy for data manipulation
  - Scikit-learn for machine learning
  - Matplotlib & Seaborn for visualization
  - Datetime for temporal analysis

## 📈 Key Metrics
- Dataset Size: 541,909 initial records
- Clean Dataset: 530,693 records
- Number of Segments: 7
- RFM Scoring Scale: 1-5
- Multiple ML Models Implemented

## 🎯 Business Applications
- Targeted Marketing Campaigns
- Customer Retention Strategies
- Personalized Customer Experience
- Revenue Optimization
- Customer Lifetime Value Prediction

## 🔄 Future Improvements
- Implement deep learning models
- Add real-time segmentation capabilities
- Include more behavioral features
- Develop an automated reporting system
- Create interactive dashboards
