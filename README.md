# Kickstarting with Excel
**Module 1 Challenge Submission, Written Analysis**

## Overview of Project

Louise has had success in fundraising for her project "Fever". She has now made an additional request for information to learn more about how other same parent and subcategory campaigns performed on Kickstarter. Specifically, the request is for more in-depth information on project launch dates and funding goals. 

## Purpose

Louise wants to know more on how representative campaigns performed in relation to their launch dates and funding goals. Using the same data set as was available from the initial phase of the project, we will continue analysis with focus on these two areas of interest. This additional analysis will add new insights on related Kickstarter crowdfunding campaigns for theater and plays. An increased level of insights would enable Louise to ensure a successful current production for Fever, and also with planning for future new campaign projects. 


## Analysis and Challenges



### Analysis of Outcomes Based on Launch Date

Please see Chart-A, "Theater Outcomes Based on Launch Date"

  The line chart shows the relationship between the Number (or quantity) of Outcomes for the Theater Category (successful, failed or canceled), and the month of a campaign’s launch. The category refers to the resulting project’s status, of successful and meeting it’s funding goal, or if the campaign failed or was canceled, and specifically for theater projects.


Chart-A: 
  ![Theater_Outcomes_vs_Launch.PNG](https://github.com/larrydodson/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.PNG?raw=true)

Observations

- In the generation of this chart the year and month have been derived from a date code within the source data, and from a range of calendar years from 2009 through 2017. And, the number of Outcome occurances have been grouped into each month for each year of the eight year duration. The line chart indicates the number of occurances per month over the entire duration. 
- Of interest is the comparison of occurances for successful versus failed and versus canceled campaigns. This line chart visualization is an effective tool to show the pattern of relationships between the different occurances and the month of launch. 
- It can be determined from the chart which are the most optimal months to launch a campaign, and what are the months to possibly to avoid for a launch. 
- Interpreting the chart, it is seen that the majority of campaigns that were launched in May and June had a higher numbers of success than other months.



### Analysis of Outcomes Based on Goals

Please see Chart-B, "Outcomes Based on Goal" 

   This line chart shows the relationship between the quantity and category of outcomes versus the size of the funding goal, and specifically for theater/plays campaigns.

Chart-B: 
  ![Outcomes_vs_Goals.PNG](https://github.com/larrydodson/kickstarter-analysis/blob/master/Outcomes_vs_Goals.PNG?raw=true)

Observations
-	By using this method, the line chart becomes an  tool to see the relationship of outcomes compared to the level of funding and for success and failure. 
- The chart implies that there are the ranges of Goal targets that may lead to successful Campaigns, when compared to the other ranges. 
- In building this chart categories of funding ranges were created, as shown, and then relationship of the number of occurrences of success and failure were counted for each of the funding.  And example of the formula is:  *=COUNTIFS(Kickstarter!$D:$D,">=10000",Kickstarter!$F:$F,"successful",Kickstarter!$D:$D,"<=14999",Kickstarter!T:T,"plays")* 


### Challenges and Difficulties Encountered
- When learning a new function and equation such as the COUNTIFS function for the generation of the Outcomes Based on Goals chart, there is effort to confirm that it is being used correctly. This took some time and correction of a couple of errors on the author's part. 
- A challenge sometimes is to combine good technical skill when generating the excel tables and charts with effective communications in writing the report, they should go hand-in-hand as equal effect components. A good presentation is based on solid analysis work, but also the communication of the work is equally important. This project is a good example. 


## Results
### **Conclusions and Recommendations.**

**Theater Outcomes based on Launch Date, and when to plan.**
1. The majority of campaigns that were launched in May and June had higher numbers of success than other months. 
2. Avoid launching a new campaign during the months of March and at the end of a year in November and December. 
3. The relationship between successful and failed campaigns track with each other for respective highs and low occurrences through a twelve-month cycle, however the highest peak and gap between the two is in May and June, and supports the recommendation to have a launch in May.
4. If it is possible, plan for a May launch for a campaign, with project preparation during the months prior to May. 

**Theater/Plays Outcomes based on Goals** 

From the chart we see that the funding Goal ranges that had occurances with the most success are: 
1. "Less Than 1000"
2. "25000 to 24999"
3. "40000 to 44999" 


**Limitations of this dataset** 
- In considering the Launch Date Chart, there can be many reasons for success and failure that we do not have visibility and insufficient data.  as examples, the experience of the project’s team, costs of production, acts of 3rd parties outside of the project team’s control, and more. 
-	In consideration of the Outcomes Based on Goal chart, a valuable part of the data is the quantity of occurrence for each of the funding Goal ranges. There are much higher numbers of campaigns at the lower ranges compared to the higher ranges, but this is a missing component in this chart. The lower number of campaigns in the higher goal ranges should not have the same weight of impact as the lower goal ranges. 
-	Currency: there are various currencies in the source data, that are not converted to one as a standard, and this should be done. The charts have used U.S. $, but actual currencies include these: US$, Canadian CAD, British Pounds, Australian AUD, Euros, Norwegian Krone NOK, Swedish Krona SEK, Danish Krone DKK, Mexican Peso MXN
-	Likely valuable data would come from follow-up on success of theater/plays post-production, how did they progress to completion, did they stay within production budget (funding Goal), how was the box-office take (if there was one), and other related information that would strengthen the overall source data with more variables that could be verified with actual results. 


**Recommendations for other possible tables and/or graphs**  
- Another version of the Outcomes Based on Goal chart, to include the number of occurrences as a sorted data column, that would then indicate the weight of each of the Goal ranges. 
- A chart to sort the campaigns by country and the currency, then to normalize to a standard currency. There are a higher occurance of canpaigns in the U.S. and Great Britain, but woudl be a good reference to see them  by country to determine there is any meaningful impact. 


.
.end 



---
.
---

...=========================================================================... 

# kickstarter-analysis
## The following Section is the submitted Module-1 classwork analysis, pre- Module 1 Challenge.


UTMCC DataViz Module-1 classwork, an analysis on Kickstarter Campaign data for Louise.

## Overview of Project - Description and Purpose
  Louise has an upcoming theater/play project named "Fever" and is considering using the crowdfunding service "Kickstarter" to fund the project. Her estimate of the cost to produce the play is $12,000. She has requested a review of other similar past Kickstarter projects to help her in planning a successful Kickstarter Campaign. 

### Purpose
  An analysis of available data from similar past projects on Kickstarter will aid Louise in planning her Campaign for "Fever". The analysis will provide information on over 4,000 crowdfunding projects in order to uncover any hidden trends, and support decision making to help ensure success for funding.
  This report is a summary of the findings from the analysis, with comments and recommendations.

## Analysis and Challenges

### Analysis of Outcomes Based on Goals 

From the data, we observe that there are over 4,000 Kickstarter Campaigns of various categories, including 3,038 of them in the U.S. The information contains the amount of funding required as “Goals”, the amount committed to by a backer as “Pledged”, the duration of the Campaign with start and end dates, country, currency, and information on the type of Campaign as Category/Subcategory. With this information we have run analysis with the goal to aid in planning successful funding.

See the charts below: 
- Chart-1.	 “Category Outcomes, Campaigns in the U.S. and Great Britain”
-	Chart-2.  “Parent Category Outcomes, Campaigns in the U.S.”

  Of all Categories, we see that Theater/Play projects are the majority and with a good success rate of meeting funding goals. The target project for Louise is a theater/play, therefore the focus is on similar projects and scope.  Louise has expressed interest in Theater projects for the U.S. and Great Britain (GB), and have given these locations priority. There were 525 Theater projects within the U.S., and 650 successful Theater/Play Campaigns in the U.S. and GB combined. 


Chart-1
 ![General Category Outcomes chart.png](https://github.com/larrydodson/kickstarter-analysis/blob/master/General%20Category%20Outcomes%20chart.png?raw=true)
 
 
 Chart-2
 ![Parent Category Outcomes barchart.png](https://github.com/larrydodson/kickstarter-analysis/blob/master/Parent%20Category%20Outcomes%20barchart.png)
 

 
 Observation
 
   Projects for Theater and Theater/Plays are popular and successful Campaign Categories in Kickstarter, when compared to all Campaign Categories, with Music projects and Film/video coming in next for number of projects. 

With continued focus on Theater/Plays in the U.S., please see Chart-3 below, “Descriptive Statistics, US Kickstarter Theater/Play Campaigns”, and the following observations.:

 Chart-3
 ![Descrip Statistics Success Failed.PNG](https://github.com/larrydodson/kickstarter-analysis/blob/master/Descrip%20Statistics%20Success%20Failed.PNG?raw=true)

 
 Observations 
-	Successful Kickstarter campaigns have a Goal mean of $5,049, with a mean of $3,000. And are much lower funding Goals than for Failed Kickstarter campaigns, at about one half the amount.
-	Louise, at $12,000 for Fever, is planning for more than twice the average successful Kickstarter goal. In order to support a higher chance of funding success a recommendation will be for the Goal amount to be adjusted lower. 
-	The mean (average), and median Pledged amounts for the Failed campaigns are much lower than the Successful Pledged amounts. 
-	The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.
-	The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.
-	For Successful Campaigns, standard deviations are about twice the IQR, for Failed Campaigns standard deviations are about three times the IQR. 

.

**Great Britain**

With the request to additionally look at specific projects in Great Britain, please see the following charts:
-	Chart-4: “Subcategory Statistics for Theater/Play Campaigns in Great Britain” 
-	Chart-5: “Research on Select Plays at the Edinburgh Fringe”
-	Chart-6: “Research on Select Plays at the Edinburgh Fringe, Sum of Average Donation and number of Backers”

   *As reference, all funding amounts are in British Pounds, GBP (£).*

 Chart-4
 ![Subcategory Stats.png](https://github.com/larrydodson/kickstarter-analysis/blob/master/Subcategory%20Stats.png?raw=true)
 
 Chart-5 *(please note chart correction: amounts are in GBP £ not U.S. $)*
 ![Edinburg Research.PNG](https://github.com/larrydodson/kickstarter-analysis/blob/master/Edinburg%20Research.PNG?raw=true)
 
 Chart-6
 ![Edinburg Donations and Backers.PNG](https://github.com/larrydodson/kickstarter-analysis/blob/master/Edinburg%20Donations%20and%20Backers.PNG?raw=true)
 
 Observations
-	There is a similar quantity of Campaigns for plays in Great Britain as in the U.S., with the "Plays" subcategory as the most successful, and with a higher chance for funding success. 
-	Compared with Campaigns in the U.S., these Campaigns have a lower target funding Goal, and are correspondingly lower for the number of backers and average donation amounts. 
-	To a specific question from Louise, Yes, these specific five plays were successfully funded on Kickstarter.  Each of these exceeded their Goal amounts, with a range of Pledged amounts from £33 to £53.


**Foresight**

  Separately from the Edinburgh festival, and with a special interest from Louise, included is a targeted Theater Play named “Foresight”. It had a successful campaign Goal of £2,000 with a Pledged amount of £2,004, with 17 backers (Pledgers). The Campaign was active from April 22 through May 16, just less than one month.  The average Donation was at £117.88. 


**Musicals**

  Also requested was a review of Musicals Campaigns, ones with estimated budgets of approx £4,000.
Please see Chart-7 below: “GB Musicals – Kickstarter” 

 Chart-7
 ![GB Musicals Kickstarter.PNG](https://github.com/larrydodson/kickstarter-analysis/blob/master/GB%20Musicals%20Kickstarter.PNG?raw=true)
 
 
 Observations
 
The mean campaign goal is around £4,000 for each project, with the median at £2,000. Also, about half of the campaign goals are less than £2,000, which is just over the 3rd quartile for amounts pledged.


### Analysis of Outcomes Based on Launch Date
See the Chart-8 below: “Outcomes Based on Launch Date”

 Chart-8
![Outcomes based on Launch Date linechart.png](https://github.com/larrydodson/kickstarter-analysis/blob/master/Outcomes%20based%20on%20Launch%20Date%20linechart.png?raw=true)

Observations
-	Interpretation from the chart indicates that there is a repeated annual cycle pattern with the best time of year to launch a new campaign for Theater/Play projects when they are started in May/June. 
-	In contrast, the end of a year around December is not the best time to launch.

## Results and Recommendations
1.	Campaigns for Theater and Theater/Plays are popular and successful Categories in Kickstarter. 
2.	Theater/Plays have a good chance of success when the funding Goal is at a target amount of $5,000.
3.	Recommend lowering the Goal funding target amount for "Fever" to $5,000, or less if possible. 
4.	Recommend starting the Campaign Launch in May or June. The optimal project start window is from May through June, on a calendar year cycle. 
5.	Recommend to not Launch around the time of December. 

### Other follow-up information and analysis that may be helpful.
For Successful Campaigns.
-	A follow up with Successful Campaigns, to determine if the project exceeded or stayed within their Campaign Goal amount. And if exceeded, how the project made up for the shortfall.

For Failed Campaigns. 
-	To consider whether a Failed Campaign was resubmitted as a new project, with a new changed Goal, and their success or failure after the resubmission. 

end. 
