## Hi there 👋

**I'm Steven Oldenburg**, a data professional. I'm passionate about leveraging data and Python to solve problems and extract insights.

### My Projects

#### Current Project:
* **Anti Money Laundering GNN Models:**  This is a new modeling technique for AML that produced amazing results, 98%+ accuracy using synthetically created data.  I found the data on kaggle and reviwed some of the literature found here: [a link](https://arxiv.org/pdf/2306.16424)  One thing that stood out is the data used requires a overview of all the data from the banks, so for the model to work it would need a central agency which stores all this private data and be readily shared which is a significant problem.  I created a model using a descision tree classifier but created two new fields which quantify the numbers of transactions without all the information being passed as was able to improve scores from 30% to 80% showing a path which may be much more practical with sharing only the number of current and previous transactions to multiple accounts and banks, which allowed the model to predict fan-in, out and scatter methods.  More research will be needed and I will post my results when completed on Kaggle, but as of right now it shows:
  * With a small amount of data from previous transactions, a count of transactions from and to unique accounts/banks AML scores can be doubled or tripled in accuracy.
  * The GNN models seem ideal under ideal circumstances but has nothing to do with the information that most banks have access to predict AML, like KYC best practices.

#### Data Science & Machine Learning

* **Time Series Modeling:** This is a college project that uses time series modeling to forecast predictions and detect seasonal trends.  A weekly trend was identified and the predict was relatively accurate, however, it should be noted that the model is only accurate are predicting trends in revenue, not daily revenue income.

* **Market Basket Analysis:** This was a college project for my masters degree to use A/B testing to draw insights of customer behavoirs.  We found that customers who purchased monitor mounts also purchased Co2 dust off and these two projects pair well together for future marketing initiatives.

* **NLP and Logistic Regression:** Finaly project, I built a model to predict star ratings based on Yelp reviews using NLP techniques. Further explored topic analysis and word frequency insights.  Findings were that 17% of the 5-star reviews in the yelp dataset were not organic customers and often were "trying" new things.  The findings also suggest that certain items draw people to give 5-star ratings more often such as coffee, sandwhiches or chicken.

* **Web Scraping Project:** Personal project to grow, I created this project to learn how to use Python to scrape a webpage efficently.  This is a very old project.

#### Technologies
* Python
* Core Data Manipulation and Analysis
* NumPy
* Pandas
##### Machine Learning
* Scikit-learn
* NLTK (Natural Language Toolkit)
* Statsmodels
##### Data Visualization
* Matplotlib
* Seaborn
##### Web Scraping
* Beautiful Soup
* Requests
##### Market Basket Analysis
* Apriori algorithms

### Let's Connect!
I'm always open to new challenges and collaborations. Feel free to reach out if you have any questions or want to discuss potential projects.
