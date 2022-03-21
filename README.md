# Amazon_Vine_Analysis

## Overview of the project

I chose an Amazon dataset who reviews movie DVDs. I used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Results

In this particular dataset, there were 49 paid reviews and 151,400 non-paid reviews. From the paid reviews, only 9 were 5 stars. For the non-paid reviews, 78,061 were 5 stars. Those results mean that around 18% paid reviews were 5 stars against 52% for non-paid reviews. 

## Summary

We can not see a postive bias in the paid reviews. It's not because you paid that you will leave a better review on the DVD product. We could actually argue the contrary. People who leaves free reviews tend to give more 5 stars. It would have been interesting to perform a chi-square test to compare the two samples on a deeper level. If we did so, we would have a higher level of confidence that the samples are not the same when it comes to 5 star reviews. 
