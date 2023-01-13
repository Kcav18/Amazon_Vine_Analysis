# Amazon Vine Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide their products to Amazon Vine members, who are then required to publish a review. The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members. The dataset I analyzed was reviews for pet products. 

This analysis consists of two technical analysis deliverables and a written report:

**Deliverable 1: Perform ETL on Amazon Product Reviews** ([Click here to view Deliverable 1 Code](https://github.com/Kcav18/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)).

**Deliverable 2: Determine Bias of Vine Reviews** ([Click here to view Deliverable 2 Code](https://github.com/Kcav18/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)).

**Deliverable 3: A Written Report on the Analysis**

## Results 

- There are 170 total Vine reviews and 37,840 total non-Vine reviews.
- There are 65 Vine Reviews that had 5-stars and 20,612 non-Vine Reviews that had 5-stars.
- 38.24% of the Vine Reviews were 5-stars and 54.57% of the non-Vine reviews were 5-stars.

This data was obtained by using PySpark in a Google Colab notebook. The code used, along with the data frames, can be viewed by clicking this link: [Vine Review Analysis Code](https://github.com/Kcav18/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb).

## Summary

The results of the Amazon Vine Analysis indicates that there is **no bias** towards reviews that were written as part of the Vine Program. From the Pet Products Review analysis that I conducted, only 38.24% of Vine reviews were 5 stars! In contrast, 54.57% of the non-Vine reviews were 5-stars. This finding shocked me as I was fully anticipating that the Vine reviews would make up the largest portion of 5-star reviews.

An additional analysis that I would recommend is looking beyond just 5-star ratings. I would like to see an analysis of all ratings by Vine and non-Vine reviews. While analyzing the negative reviews, would we see any from Vine participants?? Are the majority of the vine ratings in the 3 or 4-star category? I think looking at the whole picture might provide a better insight into the Vine program.
