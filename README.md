# Kaggle-AB-Testing
# zscore, confidence interval

https://www.kaggle.com/zhangluyuan/ab-testing/code?datasetId=33220&sortBy=dateRun&tab=profile

**Discuss**
collecting saple data from groups and converted
performing z test and confidence interval using python scipy

***Conclusion***
1.Since our p-value=0.732 is way above our α=0.05 threshold, we cannot reject the Null hypothesis Hₒ, which means that our new design did not perform significantly different (let alone better) than our old one 

2.Additionally, if we look at the confidence interval for the treatment group ([0.116, 0.135], or 11.6-13.5%) 

we notice that:

It includes our baseline value of 13% conversion rate
It does not include our target value of 15% (the 2% uplift we were aiming for)

What this means is that it is more likely that the true conversion rate of the new design is similar to our baseline, rather than the 15% target we had hoped for. This is further proof that our new design is not likely to be an improvement on our old design, and that unfortunately we are back to the drawing board
