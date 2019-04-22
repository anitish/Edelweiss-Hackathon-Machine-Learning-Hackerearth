<img src="https://github.com/buntys2010/Edelweiss-Hackathon-Machine-Learning-Hackerearth/blob/master/edel.JPG"/>

# Edelweiss-Hackathon-Machine-Learning-Hackerearth
Machine Learning hackathon by Edelweiss organised by Hackerearth
# Predict Forclosure Probability

# Problem Statement
India is a diversified financial sector undergoing rapid expansion, both in terms of strong growth of existing financial services firms and new entities entering the market. The sector comprises commercial banks, insurance companies, non-banking financial companies, co-operatives, pension funds, mutual funds and other smaller financial entities . The Edelweiss Group is one of India's leading diversified financial services company providing a broad range of financial products and services to a substantial and diversified client base that includes corporations, institutions and individuals. Edelweiss's products and services span multiple asset classes and consumer segments across domestic and global geographies. Given the availability of various alternatives across the industry customer has a propensity to move to another financial institution for Balance Transfer. Foreclosure and balance transfer has added to the concerns of NBFCs. Foreclosure means repaying the outstanding loan amount in a single payment instead of with EMIs while balance transfer is transferring outstanding Loan availed from one Bank / Financial Institution to another Bank / Financial Institution, usually on the grounds of better service, top-up on the existing loan, proximity of branch, saving on interest repayments, etc. Losing out on customers on grounds on foreclosure and balance transfer leads to revenue loss. Acquiring a new customer can cost up to five times more than retaining an existing customer and an increase in customer retention by 5% increases profits up to 25%. NBFCs have started taking pro-active measures to ensure this is curbed; and this is where you come in! Objective is primarily to arrive at a propensity to foreclose and balance transfer an existing loan based on lead indicators such as demographics, internal behavior and performance on all credit lines; along with the estimated ‘Time to Foreclose’. May the best algorithm win!

Participants are free to use any openly available data source to further enrich the dataset.

# Data Description

We have provided the following dataset:
<ul>
<li>Customer demographics</li>
<li>Customer transactions (ie. repayments made by the client)</li>
<li>List of foreclosed customers</li>
<li>Email interaction of the customer with the customer representative</li>
</ul>

The participants are expected to predict the probability of foreclosure for each of the data points in the test set.

# Leaderboard Score - 99.76 (AUC ROC)

# Learnings
<ol>
<li>I started this hackathon by taking the data in raw format and applying algorithm, I learned how analyzing data in proper format gives you higher accuracy</li>
<li>Library Hyperopt to tune the hyper parameters</li>
<li>SHAP to analysis the data</li>
</ol>

 # Things missed for higher accuracy 
 
 <ol>
<li>More focus on feature engineering</li>
<li>Use of aggregate features rather than selecting only last or sum values etc. </li>
</ol>

