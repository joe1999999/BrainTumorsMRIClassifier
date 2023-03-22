# BrainTumorsMRIClassifier

## Brain Tumor Classification from MRI images.

Vast amounts of neuroimaging data is generated everyday around the world. This treasure of potential information and insight is waiting to be exploited by modern deep learning techniques. Experts (Neurosurgeons, Radiologists) aren't always present to interpret MRI scans, especially in countries with sub-optimal healthcare services (e.g. 3rd world countries). Hence the ever rising need for using machine learning techniques to build accurate neural networks that can help clinicians with making fast diagnosis reliably and therefore gaining valuable time in the context of optimal patient management and low resources. This is a very simple example of using 'Transfer Learning' on a small MRI images dataset containing 3 classes of brain tumors and a class representing normal brain images. The goal was to achieve acceptabe prediction accuracy.

![prediction screenshot](https://user-images.githubusercontent.com/39844459/227055889-0016b9f7-3c1b-4318-a689-7cee02c10eeb.png)

## Technical stuff
This is a jupyter notebook, feel free to tweak and expirement on it.
Tensorflow, Keras, OpenCV and various other python libraries are needed, make sure to 'pip install' all the dependencies before you start.
The best accuracy was achieved was 98.31% after 10 epochs of training.

![report](https://user-images.githubusercontent.com/39844459/227056678-cbffc4ad-d6a3-428b-a387-442204982520.png)

This is the trained model if you want to use it directly : 
https://drive.google.com/drive/folders/1-zqmjH6wuZhJmu5yRSK7bSlEx9UIUPiQ?usp=sharing

## The Dataset
I dataset i used to train this model is a combination between 2 different datasets acknowledged below.
Training data:
https://drive.google.com/drive/folders/19jxQMMKWK3-MKlzjyFQ3Q_2mDG3d8QXB?usp=sharing
Testing data:
https://drive.google.com/drive/folders/1oHwDB_0HNCwzhbt8mWyJLdA75CrWSid7?usp=sharing

##Sources

Acknowledgements for the Datasets I used: 

* Navoneel Chakrabarty and Swati Kanchan
https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

* Fernando Feltrin
https://www.kaggle.com/datasets/fernando2rad/brain-tumor-mri-images-17-classes


Inspiration: https://www.kaggle.com/code/jaykumar1607/brain-tumor-mri-classification-tensorflow-cnn
