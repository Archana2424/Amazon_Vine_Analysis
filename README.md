# Amazon_Vine_Analysis

Amazon_Vine_Analysis
Big Data

OVERVIEW-

In the Module we had SellBy project ,after completing that this is given anaysis project 
The objective of the project is to analyse the reviews written by participants in the Amazon Vine paid review program compared to reviews 
from non-paid reviewers. A random databset was selected from a collection of datasets based on a specific product classification.

For this project I choose one of the bookrelated andom review url from Amazon reviews.
he ETL (Extract, Transform and Load) process was conducted on the selected dataset. 
The data was extracted from the site the read into Google Colab. 
A Amazon Web Service RDS instance was created for data storage during this project.
 The data was then transformed and the 'clean' data was loaded into a PostgreSQL database for further analysis. 

RESULTS

After an analysis of the data, it was determined that there were only two reviews that were conducted by paid Amazon Vine members. Therefore, only the unpaid reviews were considered.

Note that there are 3,105,513 reviews in the dataset but only two of them are paid Vine reviews.-REFER TO SQL (TOTALREVIEWS.PNG )UPLOADED

Neither of the paid Vine reviews met the threshold of over 20 reviews.-REFER TO SQL (PAIDVINEREVIEW.PNG)-UPLOADED

Considering only the non-paid reviews, there were a total of 378,638 reviews with 227,734 being Five-Start reviews. 
The result is that 60.14% of all the non-paid reviews received a Five-Star rating.- REFER TO (PERCENTAGERESULT.PNG)


How many Vine reviews and non-Vine reviews were there?
Total of Vine reviews: 0


Total of Non-Vine reviews:403807


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Total of Vine Five-Star reviews: 0


Total of Non-Vine Five-Star reviews: 242889

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Total percentage of Vine Five-Star reviews: 0%


Total percentage of Non-Vine Five-Star reviews: 60.14 %





SUMMARY


1,Due to the lack of paid Vine member reviews, it was not possible to conduct a study to determine if there was bias between the paid and non-paid reviews.
 When additional paid Vine reviews are generated a study of this type would be benificial.

2.In addition, I would also recommend conducting an analysis on the verified purchases to determine if there is a bias between the reviewers
, who purchased the book compared to those who did not. Do they rate higher/lower/same as those who did not purchase the book.

RESOURCES


Data Source:"https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_02.tsv.gz"

Sofware: PostgreSQL, pgAdmin, Google Colab Notebook, AWS