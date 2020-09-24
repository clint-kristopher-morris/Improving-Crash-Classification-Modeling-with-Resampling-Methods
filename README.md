# Improving-Crash-Classification-Modeling-with-Resampling-Methods

### Abstract:

Crash data analysis is commonly subjected to imbalanced data. Varied by facility and
control types, some crash types are more frequent than others. Uncommon crash
types are routinely more severe and associated with higher economic and
comprehensive costs and thus crucial to prevent. It is paramount to generate inferential
models that can distinguish severe types of crashes from more common, lower risk
events. The process of modeling towards infrequent instances induces data disparity.
Therefore, mitigating and managing imbalanced data is essential to the development of
meaningful inferences that help to reveal effective countermeasures. This study
focuses on comparing the effects of data resampling on inferential machine learning
and classical statistical models. These models were tasked with classifying different

types of events observed in 5-minute windows across a day. The events include non-
crash as a special case and four types of collision (i.e., rear-end, same-direction

sideswipe, angle, single vehicle) on freeways. Among the five classes there exist a
vast divergency in data representation, which necessitates resampling strategies to
deal with the data imbalance. Specifically, the eXtreme Gradient Boosting, one of the
most popular machine learning methods, and the classic nested logit model were
compared. It was found that oversampling enhanced model performance on minor
class prediction. The adaptive synthetic sampling approach achieved the best results,
followed by random oversampling.

[link to research!](https://drive.google.com/file/d/1tExQWZEbqmtM9JhJNhVgwSC_BLKwdPph/view)

## Data distribution prior to resampling
![Alt Text](https://i.ibb.co/d2qyL0M/paperp1.png)
## Data after resampling
![Alt Text](https://i.ibb.co/0K6SxQ7/paperp2.png)
## Figure constructed to obtain parallels between the GBM and nested logistic model
![Alt Text](https://i.ibb.co/hm8v2Q7/paperp3.png)
