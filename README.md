# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of our analysis is to ascertain how each campaign performed or fared in relation to the following parameters;
1. _Launch Date (month of launch)_
2. _Funding Goal_
## Analysis and Challenges

### _Analysis of Outcomes Based on Launch Date_ 
This analysis was carried out using "Theater" as a representative sample size from the "Parent Category" dataset / population. Then, using a pivot table, we aggregated the respective outcomes (_success, failure, canceled_) of each "theater" dataset against their launch months. The output from the pivot table was then used to create a line graph for us to have a visual representation of how "Theater" campaign performed during each month between the years 2009 and 2017
<img src ="resources\Theater_Outcomes_vs_Launch.png">    

### _Analysis of Outcomes Based on Goals_ 
This analysis was carried using "Plays" as a representative sample size from the "Subcategory" dataset / population. Then, we used simple excel calaculation (**COUNTIFS**) to aggregate the numbers / counts of successful, failed and canceled plays for different bands of funding goals. The output of this calculation was then used to create a line graph for us to visualize the percentage of successful, failed and canceled "Plays" based on funding goals
<img src="resources\Outcomes_vs_Goals.png">  

### Challenges and Difficulties Encountered
1. For the "_Theater Outcome by Launch Date_" analysis, the major challenge that I encountered was how to determine the logic to automatically retrieve the "_Year_" of launch from the "_Date Created Conversion_" column for use in my pivot table. This challenge was surmounted using the **Year( )** function available on excel to retrieve the data of interest from the relvant column of the kickstarter worksheet


2. For the "Outcomes Based on Goals" analysis, the key challenge that I encountered was how to determine a logic to automatically count and aggregate different outcomes (_success, failed, canceled_) for different "_Funding Goals_" bands for the "_Plays_" subcategory. This challenge was surmounted using the **COUNTIFS** excel function to process and aggregate the data of interest from the relevant columns in the kickstarter worksheet.  
### Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Based on this anaylsis, we observed that theaters launched in summer months (_specifically between May to August_) were the most successful. We could conclude that these months are the peak period for theaters

2. We could also conclude that the last 3 months of the year are not the appropriate period for theater launches. A progressive month-on-month decline in the number of successful theater launches was observed in these last 3 months  

- What can you conclude about the Outcomes based on Goals?
1. Based on our analysis, we could conclude that except for the unusual spike that we observed in the "_Funding Goal_" band of between $40,000 - $44,999, there is an inverse relationship between "_Funding Goal_" and percentage of success of "Plays" up to the band of $39,999. We observed a progressive decline in the percentage of success as "_Funding Goal_" increased up to the band of $39,999.

- What are some limitations of this dataset?

The following are some of the observed limitation of the dataset used for our analysis;
1. The analysis of "_Outcomes Based on Launch Date_" and "_Outcomes Based on Goals_" were carried out using "_Theater" and "Plays_" sample size datasets as against using the entire population of datasets available in the "_Parent Category_" & "_Subcategory_" for the 2 analysis respectively. We are not certain that the conclusions that we have drawn above would be thesame if the entire population datasets were analyzed.

2. The analysis that was carried out on the "Outcomes Based on Goal" dataset did not take "_Live_" outcomes or dataset into consideration. Perhaps, the percentage of success recorded for the different "_Funding Goal_" bands would not have been as high as currently observed if "_Live_" dataset was taken into consideration.

3. There is no consistency in the date intervals or duration between the launch and deadline dates for all the campaigns across board. While the intervals for some spanned a few months, others lasted for 2 weeks or less. This may have impacted the level of success achieved by some of the campaigns 

- What are some other possible tables and/or graphs that we could create?

The following are the posible charts / graphs that we could have alternatively created for our analysis;
1. Stacked Line Chart
2. Stacked Line with Markers 
3. Clustered Column Chart
4. Stacked Column Chart
5. Clustered Bar Chart
6. Stacked Bar Chart
7. Regression Analysis table and chart