# SentimentAnalysis．

目标: data里面有三个文本数据文件，neg.csv neutral.cav pos.csv 分别代表消极，中性和积极的三个情感分类。<br>
      要求实现一个分类器，对文本数据进行情感分析三分类。<br>

task1:分别统计三个情感极性中词频最高的5000个词汇(去除停顿词后，停顿词表在data目录小stop_words.csv文件内)，作为标记词<br>
      用一个文本中包含每个类别标记词最多的作为分类标准，建立分类模型。

task2:使用tf-idf对文本向量化，分别用svm和knn建立分类模型。

task3:使用随机词向量，用TextCNN建立文本分类模型

task4:使用随机词向量，多层LSTM建立分类模型

task5:借用已有的公开词向量数据再次完成task3和task4

task6:比较以上完成的多个模型泛华能力，完成总结
