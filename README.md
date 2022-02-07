# ML-Classification-Model-Development
Machine Learning Classification Model

Building a predictive model on a binomial response variable including feature engineering, model preparation, variable selection, and model development.



**Case Introduction
**A Machine Learning analysis to predict Revenue and Cross Sell Success for Halfway There was conducted.

Revenue
The OLS Regression Model results in an R-squared value of 0.748.

Insights:

1) Customers who ordered beverages to their meal drive Revenue. The engineered feature showcases that for every additional drink being sold to a meal, the revenue increases by 18.16%.

2) Customers that attended at least one masterclass are more likely to spend more on average. For every additional customer watching a masterclass, revenue goes up by almost 4%.

Recommendations:

Cross-selling for beverages should be promoted more heavily. For example, the customer could be asked to add a drink to the order right before checking out. Furthermore, a campaign to promote masterclasses should be initiated. A discount on the first order for taking part in the first masterclass could be an incentive for customers.

Cross Sell Success
To evaluate important features predicting cross-sell success, several machine learning models have been performed. The Tuned Tree model most successfully resulted in an AUC of 0.732.

Insights:

1) Customers who provided personal or professional emails were more likely to increase the cross-sell success than those who entered junk mail. This might result in less engagement with the platform as promotions are likely to be less seen.

2) The Tuned Tree Model indicates that fewer cancellations lead to more cross-sell success. A goal of fewer than 1.5 cancellations before noon should be targeted.

Recommendations:

To prevent people from using junk emails, a control instance should be implemented in the sign-up phase, avoiding certain domains. With a simple feedback survey, further analysis could discover the intentions behind cancellations.

Conclusion
We conclude that changes to increase cross-selling of beverages and implementations to enhance content consumption are predicted to raise revenue. Furthermore, the prevention of sign-ups with junk mails and the understanding of canceled orders is essential to cross-sell success.

