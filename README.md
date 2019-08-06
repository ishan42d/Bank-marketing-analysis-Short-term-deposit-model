## Bank marketing analysis / Short term deposit model
Text file containing some real data that relates to a marketing campaign run by a bank. The aim of the marketing campaign was to get customers to subscribe to a bank term deposit product. Whether they did this or not is variable ‘y’ in the data set.
The bank in question is considering how to optimize this campaign in future. What would your recommendations to the marketing manager be?

1.2 Categorical and Non Categorical attributes
Categorical -Index(['job', 'marital', 'education', 'default', 'housing', 'loan', 'contact', 'month', 'poutcome', 'y']
Non Categorical(Continuous) - Index(['age', 'balance', 'day', 'duration', 'campaign', 'pdays', 'previous'], dtype='object')

2.2 Initial observations regarding the data

Total 45211 records,7 numeric attributes : age, balance, day, duration, campaign, pdays, previous,10 categorical attributes further divided into : 6 multi-valued categorical attributes : job, marital, education, contact, month, poutcome,3 yes/no binary attributes: default, housing, loan,1 target attribute ‘y’.

No missing values (as seen above): Pre-processing should be easier.

# Distribution of #Target variable: "y": Data is imbalanced because there is ~88% 'no' and 12% is 'yes'.

No Explicit missing values in the dataset but there are a lot of ‘unknown’ values for some of the categorical variables which will be treated later.

Some variables ('balance','pdays', 'previous','Pdays','Duration') has outliers. That can also visualize through graphs further.

# The Mean age is 41 as per the data set. The mean balance is 1362 and the SD balance is high which is a sign that this is heavily distributed across the dataset.

81.74% of the time outcome of previous marketing campaign is unknown.

Most of the clients have never been contacted since contact is unknown for 28.79%.

## For detailed report please contact me at ishan42d@gmail.com
