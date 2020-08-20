# LeedsUniversity-MSc-FinalProject
## MSc Project: Deep learning classification of ECG signals to diagnose heart disease
#### Author: Shenghao Qiu
#### 201341954 sc19sq

### Introduction
This project is the MSc final project of achieving ECG recordings classification. The electrocardiogram (ECG) is the standard non-invasive exam for the first diagnosis of possible heart disease. It is based on leads attached to the torso that record electrical potentials emanating from the heart as it contracts. These signals are then analysed visually by the clinician. Accurate differential diagnosis of various arrhythmias from just the ECG requires expertise as the signals vary based on the anatomy and positioning of the leads, as well as from beat-to-beat, and much research has been conducted in the past to automate feature extraction and diagnosis of ECG signals based on machine learning. However, the performance of the traditional machine learning recognition algorithm is not satisfactory. Even if the deep learning algorithm was used, it only improved the accuracy of Atrial Fibrillation (AF) recognition. There are still many shortcomings in the implementation process. <br> 

The goal of this project is to develop a hybrid deep learning model to classify the normal signals and AF signals in order to diagnose the cardiac arrhythmia. To be specific, there are multiplestepsincluding: <br>

1. Find an appropriate dataset as training and testing dataset. Make sure the data are labeled byexperts. <br>
2. Dothedatapre-processingand augmentationif necessary. <br>
3. Explore andfind aacceptable model todotheclassification. <br>
4. Explainand evaluate themodelin aproper way.<br>

The preprocessed data can be downloaded from https://drive.google.com/file/d/1JhJrNgMxQrqHhLOiFMkzW9-PlelmQ7Is/view?usp=sharing <br>
File's name: challenge2017.pkl <br>

To see the implementation of ResNet, please open the ./ECG/CinC_ECG_ResNet.ipynb file <br>
To see the implementation of LSTM and BiLSTM, please open the ./ECG/CinC_ECG_LSTM_BiLSTM.ipynb file <br>
To see the implementation of CRNN and CARNN (i.e. CRNN + Attention) please open the ./ECG/CinC_ECG_CRNN_CARNN.ipynb file <br>

### Supplement and reference
The implementation of ResNet is referenced from https://github.com/fernandoandreotti/cinc-challenge2017/tree/master/deeplearn-approach <br>
The implementation of wavenet to augment the data is referenced from https://github.com/Dankrushen/Wavenet-PyTorch <br>
The attention model is illustrated in Multi-class Arrhythmia detection (https://www.sciencedirect.com/science/article/pii/S1566253518307632). <br>
The explaination part of the model is called LIME for CRANN. It refers to Lime-For-Time and can be illustrated in https://github.com/emanuel-metzenthin/Lime-For-Time/blob/master/doc/presentation.pdf <br>
