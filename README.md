# SBSPS-Challenge-7214-SDG-2-Zero-Hunger

<h3>Agriculture has been the backbone of Telangana's economy for a long time. There are multiple ways to increase and improve the crop yield and the quality of the crops. In this case study, we have directed to predict the price of the crop, for which we used real time data of crops Groundnut, Maize, and Bengal Gram. We have analyzed the type of crop, current price, and its location of harvest in Telangana. By analyzing these features we could predict the price of the crop.</h3>

**Steps Performed:**

- Imported both input CSV files using Pandas read_csv function
- Checked Null values using isnull function
- Checked unique values from Categorical columns using value_counts() function
- Visualized data using different graphs (Pie, Histogram, Scatter Plot) using **Matplotlib , Seaborn library and Tableau.
- Used LabelEncoder to convert Categorical columns to Numerical columns
- Selected Features & Targeted Column & assigned to a Variable
- Created Training & Testing Data using train_test_split
- Used XGBoost Regression Machine Learning model. 
- Used K-Fold for Validation
```
   Maximum Accuracy is around 99.99603365232768 % using XGBoost Model
```
**Data Visualization with Tableau **
```
https://public.tableau.com/app/profile/daripalli.aparna
```

METHODOLOGY: 

The following workflow has been followed for developing our model:
1.Data Preprocessing:  Data Preprocessing is a data mining technique used to transform the raw data into useful and efficient format. The data here goes through 2 stages:Data Cleaning and Data Transformation.- Data Cleaning: It is very important for data to be error free and free of unwanted data. - Data Transformation: Data Transformation is transformation of the datasets mathematically.
2.Exploratory data analysis:  is an approach to understand the datasets more keenly by the means of visual elements like scatter plots, bar plots, etc. This allows us to identify the trends in the data more accurately and to perform analysis accordingly. 
3. Data Visualization: This has been implemented using Tableau. The adjacent chart is an example of how we used Data Visualization concept. The Chart is called Packed Bubble Chart. Here size and optionally colour of bubbles are used to visualize the data for which we need 1 or 2 dimensions against 1 or 2 measures to build this chart. 4.XGBoost Model:  XGBoost is a decision-tree-based ensemble Machine Learning algorithm that uses a gradient boosting framework. In prediction problems involving unstructured data (images, text, etc.) artificial neural networks tend to outperform all other algorithms or frameworks.
 5. K Fold Cross Validation: k-fold cross validation is a procedure used to estimate the skill of the model on new data.

Conclusion: In this study, certain Data Analytics techniques and Machine Learning model were adopted to estimate crop price analysis with real-time data. Linear Regression is employed for discovering important information from the agricultural datasets. Using this real-time data and Machine Learning model we could predict the price of the crop at different regions of Telangana for different volumes. XG Boost Model is giving the highest accuracy of 99.9960 %, hence we will use XGBoost Model for prediction and is reliable.
