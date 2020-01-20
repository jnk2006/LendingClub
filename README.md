# LendingClub

## Project Description
<p>Your group members decide to run a startup company and pursue your entrepreneurship on peer-to-peer lending.  You identified the business platform, i.e.,  the lending club(<a href = "https://www.lendingclub.com/"></a>), the largest peer-to-peer online marketplace bringing together borrowers and lenders.   You will build a startup institutional investment company (please see the definition of the investment company in the lending club:<a href = "https://www.lendingclub.com/investing/institutional/team"></a>) using this platform to identify some segment of borrowers. However, you do not have enough funding of your own and plan to attract the venture funding and your friends (NOT your mortgage, it is too risky :)) to provide your startup funds.<br>
  (Description shown as professor provided on Canvas NJIT)</p>
  
## Dataset
<p>Since dataset was too large to upload on github, <a href = "https://www.kaggle.com/wordsforthewise/lending-club">click here</a> to access the <b>accepted_2007_to_2018Q4.csv.gz</b> data set.</p>

## NNTrust Investment company
<p>To be different from other peer-to-peer lending clubs, we decided to include data science predictive models into our company. The lenders have the advantage to choose their borrowers by the likelihood of loan being charged-off by the borrowers.</p>

### Important features
Some of the features that are considered while deciding loan charge - off are:
<ul>
  <li>Loan amount</li>
  <li>Term</li>
  <li>Interest</li>
  <li>Installments</li>
  <li>FICO score</li>
  <li>Employment data (length, income)</li>
  <li>Debt to income ratio</li>
  <li>Earliest credit line</li>
  <li>Open accounts</li>
  <li>Total accounts</li>
  <li>Mortgage account</li>
</ul>

### Predictive models
Predictive models and their AUC-ROC scores are:
<ul>
  <li>Logistic Regression: 0.7286</li>
  <li>SVM: 0.7226</li>
  <li>KNN: 0.7208</li>
  <li>Random Forest: 0.7305</li>
  <li>Random Forest with important variables: 0.72897</li>
  <li>Neural Network: 0.7290</li>
</ul>

<p>Though Random forest seems to be working fine, we decided to go with neural network because more parameters, like early stopping, regularizers and callbacks, can be used in the project (without sampling data) to obtain score higher than 90%.</p>
