# Income-Qualification

my task was to identify the level of income qualification needed for families in Latin America. The problem scenario presented to me was that many social programs have a hard time ensuring that the right people are given enough aid, particularly when focusing on the poorest segment of the population who may not have the necessary income and expense records to prove qualification.

One popular method used in Latin America for income qualification verification is the Proxy Means Test (PMT) algorithm. However, accuracy remains a problem as the region’s population grows and poverty declines. The Inter-American Development Bank (IDB) believed that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.

To solve this problem, I first had to identify the output variable. In this case, it was the level of income qualification needed for the families. Next, I had to understand the type of data that was provided to me. It was a dataset of Costa Rican household characteristics. I then had to check for any biases in the dataset and ensure that all members of the house had the same poverty level. I also had to check if there was a house without a family head, and set the poverty level of the members and the head of the house within a family.

I then had to count how many null values existed in the columns and remove null value rows of the target variable. This was important to ensure that the dataset was clean and ready for analysis.

I then used a random forest classifier to predict the accuracy of the data. To further validate the accuracy, I used random forest with cross validation. Through this process, I was able to identify the level of income qualification needed for the families in Latin America and improve the performance of the PMT algorithm.


