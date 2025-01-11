**Insights**

*   The Tuned XG Boost model provided the highest F1 score of 83%. The runner up was the Stacking Classifier model (82.8%), followed by the Tuned Gradient Classifier (82.6%).

*   The most important feature was education of employee, going as high as 47% in the Tuned Gradient Boost Model. The Tuned XGBoost and Random forest classifiers hovered between 30-35%.

*   Job Experience and Unit of Wage - Hour competed for second most important feature: Job experience was found to be second most important in the Tuned Gradient and Tuned XG Boost Models (15-17%), while Unit of Wage - Hour was second for the Random Forest (18%).

*   The top three importance features were consistent across the Tuned XGBoost, Tuned Gradient Boost, and Random Forest Models.

*   Unit of Wage - Hour was negatively correlated with Case Status (Having Unit of wage = hourly had more visa denials).

*   Job Experience and Education of Employee were both positively correlated with Case Status (Experience + Better education had less Visa Denials).

**Recommendations**

*   The Office of Foreign Labor Certification (OFLC) should first look into unit of wage and prevailing wage standardization. Everything should be converted into hourly (or the most minimum) unit of wage. Converting to annual unit is not recommended because it is unknown if the hourly workers work as much as the annual workers.

*   The OFLC should do more research on job experience, including length of experience, industry, and quality. Yes or no for Job experience does not give a good picture.

*   More research should be done into the actual costs associated for businesses on wrongly approving or wrongly denying candidates. What are the costs for sponsoring an unqualified worker? What are costs of overlooking a qualified worker?

*   Until more research is performed on wage standaridization, prior job experience, and associated business costs, I do not believe the model is ready to be deployed. Since these factors weight so heavily on model decision, it would be irresponsible to use it without the research.

*   The OFLC can, however, use a predictive model for a pre-screen process that declines applicants who have no prior job experience and no prior education. However, there is no data on no prior education in this dataset, so that might need to be conducted as well.
