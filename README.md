Supermarket Customer Analysis
==============================

Design marketing strategies aimed at customer segmentation based on data analysis.

Introduction
------------
A company engaged in Store Retailer wants to do a promotion for its customers. The company has conducted a campaign to all members and has obtained data on customers who have received campaigns or not. Based on this data, the company asks the Data Analyst team to further analyze the campaign that has been held. Then, the results of the analysis will be used as a consideration for future campaigns.

Problem Statement
------------
Based on the campaigns that have been carried out, the company wants to know what kind of customer segments will accept the campaign or who will not accept the campaign. This will be useful for the company, so that the company can receive maximum benefits or it can be said what strategies will be used to have good effectiveness for the next campaign.

To achieve the above, we as a Data Analyst team will try to answer the following questions:
1. Can the campaign be said to be quite **effective**? The assumption that the level of effectiveness of the campaign is seen from the total amount of spent. This assumption is taken due to data limitations, especially for the absence of data on how much it costs to hold a campaign and how much revenue is generated in each campaign.
2. How does customer demographics affect **campaign**? This is intended to find out how the segmentation of customers.
3. From the segmentation, what **product** is most often purchased by customers?
4. In which **place** do many customers make purchases?

Data
------------
To answer the above question, we will analyze based on the data of supermarket customers that has been collected by the company. The dataset can be accessed [here](https://drive.google.com/drive/folders/1WodnBbuYTvsF0-6HTuQABQ0KCS31lqbK).

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third-party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    │
    ├── notebooks          <- Jupyter notebooks. The naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-data-preperation`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results-oriented visualizations
    │       └── visualize.py
    │
    └── references         <- Data dictionaries, manuals, and all other explanatory materials.


--------