# Amazon_Vine_Analysis

## Overview of the Analysis
I was tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program, a service that allows manufactures and publishers to receive reviews for their products. With around 50 datasets, I chose to analyze digitial video games. As an avid videogamer myself, as well as knowledge that many game companies are shooting for digital releases over physical ones, I was curious just to what I was able to find. The link to where I was able to find these reviews is https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Video_Games_v1_00.tsv.gz .

## Results
In order to see if having paid a Vine review would make a difference in the percentage of 5 star revies, I decided to filter the results. First, I only wanted to count when there were 20 or more reviews. Afterwards, I wanted to make sure more than 50% of the total votes were deemed helpful. Then, from there, I split the results to whether they were part of the Vine program or not. This led to a total of 1685 total reviews. To my surprise though, after going through all of these filters, absolutely none of these reviews were made with Vine, they were all reviews not part of the Vine program. Undeterred though, I still wanted to see how many 5 star reviews there were. Here are my findings:
* As stated previously, there were a total of 1685 reviews.
* Out of those 1685 reviews, there were a total of 631 five star reviews
* Which means, 37.45% of all the reviews were five star reviews

## Summary
As there were no reviews made with the Vine program under these perameters, I am unable to conclude if there was a bias in the reviews in the Vine program. Perhaps next time, I will lower the standards from 20 total votes to 10, and see if I can find reviews made with the Vine program. Or perhaps, I would just look at video games in general, not just digital video games. Either way, hindsight is 20/20.
