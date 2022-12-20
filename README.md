# Data-Analysis-Google-Play-Store

This project analyzes apps in the Google Play Store to explore the current price strategies of the apps.

The findings of the analysis are discussed in this blog-post: https://medium.com/@ivanadaskalovska/how-much-should-i-charge-for-my-android-app-e970f5d7ec3d

## Installation

You can install this repository on your pc by using:
```
git clone git@github.com:Ivana-DS/Data-Analysis-Google-Play-Store.git
```
Python version: 3.8.10

Jupyter Notebook version: 6.4.6

You also need to install the requirements file:
```
pip install -r requirements.txt
```

And download the dataset:

```
wget https://github.com/Ivana-DS/Data-Analysis-Google-Play-Store/releases/download/dataset/Google-Playstore.csv
```

## Files

1. Analysing_Google_Play_Store_Apps.ipynb: The jupyter notebook which contains the cleaning process and the analyses made on the Google Playstore Dataset
2. Google-Playstore.csv : The data set used for the analysis. If you are interested in more details you can find the data set here: https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps
3. requirements.txt: Contains all the libraries needed to work with this project. 

## Usage

After installing the requirements you just have to start Jupyter Notebook in your bash by using:
```
jupyter-notebook
```

## Summary of results

The most of the Apps in Google Play Store are free of charge or very cheap (under 10$). The apps are usually using secondary revenue streams, like advertisements or in-app purchases to finance the app.