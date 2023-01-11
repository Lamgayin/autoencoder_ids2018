## 環境
**OS system**：Windows 10  
**IDE**：vscode,Jupyter Notebook  
**python environment**：Anaconda  
**python version**： 3.7  
**pip requirement**：（run）pip install -r requirements.txt  

## 資料集下載地址
**因為資料集略大，所以上傳至gitlab可能會有問題**  
**ids2018：https://www.kaggle.com/datasets/solarmainframe/ids-intrusion-csv**

## 資料集下載後請參考下dataset的文件目錄

## 文件路徑說明
**（cmd中鍵入tree /f > list.txt 可以輸出文件目錄的樹結構）**  
│  document.md  **就是readme，對項目的一些說明**  
│  ids2018.ipynb   **ids2018 Dataset 資料前處理和模型訓練**  
│  requirements  **用於載入python環境的library** 
│  
├─checkpoint   **訓練時保存最好的權重**  
│  
├─dataset  **資料集**  
│  ├─CIC-IDS-2018-Dataset
│  │      combined_abnormal.csv **最後處理完的資料集，不包含正常** 
│  │      combined_normal.csv   **最後處理完的資料集，不包含異常**
│  │      Friday-02-03-2018_TrafficForML_CICFlowMeter.csv
│  │      Friday-16-02-2018_TrafficForML_CICFlowMeter.csv
│  │      Friday-23-02-2018_TrafficForML_CICFlowMeter.csv
│  │      Thuesday-20-02-2018_TrafficForML_CICFlowMeter.csv
│  │      Thursday-01-03-2018_TrafficForML_CICFlowMeter.csv
│  │      Thursday-15-02-2018_TrafficForML_CICFlowMeter.csv
│  │      Thursday-22-02-2018_TrafficForML_CICFlowMeter.csv
│  │      Wednesday-14-02-2018_TrafficForML_CICFlowMeter.csv
│  │      Wednesday-21-02-2018_TrafficForML_CICFlowMeter.csv
│  │      Wednesday-28-02-2018_TrafficForML_CICFlowMeter.csv
│          
└─model  **模型存放位置**  