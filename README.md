# README

# Address data set

[secanter/Plant-morphology-of-Chinese-herbal-medicine: 中草药植物形态数据集 (github.com)](https://github.com/secanter/Plant-morphology-of-Chinese-herbal-medicine)

## Folder structure

|--./DataSet
 &nbsp;|--Xanthum mongolicum kitag
   &nbsp;|--Viola philippica Car
  &nbsp; |--Semen Ginkgo
  &nbsp; |--Schisandra chinensis-(Turcz.)Baill
  &nbsp; |--Rhizoma Curcumae
   &nbsp;|--Radix Platycodonis
  &nbsp; |--Plantagodepressa Willd
 &nbsp;  |--Lysimachia christinae Hance
  &nbsp; |--Leonurush-eterophyllu-sSweet
 &nbsp;  |--Houttuynia cordata Thunb
 &nbsp;  |--Herba Menthae Haplocalycis
 &nbsp;  |--Herba Chelidonii
  &nbsp; |--FRUCTUS LYCII
 &nbsp;  |--FRUCTUS HIPPOPHAE
  &nbsp; |--Crocus sativus
  &nbsp; |--Benzoinum Styracis
  &nbsp; |--Artemisia annua L
 &nbsp; |--Agrimonia pilosa Ledeb



# Use of models

## machine learning

### SVM

- Copy all folders under DataSet to **data** folder.
- Execute **main.py**

### knn

- Copy all folders under DataSet to **data** folder.
- Execute **knn.py**

## Deep learning

### AlexNet

- Copy all folders under DataSet to **data_name** folder.
- First Execute **split.py**
- Second Execute **train.py**
- Finally Execute **test.py** to check the model accuracy.

### ResNet

- The data set can be divided into training set and testing set according to the ratio of 9: 1.
- separately Copy them to **train** folder and **val** folder .
- Execute **train.py**
- You can Execute **predict.py** to check the model accuracy.

### VGG16

- The data set can be divided into training set and testing set according to the ratio of 9: 1.
- separately Copy them to **train** folder and **val** folder .
- Execute **train.py**
- You can Execute **predict.py** to check the model accuracy.

### ViT

- Copy all folders under DataSet to **data_name** folder.
-  Execute **train.py**
- You can Execute **predict.py** to check the model accuracy.