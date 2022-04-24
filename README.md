# CZ1115 Data Science Project - Hybrid Recommender System for Fashion Articles

The e-commerce market has experienced unprecedented growth in the last 5 years. The increasing significance of such a service in this digital age, have forced retailers to extract value from newly unlocked data points

With the right analysis, the data can be used to better cater to customer preferences to combat declining sales, as well as more accurately predict inventory to minimize inventory costs.
But how should retailers, of any size, approach their data analysis effectively?

We answer the following question which is valuable to fashion retailers. Which fashion articles will a particular customer be interested in purchasing next?

## Contributors

- @Rhys Lie- Data Visualization, Data Extraction, Data Wrangling, EDA, General Flow
- @Daniel Yang- Neural Networks, Machine Learning, Hybrid Recommender
- @Joel Lim- Data Visualization, Data Extraction, Data Wrangling, EDA, General Flow

## Link to Dataset:

https://entuedu-my.sharepoint.com/:f:/g/personal/dyang009_e_ntu_edu_sg/Er-4nHfuKIRFqCI4r8eYoSwBIIIgb25CXmITO1ppEGmPuQ?e=FDM96Y

## Libraries and Tools used

- Pandas
- Seaborn
- Matplotlib
- Sklearn
  -> Linear regression
  -> NearestNeighbours
  -> Ordinal Encoder
  -> SelectKBest
  -> chi2
  -> pairwise distance
- Keras  
  -> ResNet50
  -> Xception

## Files contained in this folder:

### Slides

The slides acts as a summary of our project. It covers the most important parts of our project, as well as areas in which we wish to emphasize.

### articlesEDA.ipynb

Individual Exploratory Data Analysis done on the articles sold by the fashion retailer.

### transactionsEDA.ipynb

Individual Exploratory Data Analysis done on the transactions involving the fashion retailer and customers.

### customersEDA.ipynb

Individual Exploratory Data Analysis done on the customers that visit the fashion retailer.

### combinedEDA.ipynb

Combined Exploratory Data Analysis done on the 3 datasets mentioned above.

### fullWorkflow.ipynb

Notebook detailing the full flow of how we answer the question: Which fashion articles will a particular customer be interested in purchasing next?

### feature importance & machine learning model.ipynb

Notebook details the training process of ResNet50 and Xception models and the extraction of respective feature maps. A few examples are used to demonstrate the reccomendation capabilities of each approach.

## What did we learn from this project?

- The selected fashion retail company targets young adults and older mature adults
- Ladieswear and Divided (Teens) product categories are their main revenue drivers. Average sales transaction quantum is relatively small.
- Revenue and purchase transactions trends are cyclical, consistent and steady
- We developed a full data pipeline to make use of the available dataset effectively and efficiently
- Using hybrid filtering (content based and collaborative filtering), we determine when a customer will make a purchase next and what they might purchase given their spending habits and article preferences
- Leveraging a deep learning network ResNet, we use CNN to train the model on product images and KNN for evaluating an article recommendation

## References

- https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations
- https://www.kaggle.com/code/gowrishankarin/resnet50-vs-inceptionv3-vs-xception-vs-nasnet/notebook
