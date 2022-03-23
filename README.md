# 文件执行方法

MLPClassify.ipynb仅需要sklearn以及pytorch包即可，打开文件后全部运行即可。

TextCNNClassify.ipynb需要安装spaCy库以及其英文预料包，可以参见[Install spaCy · spaCy Usage Documentation](https://spacy.io/usage)官网下载，也是打开文件后全部运行即可。

EnsembleClassify为集成模型，其中训练了以上两个模型，并进行了整合，打开后全部运行即可。

运行文件后会在**exp1data**文件夹中生成三个output文件：mlpoutput.txt, textcnnoutput.txt, ensembleoutput.txt，且在**output**文件夹中有我已经预测好的测试集，可以进行对比。