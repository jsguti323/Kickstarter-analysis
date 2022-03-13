# Kickstarting with Excel

## Overview of Project

### We are analyzing the outcomes of various kick-starter campaigns in relation to their respective launch dates and funding goals.

## Analysis and Challenges

### We first looked at how the outcomes of the campaigns related to the month of the year they were launched. In this analysis, we were specifically concerned with kick-starter campaigns that fell under the parent category “theater”. Within said category, we sorted the data based on the month of the year the campaign was launched. Finally, we sorted the data based on the outcomes of each campaign, i.e., successful, failed, or canceled. Our dataset we pulled from included theater campaigns that took place from 2009-2017. Therefore, in the chart provided below, the amount of successful campaigns shown in, let’s say January, is actually the sum of successful campaigns from every January in that nine year span. We see in the chart that the month of May produced the most successful theater campaigns, while December produced the fewest. Also, the most total campaigns are launched from May to July.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99751636/158079567-78a380c2-4c1a-4ace-9d6f-e753ef931734.png)


### Next we looked at how the outcomes of the campaigns related to their funding goals. Here, we looked at campaigns under the subcategory “plays” and grouped them based on fundraising goal.  The first group represented goals of less than $1000, the last group represented goals of more than $5000, and all groups in between represented goals in roughly $5000 increments. Once the plays were grouped based on funding goal, we broke down each group into the outcome of the play. Finally, we took the percentage of successful, failed, and canceled plays with respect to the group they were in. The data shows the highest percent of successful plays had goals of less than $1000. As the goals increased to about $3000, the likelihood of success decreased. As goals went from $3000 to about $45000, the likelihood of success began to rise again; however, once goals exceeded $45000, the likelihood of success plummeted.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99751636/158079577-e38cfbca-8f28-474b-806f-c9f5a7b714ae.png)


### The most challenging part for me in this analysis was figuring out how to get the COUNTIFS algorithm in the “Outcomes Based on Goals” worksheet just right. I had to do some research on how exactly it worked, and I continuously found myself missing corresponding arguments. Also, it took me so long to figure out the “COUNTIF” and “COUNTIFS” were two different formulas.

## Results

### Quantititatively, the most successful outcomes of theater campaigns come in the month of May. Conversely, the fewest successful outcomes come in the month of December.

### The most successful campaigns are those with outcome goals under $1000.

### In the Outcome vs Launch Date chart, we are limiting our understanding of the data by only looking at the sheer frequency of campaigns and not at more descriptive statistics. Yes the month of May produced the most successful campaigns, but it also produced the most campaigns in total as well. By volume alone, it was likely May would have the most success, because conversely May also had the most failed campaigns as well. In the Outcomes vs Goals chart, our understanding of the overall data is limited because sample size of data decreases significantly as the funding goal increases. Therefore, it is hard for us to make any inferences about the data. Yes, 100% of the plays with funding goals from $45000-$49000 failed, but there was also only one play, so that could mean nothing.

### We could understand the data better if we included graphs or tables that included more descriptive statistics, especially for “Outcomes vs Launch Date”. Right now we are looking at sheer volume, and when we do so we end up with months like May, which features both the greatest amount of successful fundraisers and greatest amount of failed fundraisers. Given that information alone, it would be difficult to make an informed decision on whether or not to launch of kick-starter in May.

