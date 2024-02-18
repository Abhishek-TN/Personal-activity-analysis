# Personal Activity Analysis

This repository contains Jupyter Notebook files for analyzing Fitbit data using various machine learning models implemented with scikit-learn.

## Dataset

The dataset used in this project is the Fitbit dataset, which includes the following columns:

- **Id**: Identifier for the user
- **ActivityDate**: Date of activity
- **TotalSteps**: Total number of steps taken
- **TotalDistance**: Total distance covered (in miles)
- **TrackerDistance**: Distance tracked by the Fitbit tracker (in miles)

Example of dataset:
```
   Id     ActivityDate  TotalSteps  TotalDistance  TrackerDistance
0  1503960366  3/25/2016   11004       7.11           7.11
1  1503960366  3/26/2016   17609      11.55          11.55
2  1503960366  3/27/2016   12736       8.53           8.53
3  1503960366  3/28/2016   13231       8.93           8.93
4  1503960366  3/29/2016   12041       7.85           7.85
5  1503960366  3/30/2016   10970       7.16           7.16
6  1503960366  3/31/2016   12256       7.86           7.86
```

## Notebooks

This project includes the following Jupyter Notebook files:

1. **Personal activity analysis SVM.ipynb**: Implementation of Support Vector Machine model for predicting activity patterns.
2. **Personal activity analysis using KNN.ipynb**: Implementation of K-Nearest Neighbors model for activity prediction.
3. **Personal activity analysis Decision tree.ipynb**: Implementation of Decision Tree Classifier for activity prediction.
4. **Personal activity analysis Random forest.ipynb**: Implementation of Random Forest Classifier for activity prediction.

Each notebook contains data preprocessing steps, model training, evaluation, and inference sections.

## Requirements

To run the notebooks in this repository, you need to have the following libraries installed:

- scikit-learn
- pandas
- matplotlib
- numpy

You can install these libraries using pip:

```
pip install scikit-learn pandas matplotlib numpy
```

## Usage

1. Clone this repository to your local machine.
2. Install the required libraries as mentioned above.
3. Open the desired notebook using Jupyter Notebook or JupyterLab.
4. Follow the instructions within each notebook to execute the code cells and analyze the Fitbit data using the respective machine learning models.
