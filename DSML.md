### DSML MCQs 

## Unit 1 An Intro To Data Science

> Q1. Types of Big data are?

    1. Structured Data
    2. Unstructured Data
    3. Semi-structured Data
    4. All the above

**Answer**  : All the above (Option 4)

<image src="./Images/typesofdata.jpg"></image>

> Q2. Which is the correct sequence of phases of Data Analytics life cycle

    1. Discovery-->Modelplanning & building-->datapreparation-->communicating result-->operationalize

    2. Modelplanning & building-->DataPreparation-->communicating result-->operationalize-->Discovery

    3. Discovery-->DataPreparation-->model Planning & building-->communicating result->operationalize

    4. DataPreparation-->model Planning & building-->operationalize-->communicatingresult->Discovery

**Answer  :** Option 3

<image src="./Images/dataanalyticlifecycle.jpg"></image>

> Q3. Pick out the correct statement.

    1. Raw data is original source of data
    2. Preprocessed data is original source of data
    3. Raw data is the data obtained after processing steps
    4. None of the mentioned

**Answer :** Option 1

<https://www.coursehero.com/file/p56n4lcu/Point-out-the-correct-statement-a-Raw-data-is-original-source-of-data-b/>

<https://www.datamation.com/big-data/raw-data/#:~:text=Raw%20data%20is%20the%20starting%20phase%20of%20all,You%20can%20trust%20the%20integrity%20of%20raw%20data.>

> Q.4 Which is not among the 5 V's of Big data?

    1. Velocity
    2. Value
    3. Variety
    4. None of the above

**Answer :** Option 4

https://www.geeksforgeeks.org/5-vs-of-big-data/

> Q5. which phase of the data analytics lifecycle usually takes the longest time?

    1. Data Preparation
    2. Model Planning
    3. Model Building
    4. Communicate Results

**Answer :**  Option 1

https://vceguide.com/which-phase-of-the-analytic-lifecycle-would-you-expect-to-spend-most-of-the-project-time/

> Q6. Which of the following can be generally used to clean and prepare big data?

    1. Pandas
    2. Data Lake
    3. U-SQL
    4. Data Warehouse

**Answer :**  Option 4

https://www.google.com/search?q=Which+of+the+following+can+be+generally+used+to+clean+and+prepare+big+data

> Q7. When data are collected in a statistical study for only a portion or subset of all elements of interest we are using ______

    1. Sample 
    2. Parameter
    3. Population
    4. None

**Answer :**  Option 1

<img src="./Images/sample.jpg">


> Q8. The process of quantifying data is referred to as?

    1. Decoding
    2. Structure
    3. Enumeration
    4. Coding

**Answer :**  Option 3

<img src="./Images/enumeration.jpg">

<br>

> Q9. What answers the question "What has happened?

    1. Descriptive analytics
    2. Predictive analytics
    3. Prescriptive analytics
    4. None

**Answer :**  Option 3

*Explanation : Prescription is done on past data to predict the future* 

> Q10. what answers the question "What will happen?"?

    1. Descriptive analytics
    2. Predictions analytics
    3. Prescriptive analytics
    4. None

**Answer :** Option 2

*Explanation : As predictive model predicts what will happen in the future*

> Q11. _____ useful knowledge from data to solve business problems can be treated systematically by following a process with reasonably well-defined stages.

    1. Extracting
    2. Preparing
    3. Prescribing
    4. None

**Answer :**  Option 1

*Explanation : Knowledge cannot be prescribed, prepared so it has to extracted*

> Q12. ______ is most important language for Data Science.

    1. Java
    2. R
    3. Python
    4 .None of the mentioned

**Answer :** Option 3

*Explanation : https://www.dasca.org/world-of-big-data/article/top-6-programming-languages-for-data-science-in-2021*

> Q13. Data Analysis is a process of ______

    1. Inspecting data
    2. Data Cleaning
    3. Transforming of data
    4. All of the mentioned above

**Answer :** Option 4

*Explanation : The process of reviewing, cleansing, and manipulating data with the objective of identifying usable information, informing conclusions, and assisting decision-making is known as data analysis. Data analysis is important in today's business environment since it helps businesses make more scientific decisions and run more efficiently.*

> Q14. By 2025, the volume of data will increase to ______

    1. TB
    2. YB
    3. ZB
    4. EB

**Answer :**  Option 3

*Explanation : It is projected that 2.5 quintillion bytes of data are created every day, with the volume of digital data expected to reach Zeta Byte by 2025.*

> Q15. A good data analytics solution includes a viable self-service ___

    1. Data mining
    2. Data wrangling
    3. Data warehouse
    4. None of the mentioned above

**Answer :** Option 2

*Explanation : A smart data analytics solution incorporates self-service data wrangling and data preparation features so that data may be simply and quickly gathered from a range of incomplete, difficult, or messy data sources and cleansed for mashup and analysis.*

## Unit 2  Preprocessing and Extracting meaning from Data 

> Q1. Which of following is a problem that missing data could cause?

    1. Some visualizations don't 
       work with missing data
    2. Some types of data  
       cleaning steps won't work 
       with null values
    3. Machine learning models 
       will break when they 
       encounter null values
    4. All the above

**Answer :**  Option 2

*Explaination : Visualization represents the remaining values instead of missing values, Machine learning models do work with less accuracy which only means that Data cleaning steps will not work*

> Q2. Select all valid strategies for dealing with null values in a column containing numerical data, assuming that we can't afford to lose any data.

Strategies : <br>

1. Replace missing values with the column median
2. Replace missing values with the column mode
3. Convert the column to categorical format using Coarse Classification ('Binning')
4. Leave the Null values as is.

<br>

    1. Strategy 1 & Strategy 2
    2. Strategy 3 & Strategy 1
    3. Strategy 4 & Strategy 1
    4. Strategy 3 & Strategy 2 

**Answer :**  Option 2

*Explanation : While replacing the values in columns we use median not mode so Strategy 1 is fixed. Considering the scenario we cannot leave the null values as it is so Strategy 3 is also fixed so answer will be Option 2*

> Q3. Which of the following code snippets returns a count of the missing values in each column of a DataFrame?

```python
1. some_dataframe.isna().sum()
2. some_dataframe.dropna()
3. some_dataframe.is_na().sum()
4. some_dataframe.value_counts.is_na()
```

**Answer :**  Option 1

*Explanation : some_dataframe.isna() gives null values for each column we just have to use sum to get all the null values*

> Q4. Impact of having noise in data / noisy data?

    1. Increases amount of storage space required 
    2. Decreases amount of storage space required 
    3. No impact on amount of storage space required
    4. None of the above

**Answer :** Option 1

*Explanation : A big chunk of your data is junk, but that gets stored in your database somehow creating the requirement of big database and cost associated with it.*

> Q5 Which learning method, algorithm or popular technique commonly used for handling the noise in data mining?

    1. Clustering 
    2. Binning
    3. Regression
    4. All the above

**Answer:**  Option 4

*Explanation : Binning smooths the corrupted data and hence is used to handle noise in data. Other useful techniques to find out noise in data are: clustering method, support vector machine (SVM) algorithm etc.*

> Q6. What happens in clustering method like k-means that is used to handle noise or noisy data in data mining?

    1. Data is organised into clusters
    2. Data is arranged in a line
    3. Any of the above
    4. None of the above

**Answer :** Option 1

*Explanation : The Values lying outside of it are considered as outliers. Thus clusters are made.*

> Q7. What is the difference between a bar chart and a histogram?

    1. Bar charts represent numbers, 
       whereas histograms represent 
       percentages 
    2. A histogram does not show the entire  
       range of scores in a distribution. 
    3. There are no gaps between the bars on 
       a histogram
    4. Bar charts are circular, 
       whereas histograms are square.

**Answer :**  Option 3

*Explanation : Histograms are used to display interval/ratio variables, which involve a continuous range of values, and so there are no gaps between the bars that represent each category.*

> Q8. The worst thing that missing data does is lower sample size and reduce power.

    1. True 
    2. False

**Answer :**  Option 2

*Explanation : If you lose half your sample and have no significant results, you notice.  If the regression coefficients or standard errors aren’t what they’re supposed to be, there’s no way to tell.*

> Q9. Data reduction  is/includes ________

    1. Data-flow diagram show, 
       how data is processed at different stages 
       in the system
    2. registering all/ selected activities of a 
       computer system.
    3. Technique used to transform raw data into 
       a more useful form..
    4. Data is shifted to modern data base 
       management system.

**Answer :** Option 3

*Explanation : In data reduction useless data is removed*

> Q10 Which of the following is not a data pre-processing methods?

    1. Data Visualization
    2. Data Discretization
    3. Data Cleaning 
    4. Data Reduction

**Answer :**  Option 1

*Explanation : Data Visualization is a step after data pre-processing*

> Q10. In Binning, we first sort data and partition into (equal-frequency) bins and then which of the following is not a valid step?

    1. Smooth by bin boundaries 
    2. Smooth by bin mean
    3. Smooth by bin median
    4. Smooth by bin values 

**Answer :**  Option 4

*Explanation : We can smooth the data by bin boundaries, mean, median only binning by values doesn't make sense here*

> Q11. Which of the following statements is true for correlation analysis?

    1. It is a bivariate analysis
    2. It is a multivariate analysis
    3. It is a univariate analysis
    4. Bivariate analysis and univariate analysis

**Answer :**  Option 1

*Explanation : It investigates the relationship between two data sets, with a pair of observations taken from a single sample or individual. Can be both bivariate and univariate*

> Q12. Choose the least likely assumption of a classic normal linear regression model

    1. The independent variable and the dependent 
       variable have a linear relationship.
    2. The independent variable is normally distributed
    3. There is no randomness in the independent 
       variable.
    4. None of the preceding.

**Answer :**  Option 2

*Explanation: https://economictheoryblog.com/2015/04/01/ols_assumptions/*

> Q13. The correlation coefficient is?

    1. The square of the coefficient of determination
    2. Can never be negative
    3. The square root of the coefficient of determination.
    4. The same as r square

**Answer :**  Option 3

*Explanation : Coefficient of Determination has been defined as the square of the coefficient of correlation*

> Q14. What is the value of the correlation coefficient if the coefficient of determination is 0.81?

    1. Must be positive
    2. 0.656
    3. Either +0.9 or -0.9
    4. Must be negative

**Answer :**  Option 3

*Explanation : Coefficient of Determination has been defined as the square of the coefficient of correlation*

> Q15. Regression modelling is a statistical tool for building a mathematical equation depicting how?

    1. One explanatory and one or above response 
       variables are related
    2. There is a link between one response 
       variable and one or many explanatory variables
    3. Several explanatory and response  
       variables are related
    4. All of the above are correct.

**Answer :**  Option 2

*Explanation : Regression analysis is one of the machine learning techniques that are used to describe the relationship between variables. There are two types of variables in regression analysis: independent variables (whose values can be manipulated) and dependent variables (whose values depend on the values of the independent variables). Regression analysis establishes the relationship between a single dependent variable and one or more independent variables. Therefore, regression analysis is a statistical procedure for developing a mathematical equation that describes how one dependent and one or more independent variables are related.*

> Q16. If any regression coefficient’s value is zero, the two variables are

    1. Independent
    2. Qualitative
    3. Dependent
    4. None of the above

**Answer :** Option 1

*Explanation : Regression line is a straight line parallel to x axis*

> Q17. Which of the given strategies helps provide the prediction mechanism by analysing the relationship between two variables?

    1. Regression
    2. Standard error
    3. Correlation
    4. None

**Answer :**  Option 1

*Explanation : Regression analysis is one of the machine learning techniques that are used to describe the relationship between variables and also make prediction on one variable*

> Q18. For two variables, X and Y, there can be a maximum of ___ lines

    1. One
    2. Two
    3. Three
    4. Four

**Answer :**  Option 1

*Explanation : In a graph there can be multiple regression lines but max we have to draw one perfect line which can pass through as many points as possible*

> Q19. Which of the following is true for the coefficient of correlation?

    1. The coefficient of correlation is not dependent on the change of scale
    2. The coefficient of correlation is not dependent on the change of origin
    3. The coefficient of correlation is not dependent on both the change of scale and change of origin
    4. None of the above

**Answer :** Option 2

*Explanation : Correlation coefficient is not affected by change of origin it is only affected by change of scale*

> Q20. Coefficient od Regression is independent of?

    1. Only Scale
    2. Only Origin
    3. Both Scale and Origin
    4. None

**Answer :**  Option 2

*Explanation : Correlation coefficient is not affected by change of origin it is only affected by change of scale* 

## Unit 3 Unsupervised Modelling

> Q1. For two runs of k-Mean clustering is it expected to get same clustering results?

    1. True
    2. False

**Answer :**  Option 2

*Explanation : we can get same clusters at any iteration of k-means method*

> Q.2 Terminating condition for k-Means method?

A. For a Fixed number of iterations <br>
B. Assignment of observation of clusters does not change between iterations <br>
C. Controids do not change between successive iterations
<br>
D. Terminate RSS when falls below a threshold

    1. A,C and D
    2. A,B and C 
    3. A,B and D
    4. All the above

**Answer :** Option 4

*Explanation : A,B,C all the methods are true when we cconsider normal clustering but RSS clusting is a type of clustering where condition is to terminate RSS when fallen below threshold*

> Q3. The difference between supervised learning and unsupervised learning is given by

    1. Unlike unsupervised learning, 
       supervised learning needs labeled data
    2. Unlike unsupervised learning, 
       supervised learning can be used to 
       detect outliers
    3. There is no difference
    4. Unlike supervised leaning, 
       unsupervised learning can 
       form new classes

**Answer :**  Option 1

*Explanation : Supervised learning uses labeled data and unsupervised learning doesn't use labeled data*

> Q4. Can decision trees be used for performing clustering?

    1. True 
    2. False

**Answer :**  Option 1

*Explanation : Decision trees can also be used to for clusters in the data but clustering often generates natural clusters and is not dependent on any objective function.*

> Q5.How can Clustering (Unsupervised Learning) be used to improve the accuracy of Linear Regression model (Supervised Learning):

A. Creating different models for different cluster groups. <br>
B. Creating an input feature for cluster ids as an ordinal variable<br>
C. Creating an input feature for cluster centroids as a continuous variable.<br>
D. Creating an input feature for cluster size as a continuous variable.

    1. A only
    2. B and C
    3. B and D
    4. All the above

**Answer :** Option 4

*Explanation : Creating an input feature for cluster ids as ordinal variable or creating an input feature for cluster centroids as a continuous variable might not convey any relevant information to the regression model for multidimensional data. But for clustering in a single dimension, all of the given methods are expected to convey meaningful information to the regression model.*

> Q6. In which of the following cases will K-Means clustering fail to give good results?

A. Data points with outliers<br>
B. Data points with different densities<br>
C. Data points with round shapes<br>
D. Data points with non-convex shapes<br>

    1. A and B
    2. B and C
    3. A and D
    4. A, B and D

**Answer :**  Option 4

*Explanation :*

<img src="./Images/k means cluster.jpg">

<br>

> Q7. Which of the following combination is incorrect?

    1. Continuous – euclidean distance
    2. Continuous – correlation similarity
    3. Binary – manhattan distance
    4. None of the mentioned

**Answer :**  Option 4

*Explanation : All distance/similarity do make sense*

> Q8. K-means is not deterministic and it also consists of number of iterations.

    1. True
    2. False

**Answer :** Option 1

*Explanation : K-means clustering produces the final estimate of cluster centroids.*

> Q9. Which of the following clustering type has characteristic shown in the below figure?

<br>

<img src="./Images/clsutering types.jpg">

    1. Partitional
    2. Hierarchical
    3. Naive bayes
    4. None

**Answer :** Option 2

*Explanation : Hierarchical clustering groups data over a variety of scales by creating a cluster tree or dendrogram.*

> Q10. Which of the following is required by K-means clustering?

    1. defined distance metric
    2. number of clusters
    3. initial guess as to cluster centroids
    4. All the above.

**Answer :**  Option 4

*Explanation : K-means clustering follows partitioning approach.*

> Q11. Which of the following statements about KMedoids algorithm are true?

A. K-Medoids algorithm can 
determine spherical shaped clusters 
B. Number of clusters to be   
    determined must be specified
C. Less sensitive to noise data than KMeans
D. Suitable for large volume of data (Scalable)

    1. A and B
    2. C and D
    3. A,B and C
    4. A and D

**Answer :**  Option 3

*Explanation : K mediods is less sensitive to noise and can determine spherical clusters. At the start we need to specify the number of clusters.* 

> Q12. K-medoids is a kind of agglomerative clustering.

    1. True
    2. False

**Answer :**  Option 2

*Explanation : K-medoids is a partitioning clustering algorithm*

> Q13. Pick out a k-medoid algoithm.

    1. dbscan.
    2. birch
    3. pam
    4. None

**Answer :**  Option 3

*Explanation : K-medoids falls under pam*

> Q14. What is the advantage of the k-Medoids Clustering Algorithm over the k-Means Clustering (Lloyd's) Algorithm?

    1. uses iterative refinement 
    2. more resistant to outliers 
    3. all of the above 
    4. represents clusters by center 

**Answer :** Option 2

*Explanation : K-Medoids falls under PAM algorithms. PAM is less sensitive to outliers than other partitioning algorithms.*

> Q15. Which of the following approaches can be used in Hierarchical Clustering?

    1. Agglomerative Clustering
    2. Divisive Clustering
    3. Both of the above
    4. None of the above

**Answer :** Option 3

*Explanation : There are two types of hierarchical clustering, Divisive and Agglomerative.*


