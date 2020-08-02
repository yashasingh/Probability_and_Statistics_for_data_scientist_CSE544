# Probability_and_Statistics_for_data_scientist_CSE544
Contains the ipython notebook for project completed as part of the CSE544.

### Problem description: 
Analyze a COVID19 + X dataset, where COVID19 dataset can be anything you want such as COVID19 data from NY, from Spain, from a given county in NY, etc. The requirement is that the dataset should span at least one month.
1. Remove any outliers using the Tukey’s rule.
2. Provide basic visualization of the COVID19 and X datasets to explain the general trends in data.
3. Use your COVID19 dataset to predict the COVID19 fatality and #cases for the next one week. Use the following four prediction techniques: (i) AR(3), (ii) AR(5), (iii) EWMA with alpha = 0.5, and (iv) EWMA with alpha = 0.8.
4. Apply the Wald’s test, Z-test, and t-test (assume all are applicable) to check whether the mean of COVID19 deaths and #cases are different from the first week to the last week
5. K-S test and Permutation test
6. Report the Pearson correlation value for #deaths and your X dataset, and also for #cases and your X dataset over one month of data.
7. Use your X dataset to check if COVID19 had an impact on the X data.
8. Check if COVID19 data changed after some local event or rule was enforced, like lockdown or stay-at-home, etc. 
9. Use linear regression to find the impact of age, gender, underlying conditions, etc., on the severity of covid19 symptoms or duration.
10. Use Chi-square independence test to check if COVID19 impacted your X dataset in some way.
