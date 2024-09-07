# Heart-Disease-Prediction 

# INTRODUCTION:
Heart disease puts an enormous burden on the global healthcare system. If the problem is attended to on time, many adverse events could be prevented. Machine Learning holds promise in diagnosing the possibility of adverse cardiac outcomes in high-risk individuals.In this article, we will be closely working with the heart disease prediction and for that, we will be looking into the heart disease dataset from that dataset we will derive various insights that help us know the weightage of each feature and how they are interrelated to each other but this time our sole aim is to detect the probability of person that will be affected by a saviour heart problem or not.

# The Heart Disease prediction will have the following key takeaways:
1. Data insight: As mentioned here we will be working with the heart disease detection dataset and we will be putting out interesting inferences from the data to derive some meaningful results.
2. EDA: Exploratory data analysis is the key step for getting meaningful results.
3. Model building: In this phase, we will be building our Machine learning model for heart disease detection.

# RESULTS AND DISCUSSIONS
1.At first we importing the libraries.
2.Then we read the csv file using Pandas library. And print the first 10 rows of dataset and the last 5 rows of dataset. 
3.Let’s analyse the dataset to get a clear insight.
4.The dataset have 303 rows and 14 columns.
5.Here we see that no null values are present in the dataset. And the datatype of values also.
6.Now let’s see the statistical measure of the dataset by using command “data.describe()”.
7.The describe() method is used for calculating some statistical data like percentile, mean and std of the numerical values of the Series or Dataframe.
8.The value_counts() method returns the object containing counts of unique values in sorted order. 
9.Here we see the unique values of target in sorted order. Here we clearly see that 165 have defective heart and 138 have a healthy heart.
10.Now we checking the correlation among the all features.And plot the graphical picture of that using seaborn. 
11.Above graphical representation shows which feature is negatively correlated and which is positively correlated. 
12.By far we have checked the correlation between the features but it is also a good practice to check the correlation of the target variable.
13.Insights from the above graph are: Four feature( “cp”, “restecg”, “thalach”, “slope” ) are positively correlated with the target feature.Other features are negatively correlated with the target feature.
14.So, we have done enough collective analysis now let’s go for the analysis of the individual features.
15.Now do the age analysis. Here we will be checking the 50 ages and their counts.
16.Here we can see that the 58 age column has the highest frequency.
17.Let’s check the range of age in the dataset.
18.The minimum age is 29 and maximum age is 77. 
19.Divide the Age feature into three parts – “Young”, “Middle” and “Elder”.
20.Here it is clearly visible that, Ratio of Male to Female is approx 2:1.Here 1- Male and 0- Female.
21.Now let’s plot the relation between sex and slope.slope: the slope of the peak exercise ST segment — 0: downsloping; flat; 2: upsloping 0: downsloping; 1: flat; 2: upsloping.









