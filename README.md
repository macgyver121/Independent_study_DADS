# Independent_study_DADS

## 1.Dataset

I have 2 folder containing dataset

1. The dataset before prepare and preprocssing
   
2. The dataset that ready for use in model

&emsp; 2.1 YouTube live comment Dataset (data_all.csv)

&emsp; 2.2 Wisesight Dataset (wsdata_all.csv)

## 2.Prepare data and preprocessing code

The code starting for ingest the raw data, prepared by delete the duplicate row, concatinate the dataset and preprocessing data.

The process for this step is following:

1. ingest_data_bypytchat.ipynb: the code for ingest Live comment Data from YouTube MorningNEWsTV3 by Pytchat
2. delete_duplicate_data.ipynb: the code for delete duplicate row with the same authorName and message
3. concatinate+preprocessing_data.ipynb: the code for concatinate and preprocessing in YouTube live comment dataset
4. concatinate+preprocessing_wsdata.ipynb: the code for concatinate and preprocessing in Wisesight dataset

## 3.Model for YouTube live comment Dataset
I have the example code for YouTube live comment Dataset in many model such as SVM, LSTM1layer, LSTM2layer and LSTM+NCP

## 4.Model for Wisesight Dataset
I have the example code for Wisesight Dataset in many model such as SVM, LSTM1layer, LSTM2layer and LSTM+NCP
