
# ProjectPrediction - Use ML to predict the project whether pass or not?

At first, we prepared Kickstarter datasets from kaggle.com as our labeled data for predicting the results. We aim to use supervised learning to train the machine with accurate prediction. As our project, the Kickstarter datasets contain data on the project Name, Category, Subcategory, Project duration, Money goal, Pledged, number of backers, and State (Failed or not). Before we continue with the data, we should install the packages for training the machine.

## Acknowledgements

 - [KickStarter dataset](https://www.kaggle.com/datasets/kemical/kickstarter-projects/data)
 - [For Data Preparation process](https://www.keboola.com/blog/data-preparation-7-easy-steps-to-deliver-high-quality-data)
 - [Types of Machine Learning](https://www.sas.com/en_gb/insights/articles/analytics/machine-learning-algorithms.html)
## Library Installation

Install numpy on your command prompt, which are essential for 
data structures for numerical operations.

```bash
  pip install numpy
```


Install pandas on your command prompt, which works with data structures like DataFrames and Series. It can load, clean, and preprocess data.

```bash
  pip install pandas 
```


Install seaborn, matplotlib on your command prompt, which helps with data visualization, an essential step for understanding data and the results of your machine-learning models.

```bash
  pip install seaborn
  pip install matplotlib
```


Install scikit-learn on your command prompt, which provides tools for data preprocessing, model building, model evaluation, and more.

```bash
  pip install scikit-learn
```

### After finishing the installation 
we need to make our data is ready to train by 
- Data cleansing, which deletes the fragment data or useless data like NULL and NaN values. 
- Data preparation, to correct the data, for example, ID is INT, but in reality, ID is not used to calculate anything, so it would be string instead. 

## Feedback

If you have any feedback, please reach out to us at phornphatmak1112@gmail.com

