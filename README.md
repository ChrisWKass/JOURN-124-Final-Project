# JOURN-124-Final-Project
Data analysis, potential questions and answers from findings, Potential story angle found within the data and relevant supporting data viz and sources

## Cleaning my data
* In workbench I looked through my data, specifically under the headings "school name" and "school type" for errors/anomolies and didnt find any.
* I then opened the data in google sheets and expanded it so that all the headings and data is visible and user-friendly.
* I included an additional row at the bottom labelled “Total.
* Although the figures appear to be numerical with currency value, they are actually captured in the table as hard coded text. In order to convert these figures into actual numbers the $ sign needs to be removed. 
* Once this is done, to return the $ sign reminding me that we are working with currency, the cells need to be formatted by selecting currency as USD
* I have now cleaned my data

## Analyzing my data
* Turning to the data, I was interested to see the % change form starting median salary to mid-career median salary
* In order to do this, I inserted an additional column to the table, calling it, % change from starting to mid-career median salary.
* The formular for this is =[(Mid Career Median Salary – Starting median salary)/ starting median salary]
* We now have a data set ready for analysis.

1. **ANALYSIS ONE**
* This involved sorting 
* I first looked at the starting median salary (hereinafter "SMS")
* I sorted the data from smallest to largest and for present purposes, was interested in the first 5 results - being the bottom 5 schools with the lowest SMS (as we have sorted to data from smallest to largest) 
* I then sorted the data from largest to smallest and again was interested in the first 5 results - being the top 5 schools with the highest SMS
* Now that I have analyzed the top and bottom five in the SMS column, I followed the same procedure for mid career median salary (Hereinafter "MCMS")
* The final thing I wanted to explore is the % change from SMS to MCMS as represented in the table below.
* To assist with visualizing the data I applied conditional formatting in the form of color scales. 
    * To this end, select the data initially analyzed  
    * Under conditional formatting option select color scales 
    * Apply the green, yellow and red scale (green = high, yellow = medium and red = low)
   
### I have conducted an analysis of the data through a means of sorting specific columns to generate specific results as represented by the following tables:

!['AnalysisOne','AnalysisOne'](/AnalysisOne.jpg)





