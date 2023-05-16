# Santander Product Recommendation Engine with Deep Learning
Using the Santander dataset (data can be downloaded from https://www.kaggle.com/competitions/santander-product-recommendation/data)
, implemented Auto Encoder (AE), Variational Auto Encoder (VAE), to fill in the scoring matrix, and then make recommendations to users.

It is recommended to run the code in **Google Colab** environment, please modify the directory in the code according to your actual directory. 

The main directory and files of this code are as follows:

--------- data (folder containing datasets)  
--------- train_and_test_set_preparation.ipynb  
--------- recommendation_engine_with_collaborative_filtering_using_auto_encoder.ipynb  

## **1 Models:**

### 1.1 Auto Encoder
<img src="https://github.com/xlsi/Santander-Product-Recommendation-Engine-with-Collaborative-Filtering-Using-Auto-Encoder/blob/main/pictures/auto%20encoder.png" width="400" height="300">

### 1.2 Variational Auto Encoder
<img src="https://github.com/xlsi/Santander-Product-Recommendation-Engine-with-Collaborative-Filtering-Using-Auto-Encoder/blob/main/pictures/variational%20auto%20encoder.png" width="400" height="300">


## **2 Experimental Results:**

### 2.1 MSE of training loss and validation loss of Auto Encoder
<img src="https://github.com/xlsi/Santander-Product-Recommendation-Engine-with-Collaborative-Filtering-Using-Auto-Encoder/blob/main/pictures/auto%20encoder%20result.png" width="460" height="280">

### 2.2 MSE of training loss and validation loss of Variational Auto Encoder
<img src="https://github.com/xlsi/Santander-Product-Recommendation-Engine-with-Collaborative-Filtering-Using-Auto-Encoder/blob/main/pictures/variational%20auto%20encoder%20result.png" width="450" height="280">



### 2.3 Hit Ratio of different models
 Model | Hit Ratio (n_recommend = 10)
 ---- | -----  
 Auto Encoder  | **0.53**
 Variational Auto Encoder  | 0.37
