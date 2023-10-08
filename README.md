# Financial-Fraud-Detection-in-Bitcoin-Networks-using-Ensemble-Deep-Learning
<h1>Abstract</h1> <br>
<li>
  <ol>This code ia a part of our paper on “Enhancing Financial Fraud Detection in Bitcoin Networks using Ensemble Deep Learning” introduces an innovative approach to bolster financial fraud detection within the Bitcoin network using ensemble deep learning models.​</ol>
<ol>Although deep learning models have been employed in the past for the detection of fraud, this study develops an ensemble of deep learning models (MLP, FNN, and Attention LSTM).​</ol>
<ol>Meticulous data preprocessing and feature engineering using SMOTE and normalization are conducted to prepare the dataset for training.​</ol>
<ol>Our ensemble model demonstrates remarkable performance, surpassing individual models with an accuracy of 99.62%, exceptional precision, and recall values exceeding 99%.​</ol>
<ol>These outcomes validate the ensemble's capacity to detect both fraudulent and legitimate transactions with unprecedented accuracy, fostering trust in digital transactions. ​</ol>
</li>

<h1>Methodology​ </h1><br>
<li>
The model includes the following processes:​
<ol>Obtaining the Bitcoin Network Transactional Metadata dataset from Kaggle, which contains transactional data​ </ol>
<ol>Handling the class imbalance by using Synthetic Minority Over-sampling Technique (SMOTE) to generate synthetic samples for the minority class.​ </ol>
<ol>Normalizing the data to a range of 0 to 1 to ensure consistent scaling of features.​ </ol>
<ol>Dividing the preprocessed data into training and testing sets using an 80:20 split ratio.​ </ol>
<ol>Training various machine learning algorithms for the ensemble model​ </ol>
<ol>Create a stacking model to combine the predictions from different base models.​ </ol>
<ol>Test the ensemble model on the testing dataset to assess its performance in predicting blockchain fraud.​ </ol>
</li>
![method](https://github.com/AvigyanChowdhury/Financial-Fraud-Detection-in-Bitcoin-Networks-using-Ensemble-Deep-Learning/assets/146307887/89e42d68-0fc5-4aa8-a874-b32efd270e40)

<a href="https://www.kaggle.com/datasets/omershafiq/bitcoin-network-transactional-metadata">Original Dataset can be found here </a>



  
