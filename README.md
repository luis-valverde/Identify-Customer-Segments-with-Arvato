# Identify Customer Segments with Arvato

## Table Of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Neccessary Files](#neccessary-files)
- [How to Run](#how-to-run)

## Introduction

This repository contains all my work for the Udacity's Machine Learning Introduction Nanodegree Program.

The goal of this project was to identify segments of a population that form the core customer base for a mail-order sales company in Germany. To accomplish this, I first preprocessed and clean the data in order to convert it into an usable form. Then, I applied unsupervised learning techniques as dimensionality reduction and clustering to segment customers. Finally, I used those clusters to see which of them comprise the main user base for the company.

## Project Overview

In this project, you will work with real-life data provided by Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. Your job as a data scientist will be to use unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, you will also need to assess and clean the data in order to convert the data into a usable form.

## Requirements

This project uses the following software and Python libraries:

- [Python](https://www.python.org/downloads/release/python-364/)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn (v0.17)](https://scikit-learn.org/0.17/install.html)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/distribution/) distribution of Python, which already has the above packages and more included.

## Neccessary Files

There are some files needed to solve the project.

1. **Identify_Customer_Segments.ipynb:** This is the main file where I performed the work on the project.
2. **Udacity_AZDIAS_Subset.csv:** Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
3. **Udacity_CUSTOMERS_Subset.csv:** Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
4. **Data_Dictionary.md:** Information file about the features in the provided datasets.
AZDIAS_Feature_Summary.csv : Summary of feature attributes for demographic data.

In addition to Udacity's Terms of Use and other policies, the use of the AZ Direct GmbH data is solely for the Unsupervised Learning project; thefore, the following files could not be submitted in this repository:

- Udacity_AZDIAS_Subset.csv
- Udacity_CUSTOMERS_Subset.csv
- Data_Dictionary.md

## How to Run

In the Terminal or Command Prompt, navigate to the folder on your machine where you've put the project files, and then use the command:

```bash
jupyter notebook Identify_Customer_Segments.ipynb
```

 to open up a browser window or tab to work with your notebook.
 Alternatively, you can use the command:

 ```bash
jupyter notebook
```

or

```bash
ipython notebook
```

and navigate to the notebook file (Identify_Customer_Segments.ipynb) in the browser window that opens.
