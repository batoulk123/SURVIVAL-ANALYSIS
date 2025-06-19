# SURVIVAL-ANALYSIS
This project analyzes survival for colon data using Kaplan-Meier analysis and cox regression to model time-to-event outcomes.
It includes data preprocessing, modelbuilding, and evaluation, providing insights into factors influencing survival.

*Insights*

1- Kaplan-Meier Curves showing an increasingly graphs providing a visual summary of the time event data, allowing to estimate survival          probabilities for each factor(exposed and colon status), determine median survival time, and compare survival between different groups.
2- The group with positive status of colon exposed to node4 has a risk of the cancer that is 20.4 times than the group with status 0.
3- Building a logistic model based on the status of colon by 73% accuracy of the classification.
4- Building a decision tree classified according to the number of nodes(exposed to node4 if nb of nodes>12),
   having a result of 98% as a percentage probability as if exposed leads to node4 case.
5- Calculating the risk measures even with making colon surgery, getting 96% risk ratio and 86% odds ratio which means that sample people       who made the surgery had 96% of the risk of reaching node4 level for colon compared to the non_surgeried people sample.
  
   **Suggesting that the surgery is providing some protection, but the effect is small.**

   **Project Link**   http://rpubs.com/batoulk/1320236
