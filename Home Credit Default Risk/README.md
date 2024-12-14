![Home Credit Default Risk Project Banner](/images/Home_Credit_logo.svg.png)


# Business Problem
Home Credit, a financial services company, aims to increase financial inclusion by offering loans to individuals with limited or no formal credit history. However, the absence of traditional credit data poses a challenge in assessing these borrowers’ repayment capacity accurately. To prevent financially vulnerable clients from being rejected or overburdened by unmanageable loans, Home Credit seeks a more reliable predictive model to determine loan applicants’ repayment abilities. This model will not only improve client satisfaction but will also support sustainable lending practices by minimizing loan defaults.

# Project Solution
For our solution to this project, we initially thought that the random forest model was the best model for HOme Credit to use in predicting the probability of default. We observed an accuracy of 0.957 and an AUC of 0.99 but quickly came to realize that our models were not actually performing that well. We made some mistakes that are mentioned below regarding balancing our data so in the end, we did not have a feasible solution. There are several modeling improvements we could make to obtain a feasible solution and I see our results as a good start but not an absolute final outcome.

# My Contribution
My contribution to this project was writing the first pass of the data cleaning function. From there, my teammate and I collaborated to make improvements to the code and add other components where needed. Additionally, I owned the entire Random Forest modeling process from the initial model to the improved model as well as the interpretating and potential improvements. I also contributed to the final presentation and owned a good portion of the talking points.

# Business Value
Since we did not have a feasible solution, there is unfortunately not much business value. However, the value could been seen as the need for more data in addition to the application data. At the conclusion of this project we learned that we should have included more data points that were available to us so if we were to provide a business value, it would be that the application of a potential client is not sufficient enough do determine their credit worthiness. 

# Project Challenges
The main challenge we faced during this project was bandwidth. For th majority of the project, there were only two of us until we completed all the modeling and complied our findings. This limited us a lot with how deep we could dive into the data and models. Another big challenge we faced with this project was our approach to our balancing technique. In our final model we used a SMOTE balancing technique but made the mistake of applying oversampling to the entire dataset rather than just the training split. Additionally, I personally faced challenges with knowing when to take samples of my dataset and when not to so I spent a lot of time running my models since I ran the models on the entire dataset. Becasue of this, I missed opportunities to make other improvements to my model or even explore additional models like xgboost to compare the performance to the random forest model.  

# Project Learnings
The main learning I took away from this project is know when to split my dataset is to separate samples to improve run time. Some other learning I took away was to spend more time on feature engineering and using additional available datasets. My team did not use the other datasets available to us (previous application, beureau data, etc.) because of bandwidth but I really would have liked to explore that more. We took a fairly simple approach to cleaning our data and I think we would have seem better results had we taken the time to include other datasets for additional features and done more complex feature engineering. 
