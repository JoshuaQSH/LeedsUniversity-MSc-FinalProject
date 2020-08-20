# LeedsUniversity-MSc-FinalProject
## MSc Project: Deep learning classification of ECG signals to diagnose heart disease
### Author: Shenghao Qiu
### 201341954 sc19sq

The preprocessed data can be downed from https://drive.google.com/file/d/1JhJrNgMxQrqHhLOiFMkzW9-PlelmQ7Is/view?usp=sharing <br>
file's name: challenge2017.pkl

To see the implementation of ResNet, please open the ./ECG/CinC_ECG_ResNet.ipynb file <br>
To see the implementation of LSTM and BiLSTM, please open the ./ECG/CinC_ECG_LSTM_BiLSTM.ipynb file <br>
To see the implementation of CRNN and CARNN (i.e. CRNN + Attention) please open the ./ECG/CinC_ECG_CRNN_CARNN.ipynb file <br>

#### Supplement and reference
The implementation of ResNet is referenced from https://github.com/fernandoandreotti/cinc-challenge2017/tree/master/deeplearn-approach <br>
The implementation of wavenet to augment the data is referenced from https://github.com/Dankrushen/Wavenet-PyTorch <br>
The attention model is illustrated in Multi-class Arrhythmia detection (https://www.sciencedirect.com/science/article/pii/S1566253518307632). <br>
The explaination part of the model is called LIME for CRANN. It refers to Lime-For-Time and can be illustrated in https://github.com/emanuel-metzenthin/Lime-For-Time/blob/master/doc/presentation.pdf <br>
