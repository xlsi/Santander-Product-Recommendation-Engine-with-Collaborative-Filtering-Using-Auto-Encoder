# Santander Product Recommendation Engine with Deep Learning
Using the Santander dataset (data can be downloaded from https://www.kaggle.com/competitions/santander-product-recommendation/data)
, implemented Auto Encoder (AE), Variational Auto Encoder (VAE), to fill in the scoring matrix, and then make recommendations to users.

代码建议在**Google Colab**环境下运行，代码中的目录请根据自己的实际目录进行修改。  

本代码主目录和子目录如下：  

/content/drive/Movie_lens/  
--------- ml-1m (包含数据集的文件夹)  
--------- auto encoder.ipynb  
--------- BERT-based-recommender.ipynb  

## **1 Models:**

### 1.1 Auto Encoder
<img src="https://github.com/YJiangcm/Movielens1M-Movie-Recommendation-System/blob/main/pictures/auto%20encoder.png" width="400" height="300">

### 1.2 Variational Auto Encoder
<img src="https://github.com/YJiangcm/Movielens1M-Movie-Recommendation-System/blob/main/pictures/variational%20auto%20encoder.png" width="400" height="300">

### 1.3 BERT-based
<img src="https://github.com/YJiangcm/Movielens1M-Movie-Recommendation-System/blob/main/pictures/bert-based.PNG" width="600" height="300">

## **2 Experimental Results:**

### 2.1 MSE of training loss and validation loss of Auto Encoder
<img src="https://github.com/YJiangcm/Movielens1M-Movie-Recommendation-System/blob/main/pictures/auto%20encoder%20result.png" width="460" height="280">

### 2.2 MSE of training loss and validation loss of Variational Auto Encoder
<img src="https://github.com/YJiangcm/Movielens1M-Movie-Recommendation-System/blob/main/pictures/variational%20auto%20encoder%20result.png" width="450" height="280">

### 2.3 MSE of training loss and test loss of BERT-based
<img src="https://github.com/YJiangcm/Movielens1M-Movie-Recommendation-System/blob/main/pictures/bert-based%20result.png" width="800" height="300">

### 2.4 test MSE loss of different models
 Model | test MSE loss  
 ---- | -----  
 Auto Encoder  | 1.0837
 Variational Auto Encoder  | 0.9956
 BERT-based  | **0.7507**
  
   
## LICENSE
Please refer to [MIT License Copyright (c) 2020 YJiangcm](https://github.com/YJiangcm/Movielens1M-Movie-Recommendation-System/blob/main/LICENSE)
