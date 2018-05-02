# predict purchase through user activities
description: 
- The  data is pulled from raw logs of a marketing database. It has three columns that record user activity over time:
    user_id,activity_date and activity_type.
- Given user activities, can we build a model that predicts which new user will make a purchase in the future?

- data has about 5 million logs, with 341568 unique user ids.
    
Summary of results
- if customer support is available, it is the best predictor. Those who received custormer support do purchase.
- Otherwise, 'EmailOpen' is the most useful feature to predict purchase, followed by 'FormSubmit', 'EmailClickthrough', 'PageView' and 'WebVisit'.
