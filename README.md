<h1 align="center"><b>Learning Disorder Prediction in Pediatrics with ASD</b></h1>

<h1><b>Abstract</b></h1>
Learning disorders are common among Pediatric individuals with Autism Spectrum Disorder(ASD). Although autism itself is not a learning disability, it can significantly affect a child’s ability to process and retain information. Early diagnosis of Pediatric individuals who may have chances of developing learning disorder might help to by a lot provide effective treatment. This research aims to develop mechanisms to detect learning disorder in Pediatric individuals aged from 1 to 18 years old. Nine machine learning algorithms were tested to curate an accurate model to predict whether a pediatric individual is susceptible to developing learning disorder or not. Random Forest outperformed all the classifiers. The model was calibrated by amalgamating a tool that enables the model to interpret and retrace the underlying factors that contribute to the results. The experimental results revealed that it is possible to detect learning disorder in Pediatric individuals with high reliability.


<h1><b>Result Table</b></h1>
Table I: Accuracy for different algorithms on dataset

| Algorithms              | Accuracy | Precision | Recall | F1 Score | Train Time (ms) |
|-------------------------|----------|-----------|--------|----------|-----------------|
| K-NN (n=5)              | 98.38%   | 100.00%   | 98.00% | 99.00%   | 0               |
| K-NN (n=15)             | 97.67%   | 100.00%   | 97.00% | 98.00%   | 93.8            |
| Decision-Tree (gini)    | 99.22%   | 100.00%   | 99.00% | 99.00%   | 15.6            |
| Decision-Tree (entropy) | 99.22%   | 100.00%   | 99.00% | 99.00%   | 0               |
| Random Forest           | 99.22%   | 100.00%   | 99.00% | 99.00%   | 156.3           |
| Naive-Bayes (Gaussian)  | 99.22%   | 100.00%   | 99.00% | 100.00%  | 93.8            |
| ZeroR                   | 54.04%   | 54.00%    | 100.00%| 70.00%   | 0               |
| Logistic Regression     | 99.03%   | 100.00%   | 99.00% | 99.00%   | 15.63           |



Table II: Accuracy for different algorithms on dataset after using various hyperparameter optimizers

| Algorithms              | RandomizedSearch CV(%)	| GridSearch CV(%) |
|-------------------------|-------------------------|------------------|
| Random Forest (gini)    | 99.22%                  | 99.22%           |
|Random Forest (entropy)	| 99.22%                  | 99.22%           |




A research paper based on this project was also published. You may find more about the project [here](https://ieeexplore.ieee.org/document/10499515)




