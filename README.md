# Amazon Vine Review
UW Data Bootcamp - Module 16

The project concentrates on Amazon vine review dataset (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz) and determines if there is a biased towards paid vs unpaid review and members who were part of the vine program.

We have used Google Colab Notebook to initialize the PySpark environment, read the above amazon dataset from S3 bucket, transformed the data, created different data frames and loaded those data frames to pgadmin i.e. PostgreSQL environment.



- ### **Results:** 
  
  - How many Vine reviews and non-Vine reviews were there?
  
  ![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Amazon_Vine_Analysis\vine_reviews.PNG)                                     ![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Amazon_Vine_Analysis\non_vine_reviews.PNG)
  
  
  
  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  
  ![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Amazon_Vine_Analysis\five_stars_review.PNG)
  
  
  
  
  
  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  
  ![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Amazon_Vine_Analysis\five_stars_review_percent.PNG)
  
  ### Summary:
  
  ​	From the analysis above there seems to be little biased comin from paid vs unpaid reviews. Although the percentage is only off by 10%. We need to further analyze the dataset on all the stars where vine program indicator = y/n to see where else the bias exists if there's any.
