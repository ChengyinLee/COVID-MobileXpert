Overview
----
This repository is a PyTorch implementation of the paper "COVID-Xpert: An AI Powered Population Screening of COVID-19 Cases Using Chest Radiography Images".

Dataset
-----
The ChestXray8 cases are available [here](https://nihcc.app.box.com/v/ChestXray-NIHCC).  
The COVID cases are available [here](https://github.com/ieee8023/covid-chestxray-dataset).  
The normal and pneumonia cases are available [here](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge).


COVID-Xpert Architecture
----
![](readme/transfer_learning.PNG)

Some Results
----
Longitudinal XCR images of a patient over the four time points.  

![](readme/one_patient.PNG)



Models
----
The model weights are available [here](https://drive.google.com/drive/folders/1AUtsxjPNVJiTboFFTzzqyeCKBPvMxbII?usp=sharing).  
You can test your own image by:
```
python testing.py --image <X-ray path>
```

Thumbnail of Generated Heatmaps
-----
![](readme/heatmap.PNG)




Dependencies
-----
* Python 3.7
* Pytorch 0.4.0


