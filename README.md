# README

# Address data set

[secanter/Plant-morphology-of-Chinese-herbal-medicine: 中草药植物形态数据集 (github.com)](https://github.com/secanter/Plant-morphology-of-Chinese-herbal-medicine)

## Folder structure

|--./DataSet</br>
 &nbsp;|--Xanthum mongolicum kitag</br>
   &nbsp;|--Viola philippica Car</br>
  &nbsp; |--Semen Ginkgo</br>
  &nbsp; |--Schisandra chinensis-(Turcz.)Baill</br>
  &nbsp; |--Rhizoma Curcumae</br>
   &nbsp;|--Radix Platycodonis</br>
  &nbsp; |--Plantagodepressa Willd</br>
 &nbsp;  |--Lysimachia christinae Hance</br>
  &nbsp; |--Leonurush-eterophyllu-sSweet</br>
 &nbsp;  |--Houttuynia cordata Thunb</br>
 &nbsp;  |--Herba Menthae Haplocalycis</br>
 &nbsp;  |--Herba Chelidonii</br>
  &nbsp; |--FRUCTUS LYCII</br>
 &nbsp;  |--FRUCTUS HIPPOPHAE</br>
  &nbsp; |--Crocus sativus</br>
  &nbsp; |--Benzoinum Styracis</br>
  &nbsp; |--Artemisia annua L</br>
 &nbsp; |--Agrimonia pilosa Ledeb</br>



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