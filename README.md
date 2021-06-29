# kickstarter-analysis
Documents created for Louise's play FEVER
## An Analysis of Kickstarter Campaigns for my client Louise
Initially, I added five new data columns
* Percentage Funded
* Average Donation
* Split Category/Subcategory into
* * Parent Category
* * Subcategory
* Converted the two Unix timestamp columns to two standard date format
---
I created a pivot table that compaired outcomes via the parent category. I added country as a filter
I created two charts:  one that included all countries; another that displayed the outcomes for the United States only.
The charts show that US outcomes are similar to all countries outcomes.  
---
I created a separate pivot table that compaired outcomes to subcategory with country and parent category as filters.  
I did not gain any additional insights with this information.  
---
Created a new pivot table comparing outcomes to launch date with parent category as a filter. 
Graphed the data and observed the following:  
* Campaigns launched in May saw the greatest success.
* Campaigns launched in January, June, July, and October had similar failure numbers.  
* The line depticting canceled campaigns was close to linear or flat.  
I then filtered the pivot table by the parent category of Theater. 
Graphed this data and made the following observations:
* The most successful theater campaigns launched in May.  
* Theater campaigns that launched in May, July, and October had the highest failure.  
* Like the all parent campaigns data, canceled campaigns was somewhat linear.  
---
My client was inspired by five plays she saw at the Edinburgh Festival Fringe and wanted information as to how they were funded.  
Created a separate sheet titled "Edinburgh Research."  
* All five were successful
* The average goal was around $2000.00, average pledge amount was $2300.00, average donation was $40 from an average of 62 backers.  
---
To aid my client, I filtered the Kickstarter data, creating two separate worksheets
* Successful US Kickstarters
* Failed US kickstarters
From these spreadsheets, I ran a statistical analysis finding mean, median, standard devision, upper and lower quartile, and IQR.  
---
Louise mentioned that she hopes to produce a musical in Great Britain.  I filtered the data by Great Britain and musicals.  I then selected pledged and goal categories and performed a statistical analysis.  Data from the statistical analysis was ploted and presented to Louise.  From this plot, the mean campaign goal was around $4,000. This is outside the outliers range for the amount pledged.  I recommended that Louise try to get her play produced for less than $4,000.  Additionally, half of the campaign goals were less than $2,000, which is slightly larger than the 3rd quartile for pledged amounts.  
---
I began working on the challenge.  
---
 # Crowdfunding Analysis for Kickstarting FEVER

## Overview and Purpose
      Our team met with Louise on June 10, 2021 to discuss her situation.  Louise is a playwriter, fairly new to the industry.  She is interested in starting a crowdfunding campaign to fund a play she wrote titled FEVER.  Her estimated budget is in excess of $10,000.  Louise would like to hire us to analyze data on crowdfunding campaigns.  I advised her that we already had an extensive database of crowdfunding information.  We would be able to provide her with a myriad of information in the form of tables, charts and recommendations.  We would present this information in easy to understand form thereby allowing her to deveop a strategy to achieve success.  

## Analysis and Challenges
   We separated columns with combined data and filtered different columns to aid in developing trends and recommendations.  Several smaller tables were created incorporating filters.  From this information, we developed charts to present to Louise.  We worked on using advanced Excel functions to aid in our analysis.  
   Initially, we created a table to compare outcomes to the parent category and added a filter for country.  Out team created two charts:  one for all countries and another for the United States only.  The charts were very similar and showed that US outcomes match outcomes for all countries.  Theater is the largest campaign category with the most successful and failed campaigns.  
   We then created a separate table that compaired outcomes to subcategory with country and parent category as filters.  We filtered the data by subcategoy for plays, United States, and all countries.  Again, both the United States and all countries charts showed similar results.  Plays is the largest subcategory with the most successful and failed plays.  
eated a new pivot table comparing outcomes to launch date with parent category as a filter. 
!https://github.com/LynMcJo06/Kickstarter-analysis/main/OutbyLaunchDt.png


### Analysis of Outcomes Based on Launch Date
The graphed data showed the following:  
 * Campaigns launched in May saw the greatest success.
 * Campaigns launched in January, June, July, and October had similar failure numbers.  
 * The line depticting canceled campaigns was close to linear or flat.  
### Analysis of Outcomes Based on Goals
The graphed data indicated:  
 * The most successful campaigns obtain 80% of their goal.
 * The least successful and most likely to fail are the campaigns that have a high goal and do not obtain funding.  
 * The closer a campaign is to reaching its goal, the more likely it will be successful.  

### Challenges and Difficulties Encountered
  Challenges encountered included time management and understanding what the client was looking for.  Additionally, we had some new staff members and it took they some time to fully understand Excel functions.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  * The most successful theater campaigns are launched in May.  
  * It is rare that theater productions get canceled.  
  * Most failed theater campaigns occur in May, July, and October.  

- What can you conclude about the Outcomes based on Goals?
  * The most successful campaigns achieve 80% of their funding goal.
  * The most successful campaigns usually seek funding less than $10,000.    

- What are some limitations of this dataset?
-   Limitations may include:  
      * the study sample may not be representative of today's market;
      * the study did not include social demographics;   
      * there are more recent data available; 
      * campaign management was not factored in; 
      * data is lacking actual campaign costs.  

- What are some other possible tables and/or graphs that we could create?
  * a table and graph looking at campaign duration versus outcomes
  * a graph of pledged amount versus outcomes
  * campaign duration versus Parent Category or Subcategory

