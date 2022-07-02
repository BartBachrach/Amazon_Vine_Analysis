# Amazon Vine Program
The purpose of this analysis was to determine the helpfulness of the vine reviews posted to a series of outdoor products. The Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Reviews on Amazon increase product visibility to shoppers, which will in turn boost sales. We received datasets on over 2 million outdoor products on Amazon and analyzed them to determine if there was any bias in the Vine program. 

## Method
We received the original dataset and performed ETL to narrow down what we were looking for by dividing the data into four tables: a customers table, a products table, a review table, and a vine table. We focused on the vine table for this analysis. At that point we needed to find just the products with more than 20 reviews, and out of that set, how many were more than 50% helpful reviews (sometimes reviews seem to ramble on without giving any idea of what they’re on about). Then we divided that set into the paid and unpaid reviews to find out how many were five-star reviews.

# Results
The vine reviews analysis showed there was virtually no difference in the rate of five-star reviews among the paid and unpaid reviews, with almost identical rates of five-star product reviews among each group.
* There were 39,976 product reviews that were more than 50% helpful, which includes both paid and unpaid reviews.
* Out of that group, 107 were paid, and 39,869 were unpaid reviews
* Out of 107 paid reviews, 56 were five-star reviews, a rate of 52.3%
* Out of 39,869 unpaid reviews, 21,005 were five-star reviews, a rate of 52.7%

# Summary
According to our data and research, there does not appear to be any bias in the Vine Review Program, with nearly identical rates of five-star reviews. In fact, the unpaid non-vine reviewers gave slightly MORE five-star reviews than the Vine reviewers. One explanation could be that the paid reviewers possibly believe they should be more critical and analytical because they’re being paid to review the product, whereas regular shoppers will tend to want to be happier about their purchase. 

We could likely recreate these results by expanding the research to include reviews at the other four star-levels and comparing the number of four, three, two, and one star reviews between each group. 

