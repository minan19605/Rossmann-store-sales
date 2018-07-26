# Rossmann-store-sales
Udacity Machine Learning Nano Degree Capstone project

# Rossmann Store Sales Project Report #
(from Kaggle Competition)

### 项目描述 ###
Rossmann是欧洲的一家连锁药店。 在这个源自Kaggle比赛[Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales)中，我们需要根据Rossmann药妆店的信息（比如促销，竞争对手，节假日）以及在过去的销售情况，来预测Rossmann未来的销售额。

## Requirements  ##
项目中我使用Python语言进行数据探索、可视化和特征工程等工作，Python 的版本是windows X64 3.5.5。涉及的主要软件包有：
- Jupyter Notebook
- numpy 
- pandas
- seaborn
- matplotlib
- xgboost

## Run
1. 运行本项目应该包含以下子目录: input。Input目录下是从Kaggle网站下载并本地解压的文件train.csv, store.csv, test.csv.
2. 在Jupyter Notebook 中加载“Rossmann Store project for report.ipynb”并直接执行。全部执行完成需要7个小时左右。
3. 生成的用于提交Kaggle的结果文件名为“xgboost_rossman_submission.csv”

## Result

本地测试集的结果：
RMSPE: 0.109707

Kaggle Private Score
0.11518

Kaggle Public Score
0.11636
