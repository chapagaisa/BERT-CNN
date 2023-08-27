# BERT-CNN

### Predicting Linguistically Sophisticated Social Determinants of Health Disparities with Neural Networks: The Case of LGBTQ+ Minority Stress

![BERT_CNN_ARC](https://github.com/chapagaisa/BERT-CNN/assets/46834070/6d5a2448-9f5d-41ce-9d09-83fc5ed75479)

  Fig: BERT-CNN network architecture for multi-label classification.

### Dependencies
The models has been tested in Google Colab which has Python Version of 3.10.12, with following required packages: <br>
1. torch==2.0.1
2. transformer==4.30.2
3. torchtext==0.6
4. numpy==1.22.4 
5. pandas==1.5.3

### Instructions
Step1: Due to Ethical concerns datasets are not made public. However, you can test the model with any datasets (Movie Review, Book Review, etc.) that is publicly available. <br>
Step2: Install dependencies using terminal "pip install -r requirements.txt". If you wish to use .ipynb file in google colab, dependencies are included in the file. <br>

### Files
1. AblationStudy_BERTONLY.ipynb: Contains BERT and a linear layer for the ablation study.
2. AblationStudy_CNNONLY.ipynb: CNN with pre-trained (GloVe) word embeddings for the ablation study.
3. BERT_CNN.ipynb: Proposed model.
4. Baseline_BiLSTM.ipynb: BiDirectional LSTM as a baseline model.
5. Baseline_RNN.ipynb: Vanilla RNN model as a baseline model.
6. Baseline_ML.ipynb: It contains the code for Random Forest and Support Vector Machine (SVM) as baseline models
