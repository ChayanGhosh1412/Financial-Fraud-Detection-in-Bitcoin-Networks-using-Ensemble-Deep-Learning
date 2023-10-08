# Financial-Fraud-Detection-in-Bitcoin-Networks-using-Ensemble-Deep-Learning

<h1>Abstract</h1> <br>

<li>This code is a part of our paper on “Enhancing Financial Fraud Detection in Bitcoin Networks using Ensemble Deep Learning” that introduces an innovative approach to bolster financial fraud detection within the Bitcoin network using ensemble deep learning models.​</ol>
<li>Although deep learning models have been employed in the past for the detection of fraud, this study develops an ensemble of deep learning models (MLP, FNN, and Attention LSTM).​</li>
<li>Meticulous data preprocessing and feature engineering using SMOTE and normalization are conducted to prepare the dataset for training.​</li>
<li>Our ensemble model demonstrates remarkable performance, surpassing individual models with an accuracy of 99.62%, exceptional precision, and recall values exceeding 99%.​</li>
<li>These outcomes validate the ensemble's capacity to detect both fraudulent and legitimate transactions with unprecedented accuracy, fostering trust in digital transactions. </li>


<h1>Methodology​ </h1><br>

The model includes the following processes:​
<li>Obtaining the Bitcoin Network Transactional Metadata dataset from Kaggle, which contains transactional data. ​</li>
<li>Handling the class imbalance by using Synthetic Minority Over-sampling Technique (SMOTE) to generate synthetic samples for the minority class.​</li>
<li>Normalizing the data to a range of 0 to 1 to ensure consistent scaling of features.​</li>
<li>Dividing the preprocessed data into training and testing sets using an 80:20 split ratio.​</li>
<li>Training various machine learning algorithms for the ensemble model</li>
<li>Create a stacking model to combine the predictions from different base models.​ </li>
<li>Test the ensemble model on the testing dataset to assess its performance in predicting blockchain fraud.​ </li>

![method](https://github.com/AvigyanChowdhury/Financial-Fraud-Detection-in-Bitcoin-Networks-using-Ensemble-Deep-Learning/assets/146307887/89e42d68-0fc5-4aa8-a874-b32efd270e40)


<h1>Dataset</h1><br>

<li>Contains information on over 4 million Bitcoin transactions​</li>
<li>​Includes information on transaction IDs, timestamps, input and output addresses, input and output amounts, and transaction fees.​</li>
<li>Includes a variety of features that can be used to detect fraudulent transactions, such as the number of inputs and outputs per transaction, the total input and output amounts, the transaction size, and the transaction age​</li>
<li>Includes a label for each transaction, indicating whether or not it is fraudulent​​</li>

<a href="https://www.kaggle.com/datasets/omershafiq/bitcoin-network-transactional-metadata">Original Dataset can be found here </a>



  
