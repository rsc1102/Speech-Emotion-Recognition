# Speech-Emotion-Recognition
This repository if for Speech Emotion Recognition on [Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio) dataset using Pytorch. The dataset is available on the Kaggle page.
This repository contains three jupyter notebooks.
* creating_labels.ipynb
* create_MFCC_dictionary.ipynb
* MAIN.ipynb

The first two notebooks are for preprocessing of the RAVDESS dataset. The notebook titled 'MAIN' is for creating the model and training.

# Observations

## Results after training for 50 epochs:
* Maximum training accuracy = 93.67 %
* Maximum validation accuracy = 70.42 %
* Maximum validation f1 accuracy = 73.67 %
## Graphs:
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/Loss_graph.JPG)
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/accuracy_graph.JPG)
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/f1_accuracy_graph.JPG)
## Confusion matrices with maximum f1 accuracy:
### Validation confusion matrix
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/val_confusion_matrix.JPG)
### Training confusion matrix
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/train_confusion_matrix.JPG)
# Requirements
* audioread==2.1.8
* backcall==0.1.0
* certifi==2019.9.11
* cffi==1.13.1
* cycler==0.10.0
* decorator==4.4.1
* ipython==7.9.0
* ipython-genutils==0.2.0
* jedi==0.15.1
* joblib==0.13.2
* kiwisolver==1.1.0
* librosa==0.7.1
* llvmlite==0.30.0
* matplotlib==3.1.1
* mkl-fft==1.0.14
* mkl-random==1.1.0
* mkl-service==2.3.0
* numba==0.46.0
* numpy==1.17.2
* pandas==0.25.2
* parso==0.5.1
* patsy==0.5.1
* pexpect==4.7.0
* pickleshare==0.7.5
* prompt-toolkit==2.0.10
* ptyprocess==0.6.0
* pycparser==2.19
* Pygments==2.4.2
* pyparsing==2.4.2
* python-dateutil==2.8.0
* pytz==2019.3
* resampy==0.2.2
* scikit-learn==0.21.3
* scipy==1.3.1
* seaborn==0.9.0
* six==1.12.0
* SoundFile==0.10.2
* statsmodels==0.10.1
* torch==1.3.0
* tornado==6.0.3
* tqdm==4.36.1
* traitlets==4.3.3
* wcwidth==0.1.7


# Citation:
*  "The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)" by Livingstone & Russo is licensed under CC BY-NA-SC 4.0

