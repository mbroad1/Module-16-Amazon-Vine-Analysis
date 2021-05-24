# Module 16 Amazon Vine Analysis Challenge
---
**The goal of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program, a service that allows manufacturers and publishers to receive reviews for their products. Using PySpark and Pandas, it will be determined whether there is any bias towards favorable reviews from Vine members in the Amazon Grocery dataset.**
---

## Results:

**Paid Vine Reviews Summary**
![Paid DataFrame](https://github.com/mbroad1/Module-16-Amazon-Vine-Analysis/blob/main/Paid_DataFrame.png)
- There were a total of **62** Vine reviews in the Grocery dataset.
- Of those 62 Vine reviews, **20** had a 5-star rating.
- The percentage of 5-star rated reviews out of all the Vine reviews was **32.3%**.

**Unpaid Non-Vine Reviews Summary**
![Unpaid DataFrame](https://github.com/mbroad1/Module-16-Amazon-Vine-Analysis/blob/main/Unpaid_DataFrame.png)
- There were a total of **31237** Non-Vine reviews in the Grocery dataset.
- Of those 31237 Non-Vine reviews, **15937** had a 5-star rating.
- The percentage of 5-star rated reviews out of all the Non-Vine reviews was **51.0%**.
---
## Summary:
- Looking at the data, we see that out of all the Paid Vine reviews for the Grocery dataset, **32.3%** are rated as 5-stars.
- Likewise, out of all the Unpaid Non-Vine reviews for the Grocery dataset, **51.0%** are rated as 5-stars.
- Therefore, there is no positivity bias with the Paid Vine reviews because the percentage of 5-star reviews is significantly less than the percentage of 5-star reviews for the Unpaid Non-Vine reviews.
  - There are 18.7% less 5-star reviews in the Paid Vine reviews vs. the Unpaid Non-Vine reviews. 
