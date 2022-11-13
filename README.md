# Amazon_Vine_Analysis

# Overview of Analysis
The Purpose of this analysis was to determine if there was any bias to teh reviews based on if the Vine review was paid for or not. We are looking at the US Sports reviews for this data. Using Spark and Google Collab to transform our data we will be able to determine if there is bias. 

We Created the tables that would help with our Analysis

## Customers Table
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/Customers%20Table.png)


## Products Table
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/Products%20Table.png)


## Review ID Table
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/review_id_table.png)


## Vine Table
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/vine_table.png)


# Results

## Filtering the Data
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/vine_table.png)
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/greater_20.png)
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/greater_20_more50Percent.png)
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/Yes%20and%20No%20vine%20reviews.png)

After filtering the data so that is was only the Reviews with greater than 20 total votes and a greater than 50% on the helpfulness of the review, and look to see if there we duplicates we could then move on to the analysis and get our results. 

## Analysis of the Paid vs Non Paid Reviews
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/Analyis%20of%20vine%20reviews%20for%20bias.png)


* How many Vine reviews and non-Vine reviews were there?
334 Paid Reviews
61614 Unpaid Reviews
61948 Total 

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
139 Paid 5 Star
32665 Unpaid 5 Star

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
41% of Paid are 5 Star
53% of Non Paid are 5 Star


## Summary
It is difficult to say if there is bias or not. After having looked at the data I would say there is a bias towards the Vine Reviews that were paid for. When we look at the data of 5 Star reviews as a percentage of total reviews it might seem that this is showing that the paid review had no impact as the unpaid actually had a higher level than the paid. However we can see that when we bring in more data, like how many 3 star or greater the paid reviews recived as a percentage they are 93% 3 Star or Greater while the Unpaid is 79% 3 Star or greater. 

## Vine Reviews with 5 Stars
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/Analyis%20of%20vine%20reviews%20for%20bias.png)


## Vine Reviews with Greater than or Equal to 3 Stars
![](https://github.com/Andrew-E-Walters/Amazon_Vine_Analysis/blob/main/additional%20data.png)


