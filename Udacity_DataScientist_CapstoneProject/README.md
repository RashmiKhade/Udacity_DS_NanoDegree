**Starbucks-Capstone**
Thanks to Udacity, as part of Data Scientist Nanodegree program, I got this exiting opportunity to work on a real world problem related to Data Science. I have chosen Starbucks Capstone Challenge to help Starbucks improve their Rewards Program to increase business and save cost.

**Installation**
The code should run with no issues using Python versions 3.*. Here is the list of modules required to run the notebook
* sklearn
* sklearn_evaluation
* prettytable
* matplotlib
* seaborn
* IPython.display 
* tqdm. 

Here is the schema and explanation of each variable in the files:

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record


link to the notebook - 

A detailed blog can be found at -  https://medium.com/@rashmi.khade/starbucks-capstone-challenge-ba6b42e9c83a

A BIG thanks to Starbucks for providing the challanging project to work on. And a BIG thanks to Udacity for providing me the knowledge and the opportunity to showcase the same.
