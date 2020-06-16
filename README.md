# Customer-Segmentation-Clustering
Customer Segmentation refers to the process of identifying several segments of customers from a pool of customer database which helps businesses to target potential user base. The technique of customer segmentation depends upon various differentiating factors such as demographics, economy status, geography etc. All these factors plays a vital role in the customer segmentation process. Companies that deploy customer segmentation are under the notion that every customer has different requirements and require a specific marketing effort to address them appropriately. In order to achieve this target, clustering mechanism of Unsupervised Machine Learning Algorithm is used specifically K-Means Clustering. Lets see how this is implemented.

# Dataset Details :
The dataset contains transactions on an e-commerce website between the period Feb 2018 to Feb 2019 from customers across different countries.
File: transaction_data.csv Columns
UserId - Unique identifier of a user.
TransactionId - Unique identifier of a transaction. If the same TransactionId is present in multiple rows, then all those products are bought together in the same transaction.
TransactionTime - Time at which the transaction is performed
ItemCode - Unique identifier of the product purchased
ItemDescription - Simple description of the product purchased
NumberOfItemsPurchased - Quantity of the product purchased in the transaction
CostPerItem - Price per each unit of the product
Country - Country from which the purchase is made.

# Tools and Libraries Used :
1. Jupyter Notebook
2. Pandas Library (for Data Manipulation)
3. sklearn
4. Seaborn
5. MatplotLib

# Methodology
1. Cleaning and Pre-processing the dataset which by imputing the Missing values using efficient techniques, Removing irrelevant characters values etc.
2. Performing Descriptive Analysis to detect any anomalies within the dataset feature values.
3. Performing Feature Engineering to create other useful features from the existing features for example- in the dataset we are given with costPerItem and NoOfItemsBought in each transaction, so simply by multiplying the two feature values we can create a new feature which would tell us about the total amount spent in each transaction from the particular userID for that specific ItemID.
4. Encoding the categorical variables with LabelEncoder for ordinal variables and One-Hot Encoding for Nominal variables. Sometimes One-Hot Encoding may give out Sparse Classes, they have been dealt appropriately in the following project.
5. Exploratory Data Analysis is required to gain insights about the existing data using various libraries such as seaborn or MatplotLib to create scatterplots, barplots, histogram etc to perform Univariate and Bivariate Analysis.
6. Some variables are required to be transformed (Log, Root etc) to get rid of the skewness in their distribution to make them normally distributed.
7. Kmeans clustering analysis is performed after appropriate value of K has been determined using the 'Elbow Method'. The final clustering is performed with the best value for K that will determine the number of clusters in your data.
8. The clusters are visualised using the Scatterplot and various analysis are performed to based on the results for business purposes.

# Results

# Conclusion
Hence, we developed a Customer Segmentation Model using a class of machine learning known as Unsupervised Learning. Specifically, we made use of a clustering algorithm called K-means clustering. We analyzed and visualized the data and then proceeded to implement our algorithm. 
