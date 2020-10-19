# A/B Testing-Email Campaign Experiment with Causal Forest
A wine retailer was running email marketing experiments to evaluate the email promotion effectiveness prior to sending the emails to a broader set of customers. 
This project was to evaluate the effectiveness of this marketing campaign and found out the target audience who would be triggered to purchase due to 
the email using the experiment data.  <br>

Tool: R  <br>

* did A/B Testing randomization check 
* built regression models to estimate average causal effect
* conducted slice and dice analysis to explore differences in the potential response to the promotional email(built multiple regression models with interacted variables and compared the purchase lift)
* built a causal forest model to estimate individual-level conditional causal effect and used it along with the margin and cost information to score each customer 

Outcome: The causal forest model indicated 55% of the experiment sample should be targeted. Please view the report to check out the summary of characteristics of the targted group. 

### To view the code, please click the following link. <br>
http://htmlpreview.github.io/?https://github.com/Sichun-Li/A-B-Testing-Email-Campaign-Experiment-with-Causal-Forest/blob/master/wine%20retailer%20code.html
 
