# Twitter-Personality-Prediction

Big Five personality traits Analysis in Turkish tweets is implemented with Bert

# Dataset

The dataset was created by collecting Tweets from Twitter users in line with a survey we conducted for Big Five personality traits.

# Notebooks

Notebooks are self-explanatory. Separate models were trained for each of Big Five personality traits. In addition, models were trained for 5 different traits such as "Satisfaction with Life" and "Income Level". You can take a look at the details of the training by reviewing the "training_example.ipynb" notebook.

# Results

We obtained separate results for each model. 

**For "Agreeableness" :**

![Görüntü 25 03 2022 22 46](https://user-images.githubusercontent.com/58830806/160191137-d989cb4e-787b-4ea8-a6d8-30818414547b.jpg)

# Analysis

**The analysis is generated as follows:**

|name      | perc(%)   |   count|
|--------- | --------- | -------|
|muhalefet | 74.6%     |    1838|
|iktidar   | 25.3%     |     624|
|total     | 100%      |    2462|

|name     | perc(%)   |   count|
|-------- | --------- | -------|
|karamsar | 27.7%     |     683|
|memnun   | 72.2%     |    1779|
|total    | 100%      |    2462|

|name          | perc(%)   |   count|
|------------- | --------- | -------|
|alkol-olumlu  | 40.8%     |    1005|
|alkol-olumsuz | 59.1%     |    1457|
|total         | 100%      |    2462|

|name        | perc(%)   |   count|
|----------- | --------- | -------|
|din-olumlu  | 26.4%     |     652|
|din-olumsuz | 73.5%     |    1810|
|total       | 100%      |    2462|

|name    | perc(%)   |   count|
|------- | --------- | -------|
|öğrenci | %15.6     |     385|
|tüccar  | %22.0     |     543|
|işçi    | %30.1     |     742|
|memur   | %32.1     |     792|
|total   | %100.     |    2462|

|name   | perc(%)   |   count|
|------ | --------- | -------|
|agree  | 39.6%     |     975|
|cons   | 83.1%     |    2046|
|extra  | 88.2%     |    2173|
|nevro  | 11.9%     |     294|
|open   | 37.2%     |     918|
(from:**Twitter Username**) lang:tr -filter:replies - 2462
