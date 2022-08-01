# FASHION RECOMMENDATION


## INTRODUCTION
Recommender systems are used in organizations like Netflix, YouTube, and Amazon. The systems lure customers with pertinent recommendations based on their selections.
Here, we use a fashion-based recommendation algorithm, which encompasses both attire and accessories.

## AIM
Our goal was to design a user interface (UI) where a user could upload a specific article of apparel or accessory and the computer would suggest 5 items that looked similar. This process is called reverse image search. Most of the ecommerce industry uses this technique and is a very powerful technique. 

## MECHANISM
1. Convolutional Neural Network is a specialized neural network designed for visual data, such as images & videos. But CNNs also work well for non-image data (especially in NLP & text classification).

2. The neural networks are trained using transfer learning from ResNet50 after the data has been pre-processed. In order to fine-tune the network model to address the current issue, more layers are included in the final layers that replace the architecture and weights from ResNet50. The ResNet50 architecture is depicted in the figure.
![image](https://user-images.githubusercontent.com/93417245/182053497-de929fb2-8a45-43cc-8cf9-c27ec8d64f3a.png)


## INVENTORY  DATA SAMPLE SET
![image](https://user-images.githubusercontent.com/93417245/182053675-ed8bbdda-a2e8-4485-809f-2a90613c5bd0.png)


## DATASET LINK
1. Kaggle Dataset Big size 15 GB

2. Kaggle Dataset Small size 572 MB


## PLAN OF ATTACK

1. Import Model
2. Extract Features
3. Exporting the Features
4. Generate recommendation


## UI

