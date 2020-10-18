# eeg-diagnosis
This code is released with NME and uses braindecode to test generalization of CNN on EEG anomaly detection as discussed in 
The NME Scalp EEG Dataset: An Open-SourceAnnotated Dataset of Healthy and PathologicalEEG Recordings for Predictive Modeling

## Requirements
1. Depends on https://robintibor.github.io/braindecode/ 
2. This code was programmed in Python 3.6 (might work for other versions also).

## Run
1. Modify config.py, especially correct data folders for your path..
2. Run with `python ./auto_diagnosis.py`
auto_diagnosis.py defines and train CNN models
diagnosis.py gives features from trained deep CNN
hybrid_lstm.py trains an LSTM model to classify sequence of features
##
