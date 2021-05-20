# Health-Insurance
FinMan is a financial services company that provides various financial services like loan, investment funds, insurance etc. to its customers. FinMan wishes to cross-sell health insurance to the existing customers who may or may not hold insurance policies with the company. The company recommend health insurance to it's customers based on their profile once these customers land on the website. Customers might browse the recommended health insurance policy and consequently fill up a form to apply. When these customers fill-up the form, their Response towards the policy is considered positive and they are classified as a lead.
## Insights
<img src=images/1.PNG></img>

##### Is Spouse with respect to Response variable has distribution of 75:25 %.. Likelihood of positive response while married approximately equals to while not married. Hence this does not explain the target variable 

<img src=images/2.PNG></img>

##### City Code with respect to Response variable has distribution of 75:25 %.

<img src=images/3.PNG></img>

##### Average Premium of Is Spouse category per Response type has distribution of 50%:50%. Average Premium per spouse category does not explains target varable, as average premium for all the combinations is .50(Approx).

<img src=images/4.PNG></img>

##### Distribution of Holding Policy Duration to Response type is 75%:25%(Approx). Which states that there is approximately 25% probability for positive response type.

<img src=images/5.PNG></img>

##### Distribution per Response type for Policy Type is 75% :25% (Approx)

<img src=images/6.PNG></img>

##### The distribution of Policy Category to Response type shows variation, hence we can say policy category is a potential important variable.

<img src=images/7.PNG></img>

##### We notice that within same spouse category it is hard to state difference for each response type, distribution is approximately same. But when we compare the categories of Spouse type , we can see the change in distribution. Which means for non married , the upper age has to spend less in comparison to married. But we can not distinguish for response categories for each spouse type.

<img src=images/8.PNG></img>

##### We see the premium distribution for response type is almost same, there is no difference in distribution for positive and negative response. Hence it does not help in explaining the Response, both category has equal likelihood.

## Aproach

### Missing Values Treatment

- Categorical - Mode

- Numerical - -999

### Feature Aggregation 

- Groupby using statistcal methods like min, max, average, etc. Used manual function like top_ten and bottom_ten 

