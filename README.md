# Personalized-Cancer-Diagnosis
**Description**

A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated. Once sequenced, a cancer tumor can have thousands of genetic mutatio ns. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). As not all mutations lead to cancer. Due to a mutation in a gene, there is some genetic variation developed in a gene. But the question comes, from which particular mutation this genetic variation happened in a gene. Currently this interpretation of genetic mutations is being done manually which is a very time-consuming task. Based on a gene and a variation in it, a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

**Business Problem**

A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze.
The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest.
Finally, this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them into any one of the 9 different classes. Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated by a machine learning model.
Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated by a machine learning model.

**Problem Statement**

Classify the given genetic variations/mutations based on evidence from text-based clinical literature. In this problem, we need to find the mutation-type given the gene, variation and some text data from published research.

**Source of Data**
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data Data: Memorial Sloan Kettering Cancer Center (MSKCC)

**Real-world/Business objectives and constraints.**

No low-latency requirement.

Interpretability is important.

Errors can be very costly.

Probability of a data-point belonging to each class is needed.

**Prerequisites**

Python 3

Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy 
and scipy.

mlxtend

Library used

ipython-notebook - Python Text Editor/Google colab

sklearn - Machine learning library

seaborn, matplotlib.pyplot, - Visualization libraries

numpy, scipy- number python library

pandas - data handling library

mlxtend - used for stacking the models

Done by- Author
Sai Krishna
