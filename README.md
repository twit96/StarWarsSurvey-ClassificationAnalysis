<h1 align="center"> Star Wars Survey Classification Analysis </h1> <br> 

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents
- [Dataset Description](#dataset-description)
- [Project Description](#project-description)
- [Project Notebooks](#project-notebooks)
- [Miscellaneous Files](#miscellaneous-files)
- [Contributors](#contributors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Dataset Description 
The Star Wars Survey dataset is a labeled dataset with 1188 records. It has 15 features, which are survey questions regarding people's opinions on the Star Wars franchise and some personal information such as: 

* "Do you consider yourself a Star Wars fan?",
* "Which is your favorite movie?",
* "Which character shot first?",
* "Gender",
* "Income",
* et cetera. 

More information about the dataset can be found [here.](https://github.com/fivethirtyeight/data/tree/master/star-wars-survey) 

## Project Description 
Our aim is to train a classifier to predict a person's answers to some questions about the franchise given their answers to other such questions, or to try to predict a person's personal characteristics based off of their answers to questions about the franchise. 

## Project Notebooks 
The project is divided into the six Jupyter Notebooks below: 

1. [Data Preparation](./project_files/data_prep.ipynb)
2. [Data Exploration and Feature Engineering](./project_files/data_expl_feature_eng.ipynb)
3. [Decision Tree Classifier](./project_files/decision_trees.ipynb)
4. [K-Nearest Neighbors Classifier](./project_files/knn.ipynb)
5. [Naive Bayes Classifier](./project_files/naive_bayes.ipynb)
6. [Neural Networks Classifier](./project_files/neural_network.ipynb) 

## Miscellaneous Files 
* [Column Names](./project_files/column_names.txt) - Text file manually created and used in the Data Preparation notebook to replace the two header rows of the dataset with a simpler, single header row. 
* [Unique Values](./project_files/unique_values.txt) - Text file generated in the Data Preparation notebook in order to manually check for inconsistent values in the dataset. 

## Contributors 
[Nico Arrieche](https://github.com/nicoarrieche/) • [Chance Mason](https://github.com/cmason1998) • [Mitchel Walker](https://www.linkedin.com/in/walker-mitchel/) • [Tyler Wittig](https://www.linkedin.com/in/tylerwittig/) 
