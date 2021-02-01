# Ford Gobike Trip Data
## by Reham ElTagoury

## Dataset
 This Dataset consist of over 18k trips made by people I am keen to study if the features like user type , gender and birth year can help in prediction of duration.
 Download the dataset from [Here](https://www.kaggle.com/franckjay/ford-gobike-data) I used the 2019 version provided in Udacity Classroom


## Summary of Findings
In the exploratory notebook we explored the data to know whether we can predict the duration of the trip according to the other features we found out that the data has plenty of outliers like the start and end locations of some trips are the same so wehad to get the distance as expected it was less than 0.0001 so we had to filter them, we also studdied the effect of birth year and turned out thta young people tends to have more trip duration than older people. also the femal customers tend to have long duration than male customers so it's better to promote bikes to them. when we studied the days of the week it turned out that thursday is the most picked day by the people and sunday and saturday are the least so we can make offer on these days for people to take their bikes. 



## Key Insights for Presentation

- The relation between the distance and duration wasn't that useful (pretty low correlation between them)
- The female customers tends to make longer trips than male
- Customers tends to make longer trips than subscribers.
- Young people make longer trips
