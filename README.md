# Sampling_comparision

## Introduction to Sampling

Sampling is a statistical technique used to collect data from a subset of a population to make inferences about the whole population. It is often used when it is impractical or impossible to study the entire population.

## Oversampling

In this study, an oversampling technique was used to address the imbalance in the dataset, where there were many more non-fraudulent cases than fraudulent cases. Oversampling involves creating more samples of the minority class (fraudulent cases) to match the number of samples in the majority class (non-fraudulent cases). This results in a more balanced dataset that can be used to train machine learning models more effectively.

## Dataset and Results

The dataset used in this study is Creditcard_data.csv. The results of the sampling comparison are stored in the comparison.csv file.

## Sampling Techniques

#### 1. Simple Random Sampling:
Employs randomization to ensure each population member has an equal probability of selection, guaranteeing unbiased representation.


#### 2. Systematic Sampling:
Involves selecting elements at predetermined intervals, offering efficiency while requiring careful interval selection to avoid periodicity biases.


#### 3. Cluster Sampling:
Divides the population into naturally occurring groups (clusters) and randomly selects clusters, providing cost-effectiveness but potentially introducing cluster-level biases.


#### 4. Stratified Sampling:
Segments the population by relevant characteristics (strata) and randomly selects elements within each stratum, ensuring proportional representation for key subgroups.


#### 5. Bootstrap Sampling:
Relies on resampling with replacement from the original data, generating pseudo-populations to robustly estimate sampling distributions and variances.


## Models

Five machine learning models were applied to each of the samples generated using the different sampling techniques:

* Random Forest
* Logistic Regression
* Naive Bayes
* Decision Trees
* KNN


Following the generation of five distinct samples using these techniques, five models were applied to each sample. The accuracies of each model for a given sample are summarized in the table below:


![image](https://github.com/UdaySharmaUS/Sampling_DS/assets/110687732/2cef532c-80cf-4426-88f8-855279165819)


In the table above, each row corresponds to a sampling technique, and each column represents the accuracy achieved by each model applied to the respective sample generated using that particular technique.


## Flowchart

The following flowchart is a brief overview of the sampling process:

![image](https://github.com/UdaySharmaUS/Sampling_DS/assets/110687732/c434ff66-f8de-4d8a-a7a9-9a517704831a)

