# Amazon_Vine_Analysis-

## Overview of the project: 

- For this project we collected reviews data regarding **pet products** games and used **Pyspark** to conduct the ETL process of *extracting, transforming and connecting*  the data to a database that we created via the *AWS server*. Once this process was complete an analysis was carried out to determine if there was a **favorable review bias** from the Vine members in our data set.

##  Project Deliverables: 

1. Deliverable 1: **Perform ETL on Amazon Product Reviews**
2. Deliverable 2: **Determine Bias of Vine Reviews**

## Results

<img width="663" alt="Screen Shot 2021-08-09 at 12 09 46 AM" src="https://user-images.githubusercontent.com/82069038/128659625-ce2350da-7b2f-4405-8293-9541aba756c8.png">

	
**How many Vine reviews and non-Vine reviews were there?**	

- There were 170 *Vine reviews* and 37,840 *non-Vine reviews*. 
  
**How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**	

- 65 of the Vine reviews were 5 star.
- 20,612 of the non-Vine reviews were 5 star.

**What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**	
<img width="509" alt="Screen Shot 2021-08-09 at 12 11 15 AM" src="https://user-images.githubusercontent.com/82069038/128659719-1eba51da-1a8f-49e1-b86d-5f860be0f0af.png">
<img width="251" alt="Screen Shot 2021-08-09 at 12 11 21 AM" src="https://user-images.githubusercontent.com/82069038/128659721-4fa9a04b-dad2-4eb2-8f97-e9edee475334.png">
<img width="531" alt="Screen Shot 2021-08-09 at 12 11 27 AM" src="https://user-images.githubusercontent.com/82069038/128659722-290dd16b-223a-4477-b115-6c8a043e2f41.png">
<img width="237" alt="Screen Shot 2021-08-09 at 12 11 32 AM" src="https://user-images.githubusercontent.com/82069038/128659723-e5637662-23d0-4a5e-889f-0ebaaf2ffdfe.png">
- 48% of the 5 star reviews were Vine.
- 54% of the 5 star reviews were non-Vine.

## Summary

There are only **48%** of *5 star* Vine reviews in the dataset as opposed to **54%** of *5 star* non-Vine reviews which suggests a lack of bias. There is most liklely a lack of proportion in the data set since 170 of the 37,840 reviews were from Vine users, which could result in a lack representation in the analysis. 

## Resources

**Data Source:** https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

**Software:** Jupyter Notebook, Python, AWS, Google-Colab, PySpark
