# **Kickstarting with Excel**
## **Overview of Project**
---
### -**Background:**
    With the help of Excel, the financial budgeting and discovering the hidden trends to help Mrs.Louise for her next play campaign, *Fever*, by observing and analyzing her provided data on several thousand crowdfunding projects. The provided data that was dealt was based on monetary values, dates, text and some numbers. To make some data readable, some data was converted into desired and readable format using “format” and a desired formula.
---
    Through filter and formulas, the percentage of funded campaign was determined, and it was seen that there were a lot of funded campaigns that were either canceled or failed even though The number of successful campaigns’ % funded was more. Since, Mrs Louise has 12000$ available for her next Play’s campaign, she wants to find out whether that would be a good decision or not. In order to do that, through filter and data analysis, it is concluded that her Great Britain’s Theatre/Plays campaigns showed the greatest number of successful outcomes. However, diving deeper into the analysis of the campaigns’ goal and pledged amounts, it was determined that there is the presence of ***outlier***!
---
### -**Purpose:** 
 In order to forecast the outcome of her next play *Fever*, we need to find the best and reasonable goal amount that is expected to be pledged at the right month of the year. 

### -**Brief of the Reports:** 
    Therefore, it was determined that the month-May has the most successful theatre plays; Dec-Month has the intercepting-point of the successful and failed number of percentage outcome of theatre plays. Canceled plays are almost constant through -out the year. Not only that, but it is also discovered that there are two reasonable goal amounts that Mrs.Louise should consider before going for next campaign, *Fever*! 
    ---
    Throughout the course of 8 years of plays, it is seen that number of failed percentage goal amount is greater that of successful. The Percentage canceled goal amount is the least even though it is constant throughout the years. The two intercepting-points for the number of percentage successful and failed outcomes are at the goal amount of $45000-$49999 and $15000-$19999, respectively.  This implies that any goal amount lesser or equal to the two intercepting points will be a prudential decision for Mrs Louise for her next campaign! Therefore, her 12000$ for her next campaign is going to be a wise decision.
---
## **Analysis and Challenges**

### **Analysis of Outcomes Based on Launch Date**
    To find the theater outcomes based on Launch date (![This is a screenshot](C:\Users\Zohair K ^_^\Desktop\Excel module1\Class Folder\resources\Launchdatessh.PNG)), the formulated data was imported into the new sheet,Theater Outcomes by Launch Date, into pivot table for analysis (![This is a screenshot](C:\Users\Zohair K ^_^\Desktop\Excel module1\Class Folder\resources\scrshtTheatreoutcomesvslaunchdates.PNG)). After seeing the greater number of successful outcomes in all the campaigns through filters, the theater outcomes showed the most results in the month of May during the period of 8 years starting from 2009 to 2017.
---
### **Analysis of Outcomes Based on Goals**
    Similar method was applied to determine the number of outcomes [Successful, Failed and Canceled] percentages. The only difference was application of the “COUNTIFS()” formula in column B, C &D . The formula was used to find the criteria, the # of each outcomess in the respective columns in the Kickstarter-Sheet (![InkedSCRSHtPlaysvsgoals_LI screenshot](C:\Users\Zohair K ^_^\Desktop\Excel module1\Class Folder\resources\InkedSCRSHtPlaysvsgoals_LI.jpg). After finding the percentages, the line with markers graph was plotted to determine the reasonable goal amount for the upcoming play. 
    ---
### **Challenges and Difficulties Encountered**
    Challenges or difficulties that were faced during the analysis was on the formulation of different data. For example, some magic undesired numbers were resulting multiple times for the used formula. After trial and error and filtering the data, the numbers were resulted in the expected range. Second, there was some difficulty in editing the labels of horizontal axis, especially for the graph (![Screenshot of scrshttotalcategvslaunchdateoutcome](C:\Users\Zohair K ^_^\Desktop\Excel module1\Class Folder\resources\scrshttotalcategvslaunchdateoutcome.PNG). 
    ---
## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    Month-May has the most successful theatre plays; December is the month that shows the number of successful and failed outcomes for the theater. Canceled plays are almost constant through-out the year !([Theatre outcomes vs Launched years screenshot](C:\Users\Zohair K ^_^\Desktop\Excel module1\Class Folder\resources\Theatre outcomes vs Launched years.png)).
    --
- What can you conclude about the Outcomes based on Goals?
    It is seen that the number of failed outcomes percentages for the goal amount is greater than that of successful one throughout the period of years (2009-2017). The number of canceled percentage outcome for the goal amount is the least but almost constant throughout the 8 years. There are two intercepting points for the number of successful % outcomes and the number of failed percentage outcomes for their respective goal amounts and that are at $ 45000-$49999 and $15000-$19999, respectively. This implies that any goal amount lesser or equal to the two intercepting points will be a prudential decision for Mrs. Louise. (![Outcomes_vs_Goals scrnsht](C:\Users\Zohair K ^_^\Desktop\Excel module1\Class Folder\resources\Outcomes_vs_Goals.png).
    ---
- What are some limitations of this dataset?
    From my recent excel-experience, I agree to the point that excel and any dataset that it carries are not usually in a good alignment with one another. One must go through a lot of formulas to crosscheck whether our desired value is the same as resulted, especially in the case when excel contains a lot of data for our analyses. Hence, the chances of error and/or its possibilities increases while identifying and removing those errors decreases. In addition to that, it can become time-consuming when cross-checking is done. [Link:  https://www.knime.com/blog/ten-common-issues-when-using-excel-for-data-operations]. 
    ---
- What are some other possible tables and/or graphs that we could create?
    No other possible charts or tables are useful enough for the dealing and analyses of the dataset of Mrs. Louise to uncover the trends of her future campaigns by looking in the results of the past and present. The currently are the best possible one to deal the data
