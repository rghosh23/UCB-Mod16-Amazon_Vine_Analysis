# Amazon Vine Program Analysis

## Overview of the analysis

The purpose of the analysis is to use cloud service database and connecting it locally to PgAdmin to have interactive databases. Another purpose is to use Google colaboratory to perform data analysis with Pyspark to see if the Vine program helps promote more 5-star reviews or not.


## Results

The results are displayed below:

![Deliverable2](https://user-images.githubusercontent.com/102441140/182259070-0f91bab4-c10b-426c-b320-744d00c318cd.png)

*- How many Vine reviews and non-Vine reviews were there?*

There are 43 reviews from Vine users and 7750 reviews from non-vine users

*- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?*

Total 5 stars by Vine users is shown to be at 14 reviews. Total 5 stars from non-Vine users is shown to be at 4027 reviews.

*- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?*

Percentage of vine reviews with 5 stars is  approximately 32.6% Percentage of non-Vine reviews with 5 stars is aproximately 52.0%

## Summary

Since the percentage of vine reviews for 5 stars is significantly lower than the percentage of non-vine reviews for 5 stars, there is no positivity bias for reviews. If there were bias for the vine program, we can expect a huge jump in the vine reviews for 5 stars.

An additional analysis that would be helpful is to check if there are any duplicate users in the non-Vine program. People might be reviewing from multiple accounts an dthat might be swinging the % of 5-star reviews.
