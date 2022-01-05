### Summary

This repo contains an analysis and related files for Kickstarter campaign data with a focus on musical plays.

## Overview of Project

The client requested an analysis of musical theater Kickstarter campaigns from 2009 to 2017 in order to better determine the factors that contribute to a successfully funded project.

## Analysis and Challenges

This analysis began by filtering the data to restrict to musical plays. In order to isolate these data, we first had to break apart the catergory/subcategory data provided in the original dataset. By focusing only on this category we can see the breakdown of campaign results based on launch date.

![Theatre_Outcomes_vs_Launch](kickstarter-analysis/resources/theater_outcomes_vs_launch.png)

From this, we can determine that musical play campaigns show the highest rates of success in the early summer, and the lowest rates in the winter, as compared to the rate of failed campaigns.

After providing additional data based on country information, we moved into an analysis of outcomes based on goals. From this, again filtering for plays, we see that there are two bands of high (>60%) success: goals set under $5000, and goals set between $35000 and $45000

![Outcomes_vs_Goals](kickstarter-analysis/resources/outcomes_vs_goals.png)

> The data are clear: it is possible have a successful musical theater campaign on Kickstarter provided some criteria are met, mainly that the campaign launches in summer and that the goal is a reasonable one given the potential audience of the project.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Overall, theater Kickstarter campaigns are most successful when launching in May and June, at the start of summer and after the conclusion of the previous theater season (which runs September through May). It is adviseable to avoid launching theater campaigns in December, where the number of successful campaigns is nearly equal to the number of failed campaigns.

- What can you conclude about the Outcomes based on Goals?

While it may be tempting to assume that the higher the goal the less successful the campaign, this is not correct. The data show that while campaigns with goals under $5000 do show a high (>70%) rate of success, projects in the $35000-$45000 bracket also show high levels of successful funding.

The quantity of projects should also be noted, however, with 186 projects in the lowest (<$1000) bracket, and only 6 in the $35000-39999 bracket.

- What are some limitations of this dataset?

One benefit of backing a project on Kickstarter is the ability to receive perks from the campaigner; this analysis lacks data on this and such perks, or lack thereof, could influence the success rate of campaigns.

- What are some other possible tables and/or graphs that we could create?

This analysis focuses on the success/failure of theater campaigns on Kickstarter (and within that, musicals). Beyond this though, the primary dataset includes Kickstarters from a variety of categories. It would be useful to compare campaigns by category, to see if there are other categories that are generally more successful on the platform. Similarly, different catefories of campaigns may show greater levels of funding based on different launch months as compared with theater.


