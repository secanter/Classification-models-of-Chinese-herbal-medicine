# README

# Address data set

[secanter/Plant-morphology-of-Chinese-herbal-medicine: 中草药植物形态数据集 (github.com)](https://github.com/secanter/Plant-morphology-of-Chinese-herbal-medicine)

## Folder structure

|--./DataSet
   |--Xanthum mongolicum kitag
   |--Viola philippica Car
   |--Semen Ginkgo
   |--Schisandra chinensis-(Turcz.)Baill
   |--Rhizoma Curcumae
   |--Radix Platycodonis
   |--Plantagodepressa Willd
   |--Lysimachia christinae Hance
   |--Leonurush-eterophyllu-sSweet
   |--Houttuynia cordata Thunb
   |--Herba Menthae Haplocalycis
   |--Herba Chelidonii
   |--FRUCTUS LYCII
   |--FRUCTUS HIPPOPHAE
   |--Crocus sativus
   |--Benzoinum Styracis
   |--Artemisia annua L
   |--Agrimonia pilosa Ledeb



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

### VGG16

- The data set can be divided into training set and testing set according to the ratio of 9: 1.
- separately Copy them to **train** folder and **val** folder .
- Execute **train.py**
- Finally Execute **test.py** to check the model accuracy.

### ViT

- Copy all folders under DataSet to **data_name** folder.
-  Execute **train.py**
- You can Execute **predict.py** to check the model accuracy.