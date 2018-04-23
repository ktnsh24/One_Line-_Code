# One Line Code for Data Examination

### Introduction


Whenever we start to examine any dataset. We generally take a look at **Shape of the data, Top, Bottom and Random Sample of the observations, Data type, data statistics and the missing values** available in the dataset. In order to examine everything I mentioned, we have to write some code, specifically finding the data missing percentage. I try to make this code. With this, a user can just run this one line of code in their IPython session and can examine without writing any other code. Below, I have described step by step procedure to run this code.  

The code will help user's to examine their data by just running this external code. By running this external code, a user can examine,

* [The shape of the data](#The-shape-of-the-data)
* [Top observations of the data](#Top-observations-of-the-data)
* [Bottom observations of the data](#Bottom-observations-of-the-data)
* [Random observations of the data](#Random-observations-of-the-data)
* [Choice of the observations from the data](#Choice-of-the-observations-from-the-data)
* [Data type of the all features and target variables](#Data-type-of-the-all-features-and-target-variables)
* [Summary statistics of the dataset variables](#Summary-statistics-of-the-dataset-variables)
* [Total missing value percentage of the dataset](#Total-missing-value-percentage-of-the-dataset)
* [Missing values sum and percentage in each observation](#Missing-values-sum-and-percentage-in-each-observation)

### Guidence required

Hello Everyone, this is something I did because I'm trying to improve my python skills. I beleive there could be some fault in my code or any mistake. I will appreciate your response and view on it. If you think there is possibility to improve this code. Please help me with your guidence. 

If you want to use this code, you are allowed to use it with appropriate reference. 

### Step 1 (Most Important one)
As different user titled their data frame differently but my code only understands one title name "dataset". So In order to use my code you need to do this👇👇👇.

![Screen%20Shot%202018-04-23%20at%207.12.14%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%207.12.14%20PM.png)

Or if you don't want to do this just titled your data frame as the 'dataset'. Like this 👇👇👇

![Screen%20Shot%202018-04-23%20at%207.20.13%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%207.20.13%20PM.png)

### Step 2 Running External Code: %run

As you begin developing more extensive code, you will likely find yourself working in both IPython for interactive exploration, as well as a text editor to store code that you want to reuse. Rather than running this code in a new window, it can be convenient to run it within your IPython session. This can be done with the %run magic.

My External code name is One_Line_Code.ipynb

You can execute this code from your IPython session as follows:

![Screen%20Shot%202018-04-23%20at%207.32.12%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%207.32.12%20PM.png)

# Examine the External code output

After you've run this script, all functions defined in it are available for use in your IPython session.

# The shape of the data

![Screen%20Shot%202018-04-23%20at%207.42.51%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%207.42.51%20PM.png)

# Top observations of the data

My code is flexible. In order to examine the top observations, the code will not show you the top 5, 10 or 20 observations but it is up to user how many top rows/observation he want to see. The code asks to user to fill the number. The number is basically tell the the number of top observations he want to see.

![Screen%20Shot%202018-04-23%20at%207.52.44%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%207.52.44%20PM.png)

After filling the number, **PRESS ENTER**, the Top rows will look like this. (I will fill 5.)

![Screen%20Shot%202018-04-23%20at%208.00.17%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%208.00.17%20PM.png)

# Bottom observations of the data

Same like previous one, here user have also freedom to examine the number of bottom observations. He can fill any number.

![Screen%20Shot%202018-04-23%20at%208.16.04%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%208.16.04%20PM.png)

# Random observations of the data

For example, here I oly want to see 2 random samples. So enter the value 2.

![Screen%20Shot%202018-04-23%20at%208.20.16%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%208.20.16%20PM.png)

# Choice of the observations from the data

Choice of the observation allows user to look into any between of observations he want to see in the dataset. He only has to filled the index numbers. 

![Screen%20Shot%202018-04-23%20at%208.20.52%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%208.20.52%20PM.png)

# Data-type of the all features and target variables

From the type of data, the user can identify, features and target variables **Data type and Total non-null values**.

![Screen%20Shot%202018-04-23%20at%208.21.18%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%208.21.18%20PM.png)

# Summary statistics of the dataset variables


![Screen%20Shot%202018-04-23%20at%208.21.39%20PM.png](attachment:Screen%20Shot%202018-04-23%20at%208.21.39%20PM.png)

# Total missing value percentage of the dataset

In this case, there were no missing value present in the dataset. So It will show 0%.


![alternativetext](/Users/ketansahu/Desktop/percent+sum.png)
# Missing values sum and percentage in each observation

As we have seen, the data has no missing value, so observations count and percentage is also zero. Hence you will see the message like here. Also you can not see any table now. But, If your data has any missing values in any of the raw. you will see the sum and percentage in the table dataframe.



