# Data_Preprocessing_Techniques

## Data Preprocessing:
Data preprocessing is a technique that helps us solve data quality issues which include noise, outliers, missing values, duplicates etc. Preprocessing data can help us in improving the data mining analysis and help predict results with higher accuracy.

### This project is divided into two parts –
- Part 1 – Understanding and implementing the data preprocessing tutorial.
- Part 2 – Data preprocessing on different datasets of different domains.

### Part 1: Data Preprocessing:
Dataset: Datasets used
- breast-cancer-wisconsin.data
- auto-mpg.csv
- iris.csv
- DTW_prec.csv

#### Following is the implementation of data preprocessing techniques for different datasets.

##### a) breast-cancer-wisconsin.data
- Missing values - Some of the features in the dataset are missing or were not collected so we drop the null values   
	using dropna() or replace them with their median or mean values.
- Removing Outliers - Identified outliers using box plot and computed the z-scores to discard outliers.
- Duplicate data - Removed duplicate rows using drop_duplicates().
- Sampling - Selected samples from datasets using various sample sizes.
- Discretization - Transformed Clump Thickness (continuous value) to a categorical value

##### b) auto-mpg.csv
- Shuffling data frames - Shuffled datasets in order to get better prediction results.
- Sorting dataframes - Sorted values in ascending or descending order.
- Dropping fields - Dropped certain fields which can help to discard unnecessary columns or irrelevant data to our problem definition.
- Calculated fields - Added a new field that gives the weight in kilograms by doing some operations on existing attributes.
- Feature Normalization - Normalized the MPG attribute using the z-score method.
- Concatenating rows and columns - Used the concat function to concatenate name and
horsepower.

##### c) iris.csv
- Label encoding - Using the tensorflow function encode_text_index, we label encoded the “species” column.
- One Hot encoding - Using the tensorflow function encode_text_dummy, we one hot encoded the “species” column.
- Creating X and Y data - Used the to_xy function before passing the data for training and testing.
- Training and Validation - Split the data into train and test in a way where 75% is training and 25% is testing.

##### d) DTW_prec.csv
- Aggregation - Time series data grouped and aggregated by day, month, and year to obtain respective precipitation values.

##### e) Image dataset (Picture[1-16].jpg)
- PCA (Principal Component Analysis) - Reduced the data from its higher dimensional space to a lower dimensional space. Implemented PCA on the images dataset having 16 RGB files.

------------
-------------
### Part 2: Data preprocessing on Unclean Datasets of Different Domains

Dataset: 
- Candyhierarchy2017.csv (makingnoiseandhearingthings.com)
- Online Retail.xlsx
- titantic_test.csv and titanic_train.csv
- Seattle_Salary.csv

#### Following is the implementation of data preprocessing techniques for different datasets:

##### a) CandyHierarchy2017.csv:
Domain area - Candy hierarchy data
This is a Candy hierarchy data for the 2017 Boing Halloween candy hierarchy. It is collected by taking a survey. This dataset has more than 2400 surveyed entries with 120 attributes. Initially we preprocessed the data to find what people in the United States, in a certain age group, think about Hershey’s milk chocolate.

##### b) Online Retail.xlsx
Domain area – Online retail data
This is a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

Data description: InvoiceNo StockCode Description Quantity InvoiceDate UnitPrice
CustomerID Country.

##### c) Titanic data:
This is the Titanic disaster data which has information of passengers traveling and information about their survival. It is split into two sets: titanic_train.csv and titanic_test.csv.



