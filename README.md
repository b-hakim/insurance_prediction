# Insurance Project 

The goals of this project are: 
1) Analyze the client's insurance charges 
2) Suggest Client's subscription fees 
3) Predict the lost profit ratio (use the suggested fees as paid money)

The analysis and prediction module are discussed in the attached notebook.

# Current State
- The significant features that affect the costs are: ['smoker', 'bmi', 'age'] in order. Specifically, clients with 'bmi'>= 30, reflecting obesity, are most relevant to the insurance costs. 
- It seems that clients with obesity who are smokers can have a separate higher premium plan as the insurance costs range between 30k to 45k
- Similarly, clients who are not obese but are smokers can have an average premium plan as their insurance costs range roughly between 10k to 25k
- The current model achieves a 14% error for the prediction of the insurance cost. Further improvement is achievable by using different models based on the client category (roughly can be divided into 4 categories based on the analysis made in this work. 

# Future work
- Analyze more features to separate the non-smokers and obese class as well as the non-smokers and non-obese class into separable categories to reflect the different cost categories.
- Decreasing the prediction error by using a different model based on the different categories. It seems that each category can be modeled by a linearly, thus
- Suggesting a different set of subscription plans and showing the loss rate for each set.

