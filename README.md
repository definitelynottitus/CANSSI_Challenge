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
<p>From the BC Ferry website we are able to obtain the information that heavy traffic and procedual issues combine account for 80% of the delay. Because of this fact, the model we build is design to mainly focus this part of the delay. Moreover, this part of the delay are most consistent compare to delay cause by weathers.</p>
<ul>
  <li>A binary feature is added from the existing full date column to seperate national and provincal holidays and weekends. The goal of this feature is to let models better highlight days which are more likely to be delayed due to heavy traffic from either holiday season or in the weekends.</li>
  <li>A categorical feature is added from the existing full date column to separate different seasons. This feature has 4 levels which account for different seasons. This is added because our exploratory plot shows that during the summer there are more delays due to summer break</li>
  <li>A binary feature is added from the existing departure time column to seperate hours with heavy traffic.</li>
  <li>A binary feature is added using wind speed and visibility column from the weather data provide to enginer the likelyhood of procedual delay due to low visibility or high wind speed.</li>
</ul>

    
