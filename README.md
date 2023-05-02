# Statistical Analysis (A/B Testing) 
Project at Turing College | May 2021

## Sprint 2: Statistical Tests and Experiments
The goal is to analyse once run, online Udacity A/B test results! <br/>
Data is available [here](https://docs.google.com/spreadsheets/d/1Mu5u9GrybDdska-ljPXyBjTpdZIUev_6i7t4LRDfXM8/edit#gid=0)

##### Libraries Used
``` Numpy ```
``` Pandas ```
``` Matplolib ```
``` Seaborn ```
``` Statsmodels ```
``` Scipy ```

### Summary and Findings
*   Other metrics evaluated apart from the Click-through Rate includes *Overall Conversion Rate*, *Click Conversion Rate*, and *Enrollment Conversion Rate*
*   The p-values of the ztest and ttest results for the Click-through rates are very largely the same. However, the pvalues of the ztests and ttests for the other metrics differed greatly, although the Overall Conversion Rate had the same conclusion as in the ztest.
*   The conclusions for the conducted ztests are the same across all confidence levels for the click-through rate.
*   There is not a significant difference between the Experiment and Control groups, also as confirmed from the Confidence Intervals

## License
The MIT License - Copyright (c) 2021 - Oluwafunmilayo Somoye
