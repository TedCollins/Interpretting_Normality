# Interpretting_Normality
This application helps a data analyst interpret the meaning of normality tests by letting them experiment with normality tests of normal and non-normal distributions

###Understanding Data Distributions and Testing for Normality###

#By Ted Collins on 1/25/2015#

###Purpose###

The purpose of this data application is to teach data analysts, through interactive learning, how to interpret the results of the Shapiro-Wilks and the Anderson Darling Tests.

By randomly generating a normal dataset with x observations, the data analyst can know what "Normality" means for both tests, for example, a high p-value in the shapiro-wilks test means that the distribution looks to be normal. 

In addition, analysts can learn how increasing dataset sample size can alter the results of both tests for normality.


###How to get started###

Open the application by typing in the runApp("interpreting_normality") in the R command line, or by clicking the Run Application button on the top right of the screen (if you use R Studio). 

Once the application is launched, the user will see a randomly generated histogram and input options on the left side of the app. 

#Inputs that the user can change are:

1. Number of Observations in the sample dataset. This can be from 1 - 5000. 
2. Type of Distribution - The user can pick from the list c("gaussian", "cauchy", "exponential", "chi-squared", "weibull - 2 shape").
3. Number of Bins for the Histogram - The user can pick how many bins to include in a standard histogram. 

#Tabs that the user can access

There are three tabs included in the application.

1. Histogram Tab - The user can look at how the distribution would appear on a customizable histogram. 
2. The Shapiro Tab - The user can look at results from the shapiro-wilks test, and see how the results change as they tweak the distribution characteristics. 
3. The Anderson Darling Tab - The user can look at results from the anderson darling test, and see how the results change as they tweak the distribution characteristics. 

#Benefits

The next time that a data analyst needs to assess the normality of a given dataset, they can use this application to gather a baseline understanding of what normality looks like, from histograms and two popular normality tests. 

#For Questions and Contact
Ted Collins
edward.read.collins@gmail.com
