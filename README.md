# **Human Activity Recognition Using Smartphone Data**

 The Human Activity Recognition database was built from the recordings of 30 study participants performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The objective is to classify activities into one of the six activities performed.

 ## ***Data pre-processing***:

 In Data pre-processing perform various activities like:

        Checking Duplicates
        Checking and removing NULL/missing values
        Checking for class imbalance
![Class Imbalance ](<Plot Images/BarPlotActivity.png>)
Class Imbalance 
 
 
## ***Exploratory Data Analysis***:

EDA involves visualizing the data to see how the different features vary across different activities, or computing summary statistics such as mean and standard deviation to understand the distribution of the data.

![Activities](<Plot Images/activities.png>)
![tBodyAccMag-mean](<Plot Images/box1.png>) 
![Angle between X-axis and gravityMean](<Plot Images/box2.png>) 
![Angle between Y-axis and gravityMean](<Plot Images/box3.png>)
![PCA](<Plot Images/PCA.png>)
![TSNE](<Plot Images/tsne.png>)


## ***ML Model***:

Decision tree model
![Decision tree](<Plot Images/Decision tree model with Hyperparameter tuning and cross validation.png>)

Kernel SVM
![Kernel SVM](<Plot Images/ernel SVM model with Hyperparameter tuning and cross validation.png>)

Logistic Regression
![Logistic Regression](<Plot Images/Logistic Regression model with Hyper-paramerter Tuning and Cross - Validation.png>)








