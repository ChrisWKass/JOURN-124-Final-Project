# JOURN-124-Final-Project
Data analysis with potential questions and answers from findings, Potential story angle found within the data and relevant supporting data viz and external + additional sources.

## Cleaning my data
* In workbench I looked through my data, specifically under the headings "school name" and "school type" for errors/anomolies and didnt find any.
* I then opened the data in google sheets and expanded it so that all the headings and data is visible and user-friendly.
* I included an additional row at the bottom labelled “Total".
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
   
### I have conducted an analysis of the data through a means of sorting specific columns. To this end, the specific results generated as shown from the tables below provide answers to the following potential questions:
      a) What 5 schools have the lowest SMS?
      b) What 5 schools have the highest SMS?
      c) What 5 schools have the lowest MCMS?
      d) What 5 schools have the highest MCMS?
      e) What 5 schools generate the lowest % change from SMS to MCMS?
      f) What 5 schools generate the highest % change from SMS to MCMS?

!['AnalysisOne','AnalysisOne'](/AnalysisOne.jpg)

2. **ANALYSIS TWO**
* This involved sorting and filtering.
* We are analyzing schools by name but we filtered specifically for school type
* This is basically the same as the previous process the only difference being, making use of filtering so that we can filter through school types.
* I went through and repeated the process for each school type (engineering, ivy league, state, liberal arts, party.
* NOTE: when analyzing the Ivy League category, there are only 8 schools, meaning that some schools will appear in both the bottom and the top categories.

### The following tables are relevant for the purposes of this analysis and provide answers to the following potential questions:
#### Within each respective school type what are the 5 school names 
      a) with the lowest SMS?
      b) with the highest SMS?
      c) with the lowest MCMS?
      d) with the highest MCMS?
      e) that generate the lowest % change from SMS to MCMS?
      d) that generate the highest % change from SMS to MCMS?

#### ENGINEERING

!['Engineering','Engineering'](/Engineering.jpg)

#### IVY LEAGUE

!['IvyLeague','IvyLeague'](/IvyLeague.jpg)

#### LIBERAL ARTS

!['LiberalArts','LiberalArts'](/LiberalArts.jpg)

#### PARTY

!['Party','Party'](/Party.jpg)

#### STATE

!['State','State'](/State.jpg)


3. **ANALYSIS THREE**
* Using pivot tables I wanted to analyze the various school types in terms of the averages of the SMS, MCMS and average % change from SMS to MCMS
* For analysis purposes, I took a hard copy of the data that was returned in my pivot table analysis which appears thus:

!['AnalysisThree','AnalysisThree'](/AnalysisThree.jpg)


### Possible Questions that are answered by above pivot table:
      a) What is the overall average SMS for each school type?
      b) what is the overall average MCMS for each school type?
      c) what is the overall average % change from SMS to MCMS for each school type? 


## Lets take a closer look at the data and other data visalization that will support a potential story pitch

!['Bottom5SMSpercentile','Bottom5SMSpercentile'](/Bottom5SMSpercentile.jpg)

https://infogram.com/bottom-5-schools-based-on-sms-percentile-analysis-pdf-1h8n6m30rxxoj4x

!['Bottom5MCMSpercentile','Bottom5MCMSpercentile'](/Bottom5MCMSpercentile.jpg)

https://infogram.com/bottom-5-schools-based-on-mcms-percentile-analysis-pdf-1ho16vogy9e5x4n?live

### What becomes apparent is that Black Hills State University fairs particularly badly - lets review the data gathered and analyzed thus far:
* Starting with the Analysis One, Black Hills State University (Hereinafter "BHSU") has he second lowest SMS, the lowest MCMS as well as the lowest % change from SMS to MCMS.
* Turning to the above bar chart representing the bottom 5 schools based on SMS percentile analysis, BHSU features right at the bottom in all instances
* In so far as the bar chart representing the bottom 5 schools based on MCMS percentile analysisis concerned, BHSU again does consistently badly and in all but two instances (where is comes very close second from last) scores lowest.

## STORY PITCH:
### WHY DOES BLACK HILLS STATE UNIVERSITY SCORE SO POORLY,CONSISTENTLY THROUGHOUT MY DATA ANALYSIS?  
#### I would begin by looking at factors that might contribute to why BHSU yields the the results in my findings, for example, 
   * What is the University's admssions policy?
   * How do the admitted applicants fair on their SAT scores?
   * What is the student to faculty ratio?
   * I would also look at the retention rate over time
   * Importantly, what are some of the common jobs by major from this university?
##### For the purposes of this submission, the above necessarily entails examples of additional sources that could be used for the purposes of the story pitch. 
 
 #### Based on my findings I would then write up a profile featuring BHSU and why its graduates are among the lowest paid throughout their career in the US

