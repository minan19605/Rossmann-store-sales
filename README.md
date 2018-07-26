{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Rossmann Store Sales Project Report #\n",
    "(from Kaggle Competition)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### 项目描述 ###\n",
    "Rossmann是欧洲的一家连锁药店。 在这个源自Kaggle比赛[Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales)中，我们需要根据Rossmann药妆店的信息（比如促销，竞争对手，节假日）以及在过去的销售情况，来预测Rossmann未来的销售额。"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Requirements  ##\n",
    "项目中我使用Python语言进行数据探索、可视化和特征工程等工作，Python 的版本是windows X64 3.5.5。涉及的主要软件包有：\n",
    "- Jupyter Notebook\n",
    "- numpy \n",
    "- pandas\n",
    "- seaborn\n",
    "- matplotlib\n",
    "- xgboost"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Run\n",
    "1. 运行本项目应该包含以下子目录: input。Input目录下是从Kaggle网站下载并本地解压的文件train.csv, store.csv, test.csv.\n",
    "2. 在Jupyter Notebook 中加载“Rossmann Store project for report.ipynb”并直接执行。全部执行完成需要7个小时左右。\n",
    "3. 生成的用于提交Kaggle的结果文件名为“xgboost_rossman_submission.csv”\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Result\n",
    "\n",
    "本地测试集的结果：\n",
    "RMSPE: 0.109707\n",
    "\n",
    "Kaggle Private Score\n",
    "0.11518\n",
    "\n",
    "Kaggle Public Score\n",
    "0.11636"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.5.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
