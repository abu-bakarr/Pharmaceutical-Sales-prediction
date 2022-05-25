# Rossmann-Pharmaceuticals-Sales-Prediction

**Table of Contents**

- [Rossmann-Pharmaceuticals-Sales-Prediction](#rossmann-pharmaceuticals-sales-prediction)
  - [Overview](#overview)
  - [Scenario](#scenario)
  - [Approach](#approach)
  - [Project Structure](#project-structure)
    - [data:](#data)
    - [models:](#models)
    - [notebooks:](#notebooks)
    - [scripts](#scripts)
  - [Installation guide](#installation-guide)

## Overview

This repository is used for week 3 challenge of 10Academy. The instructions for this project can be found in the challenge document.

## Scenario

You work at Rossmann Pharmaceuticals as a Machine Learning Engineer. The finance team
wants to forecast sales in all their stores across several cities six weeks ahead of time.
Managers in individual stores rely on their years of experience as well as their personal
judgement to forecast sales.

The data team identified factors such as promotions, competition, school and state holidays,
seasonality, and locality as necessary for predicting the sales across the various stores.

Your job is to build and serve an end-to-end product that delivers this prediction to analysts
in the finance team.

## Approach

The project is divided and implemented by the following phases

- Exploration of customer purchasing behavior
- Prediction of store sales
  - Machine learning approach
  - Deep Learning approach
- Serving predictions on a web interface

## Project Structure

The repository has a number of files including python scripts, jupyter notebooks, pdfs and text files. Here is their structure with a brief explanation.

### data:

- the folder where the dataset csv files are stored

### models:

- the folder where models' pickle files are stored

### notebooks:

- `EDA.ipynb`: a jupyter notebook for exploratory data analysisalgorithms

### scripts

- `app_logger.py`: a python script for logging
- `file_handler.py`: a python script for handling reading and writing of csv, pickle and other files
- `df_cleaner.py`: a python script for cleaning pandas dataframes
- `df_selector.py`: a python script for selecting data from a pandas dataframe
- `df_visualizer.py`: a python script for plotting selected data
- `df_outlier_handler.py`: a python script for cleaning outliers in a pandas dataframe

## Installation guide

```
git clone https://github.com/abu-bakarr/Pharmaceuticals-Sales-Prediction
cd Pharmaceuticals-Sales-Prediction
pip install -r requirements.txt
```
