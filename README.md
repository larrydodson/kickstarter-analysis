# kickstarter-analysis
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
