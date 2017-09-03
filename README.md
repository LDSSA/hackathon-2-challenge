# hackathon-2: Time Series!

## First things first

Read the [challenge](https://docs.google.com/document/d/1zjjJxPWABlJjqiNgy2B7LF0EO_qTcx7Lh9Rqoklhq7U/edit?usp=sharing)

## Target column

The target column is `sales`. Note that in the sales can have a negative number and this is the case in which returned merchandise exceeded the value of purchased merchandise. That's right, people returned more than the bought.

## How to make submissions

1. Slack Sam with the team gif and team name
1. Using the key given to you, visit http://hackathon-2.lisbondatascience.org/submit and follow the instructions

## Sample submission

Here is the first 5 lines of a valid submission.

```
date,section,store,sales
2010-02-05,1,1,24924.5
2010-02-12,1,1,46039.49
2010-02-19,1,1,41595.55
2010-02-26,1,1,45807.2778589
2010-03-05,1,1,17855.9188765
```

Since you are predicting sales for a particular day, each submission requires quite a bit more information (3 features!) in order to be able to identify which observation you are actually trying to predict. This is quite a bit different from the first hackathon in which we only needed a single ID to identify an observation.
