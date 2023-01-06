# Amazon_Vine_Analysis
# OVERVIEW:
In this project we were given different Amazon datasets to work and find out whether or not the Amazon Vine Program would work for that specific product or not.The vine review program is an incentive model in which customers are gifted free stuff when they write good reviews.
For the ETL (extract, transform and load) I was able to use Pyspark on the US tools data set and PostgresSQL to load all the tables required.
Part of my findings were found by using Pandas.

#Resources:
1.US TOOL DATA SET
2.Google Colab (to run PySpark)
3.Jupyter Notebook
4.AWS S3 and RDS
5.PostgreSQL

#ANALYSIS AND RESULTS:

I worked with the last table called vine_table to perform the Vine program analysis to filter the best reviews, and see if there were significantly more 5-star reviews in the paid and incentivized (vine) program. The best reviews were those that were highly voted as helpful. Then, I filtered to see which of those were part of the vine program and which were not. Please refer to the Vine_Review_Analysis.ipynb

# RESULTS:
##Paid Vine Program:

*285 total reviews
*158 5-star reviews
*54% of vine reviews were 5-star

##Unpaid reviews:

*31545 total reviews
*14152 5-star reviews
*46% of unpaid reviews were 5-star

# Summary:
As we can see from our above analysis, that there is no significant difference between the Paid Vine program reviews and the unpaid reviews. We clearly see that the customers are not positively biased towards this program, as we are not achieveing maximum results by paying for the 5 star review program.

Further Analysis can be done by finding average mean of 5 star paid reviews and unpaid reviews and also, we can have a look at the other data sets and see whether the customers are biased or not.
