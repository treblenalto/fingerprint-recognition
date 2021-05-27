# Fingerprint Recognition

## Overview
Fingerprint image classification using Random Forest, Catboost, and CNN 

## Data

**Training Dataset** 
* 80 images: 10 images per person, 8 people
* label: first number of file name (ex '1 (1)bmp' -> fingerprint of person 1)
  ![trainset-image](https://github.com/Taehee-K/Fingerprint-Recognition/blob/main/train.png)

**Test Dataset**
* 80 images, without label
  ![tesetset-image](https://github.com/Taehee-K/Fingerprint-Recognition/blob/main/test.png)

## Model
* **Random Forest Classifier**
* **Catboost Classifier**
* **Convolutional Neural Net**

## Structure
```
Fingerprint Recognition
├── README.md
├── code
│   ├───fingerprint_cb.ipynb
│   ├───fingerprint_cnn.ipynb
│   └───fingerprint_rf.ipynb
│
├── data
│   ├───test
│   └───train
│   
├── model
│   ├───model_cb.pkl
│   ├───model_cnn.h5
│   └───model_rf.pkl
│
├── result
│   ├───result_cb.csv
│   ├───result_cnn.csv
│   └───result_rf.csv 
│   
```