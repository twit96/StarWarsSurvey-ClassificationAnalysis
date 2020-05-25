<h1 align="center"> Star Wars Survey Classification Analysis </h1> <br> 

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

1. [Data Preparation](./1. Data Preparation.ipynb)
2. [Data Exploration and Feature Engineering](./2. Data Exploration and Feature Engineering.ipynb)
3. [Decision Tree Classifier](./3. Decision Tree.ipynb)
4. [K-Nearest Neighbors Classifier](./4. KNN Analysis.ipynb)
5. [Naive Bayes Classifier](./5. Naive Bayes Data Analysis.ipynb)
6. [Neural Networks Classifier](./6. NeuralNetwork.ipynb) 

## Miscellaneous Files 
* [Column Names](./column_names.txt) - Text file manually created and used in the Data Preparation notebook to replace the two header rows of the dataset with a simpler, single header row. 
* [unique_values.txt](./unique_values.txt) - Text file generated in the Data Preparation notebook in order to manually check for inconsistent values in the dataset.
