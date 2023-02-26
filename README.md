# Data Preprocessing
## Introduction
Data preprocessing, which is a crucial phase in the data mining process, can be defined as the altering or dropping of data before to usage in order to ensure or increase performance.
Data analysis that has not been thoroughly checked for these issues may yield false results. So, before performing any analysis, the representation and quality of the data must come first.
Hence in this section, we usually preprocess a dataset from a company's campaign research.
## Procedure of Duty
### Data Preparation 
A modified version of the Bank Marketing dataset, which is the data set connected to direct marketing efforts of a Portuguese banking institution, is utilized in this experiment as the data file bank.csv. On phone conversations, the marketing campaigns were based.
In order to determine if the product (bank term deposit) would be subscribed ('yes') or not ('no'), it was frequently necessary to make more than one contact with the same client. Moro et al. (2014) created/donated the original dataset to the UCI repository (https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

![dataReview](https://user-images.githubusercontent.com/81562297/221419710-53133b85-fd6e-439f-97d3-4f0ace09d9de.png)

### Data Exploration
We would determine the correlation between pair-to-pair data features and obtain a description from this section.
In which the first task was to determine how three different forms of data—nominal, ordinal, and numerical values—were distributed.
In order to determine the relationship and affiliation of each pair of datasets, the second work would involve comparisons between three pairs of feature.
Ultimately, using the dataset's three separate properties, we would group its worth and derive an explanation for the research.

![group](https://user-images.githubusercontent.com/81562297/221419921-5baffe15-2dda-45e1-a3f6-8a857a409e34.png)

### Dealing With Missing Data
Due to the insufficient values in the dataset, the information may not be sufficiently reasonable to run any learning processes; however, this approach would address the issue.
In particular, there are numerous techniques to replace missing data and nan values, one of which is to use the mean or median of the numerical data.
![line](https://user-images.githubusercontent.com/81562297/221419971-6d0d76df-964e-485a-a853-c22bb509a367.png)

## Reference
https://docs.oracle.com/cd/E40248_01/epm.1112/cb_statistical/frameset.htm?ch07s02s10s01.html
