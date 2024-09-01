# Call Centre Trends

### Dashboard Link : https://app.powerbi.com/groups/me/reports/720c15b6-d2e9-41f6-ac85-aeb71699fb99/e2c477f71d03bdd6d031?experience=power-bi

## Problem Statement

It’s omnipresent: telecom marketing. Better price here. Better service there. Best for small businesses here. Best for young urbanites there. But what do customers really want? Our client, a big telecom company needs to know. This email just arrived for you: 

###Create a dashboard in Power BI for Claire that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset. Get creative! 


Possible KPIs include (to get you started, but not limited to):

Overall customer satisfaction
Overall calls answered/abandoned
Calls by time
Average speed of answer
Agent’s performance quadrant -> average handle time (talk duration) vs calls answered

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view.
- Step 5 : Visual filters (Slicers) were added for four fields named "Agents", "Resolved Y/N" & "Date". 
- Step 6 : One card visuals was added to the canvas, one representing average of speed of answer in seconds & number of case resolved Yes/No
- Step 7 : Slicer used to segregate the data between parts e.g. Agents, resolved and date.

            Although, by default, while calculating average           
           

  (a) Average if satisfaction rating, average speed of answer.

  (b) Average calls answered.
  
  (c) Average Cases Resolved. 
  
  (d) Agent Statistics.
  
  
  

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;


### [1] Slicer Created to distribute Agents, Where every single individual has its own data where calls are answered, resolved, Avg satisfaction rating, Avg answered in seconds. 
   
thus, higher number of customers cases are resolved than not resolved.
           
### [2] Average Ratings

    a) Becky -     3.37/5
    b) Dan -       3.34/5
    c) Diana -     3.40/5
    d) Greg -      3.41/5
    e) Jim-        3.40/5
    f) Joe -       3.34/5
    g) Martha-     3.46/5
    h) Stewart -   3.43/5
   

  
  These ratings will change if different visual filters will be applied.  



  
  ### [3] Average Speed of Answering the call has come up to 67.50 in seconds.
  
     
Average woudnt change if different visual as its a card.

 ### [4] Some other insights
 
 ### Class
 
 Number of calls per month 

So all agents in below months has answered/Not Answered the call

January   -    1455 Answered **** 317 Not Answered
February  -    1298 Answered **** 318 not Answered
March     -    1301 Answered **** 311 not Answered

        thus, more customers have travel type 
