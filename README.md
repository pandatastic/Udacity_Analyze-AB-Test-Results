# Udacity_Analyze-AB-Test-Results
Udacity Business Analyst Nanodegree, part I, final project

For this project, I analyzed the results of an AB test run by an e-commerce site, to see if their new landing page had any significant impact on conversion ratio. 

This project consist of three parts, all of them are used to compute and analyze the result of the A/B test.

## Part I - Probablity
The conversion ratio of the pages are compared to the overall conversion ratio.

## Part II - A/B Test
Hypothesis testing, where the old landing page is better unless there is significant proof that the new page is better.
P-value was calculated in order to determine the hypothesis.

## Part II - Regression
Logistic regression was performed.
Added extra independent variable of _country_ to see if this affected the conversion ratio.

## Conclusion
<li>Fail to reject null hypothesis: old landing page is *not overpermormed* by the new landing page.</li>
<li>The user's geoip country did not have an impact on conversion ratio.</li>
<li>New landing page should not be launched pending new data points.</li>
