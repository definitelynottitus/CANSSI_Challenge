<h1>CANSSI BC Ferry Lateliness Prediction Challenge</h1>
<a href="http://www.canssi.ca/news-events/canssi-datathon-2019/" target="_blank">Click here to see description of the challenge</a>
<br/>
<a href="https://www.kaggle.com/titus24/competitions" target="_blank">Click here to see my Kaggle page</a>
<h3>The list of models we used to tackle the problem</h3>
<ul>
  <li><strong>Random Forest</strong></li>
  <li><strong>Logistic Regression</strong></li>
  <li><strong>Adaptive Boosting</strong></li>
  <li><strong>Extreme Gradient Boosting</strong></li>
</ul>
<h3>The rationale behind our model</h3>
<p> From the BC Ferry website we are able to obtain the information that heavy traffic and procedual issues combine account for 80% of the delay. We enginerred a new binary feature from the existing scheduel departure time column to seperate national and provincal holidays and weekends. The goal of this feature is to let models better highlight days which are more likely to be delayed due to heavy traffic from either holiday season or in the weekends.</p>
    
