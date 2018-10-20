# Rossmann Store Sales Project Report #
(from Kaggle Competition)

### Project description ###
Rossmann is a chain stores in Europe. And this project is from Kaggle competition [Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales). I need to predict Rossmann stores' sales according provided data, like the promotion, competition, holiday and etc.

## Requirements  ##
In this project, I use Python for data explore, visulization and featuring engineering. Python version is windows X64 3.5.5. And involved packages inlcude:
- Jupyter Notebook
- numpy 
- pandas
- seaborn
- matplotlib
- xgboost

## Run
1. To run this project, you should include sub directory: input. The Input directory has data downloaded from Kaggle and unzip to local: train.csv, test.csv.
2. In Jupyter Notebook to load “Rossmann Store project for report Eng.ipynb” and execute it. The executation time needs about 7 hours。
3. The result is "xgboost_rossman_submission.csv" and can be uploaded to Kaggle.

## Result

The result of local test set:
RMSPE: 0.109707

Kaggle Private Score
0.11518

Kaggle Public Score
0.11636
