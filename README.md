# Amazon Vine Analysis
## Overview 
The purpose of this analysis was to utilize postgreSQL, pyspark, and AWS to conduct an analysis of Amazon Reviews. After selecting to do the analysis on the Electronics data sheet and cleaning it, the goal was to see if there was any bias affecting the quality of reviews when comparing them from people who are involved in the Amazon Vine Program, versus those who are not. 

## Results 
After filtering the available reviews to customers who had recieved at least 20 votes and had over 50% percent of those votes marked helpful, we calculated:
- The total number of reviews for all Vine and non-Vine customers.
- The number of 5 star reviews by Vine and non-Vine customers.
- Percentage of 5-star reviews by total reviews for all Vine and non-Vine customers.

Included below is a table showing these results.

<img src="images/vine_analysis"> 

## Summary 
