# Customer Behavior Analysis: Nov–Dec

## Overview
This project analyzes online shopping session data to uncover behavioral patterns during the peak retail months of November and December. Using statistical techniques and probability modeling, it supports the marketing team in designing data-driven campaigns targeting the right customer segments.

## Significance
Holiday shopping drives a disproportionate share of annual e-commerce revenue. Understanding how returning and new customers behave — how long they browse, what they click, and whether they convert — gives marketing teams a measurable edge when planning campaigns for high-stakes periods.

## What Was Done

**Purchase Rate Analysis**
Calculated session-level purchase rates segmented by customer type (Returning vs. New) for November and December, revealing meaningful differences in conversion behavior between the two groups.

**Correlation Analysis**
Identified the strongest correlation in total time spent across page types (Administrative, Informational, ProductRelated) among returning customers, highlighting which browsing behaviors tend to co-occur.

**Probability Modeling**
Applied a binomial probability distribution to quantify the likelihood of achieving at least 100 sales out of 500 sessions for returning customers, given a 15% campaign-boosted purchase rate. A distribution chart was plotted to visualize expected outcomes across a range of sales scenarios.

## Skills Demonstrated
- Data wrangling and filtering with **pandas**
- Statistical correlation analysis with **scipy / numpy**
- Probability modeling using **binomial distributions**
- Data visualization with **matplotlib**
- Translating business questions into quantitative analyses

## Practical Value
The outputs directly inform campaign planning: the purchase rate tells you who converts, the correlation analysis tells you how browsers engage, and the probability model tells you what sales volumes are realistically achievable — before a dollar is spent on the campaign.
