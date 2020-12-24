# Kickstarting with Excel

## Overview of Project

We used multiple operations on the data of previous campaigns to determine the factors of success. These results were also visualized in order to give a better understanding of the findings.

### Purpose

In this project we are trying to determine which factors are essential for having a successful campaign.

## Analysis and Challenges

In my analysis I had to create new columns which contained data derived from the existing information. In order to summarize/visualize the required information I also created pivot tables. This displayed information in a clean and easy to visualize manner. There were a few challenges initially like applying the formula to the complete column, finding some specific function but I overcame them by asking my peers as well as doing simple search on google.

### Analysis of Outcomes Based on Launch Date

This analysis proved to be vital in choosing which months are the best for launch date. A pivot table was created having Date created in rows, outcomes in columns and values to be count of outcomes. Next this information was plotted in the form of trendlines. 

### Analysis of Outcomes Based on Goals

In this analysis we can observe a loose linear relationship between failed/Canceled campaigns with the amount of goal set. Also higher goal leads to less successful campaigns. In this analysis we needed logical reasoning in order to grab our data. So the 'CountIFS' function was used. Since the data we were acquiring needed at most 3 conditions to satisfy. After the information was extracted, it was then plotted in the form of trend-lines.

### Challenges and Difficulties Encountered

Possible challenge in these two analysis could have been the selection of wrong columns in the Countifs function and using the wrong features in the pivot table.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1) The spring and summer seasons are the best time for launching a campaign.

2) Success rate is high and failure rate is some what stable in the above stated seasons.

- What can you conclude about the Outcomes based on Goals?

The most suitable range of the goal should be between 0$ and 15000$. This is also where the failure percentage intersects the success percentage.

- What are some limitations of this dataset?

For some categories we do not have the data present. For example in the 'Theatre outcomes by launch date' analysis there no information for canceled campaigns in the months September- November. Also since we are only looking at a few factors there could be several other reasons for the campaigns to fail or succeed. Like for example if this analysis was done on the data for 2020, all campaigns would have most likely failed/canceled. Not because of the season or goals but because of social distancing and lock down factors.

- What are some other possible tables and/or graphs that we could create?

A histogram could have been created for Outcomes based on launch dates, Quarterly analysis could have also been done to get a better Idea of which yearly window should be chosen.
