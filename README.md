# BrainTumoursMRIClassifier
## A Brain Tumors Classification using MRI images.

Vast amounts of neuroimaging data is generated everyday around the world. This treasure of potential information and insight is waiting to be exploited by modern deep learning techniques. Experts (Neurosurgeons, Radiologists) aren't always present to interpret MRI scans, especially in countries with sub-optimal healthcare services (e.g. 3rd world countries). Hence the ever rising need for using machine learning techniques to build accurate neural networks that can help clinicians with making fast diagnosis reliably and therefore gaining valuable time in the context of optimal patient management and low resources. This is a very simple example of using 'Transfer Learning' on a small MRI images dataset containing 3 classes of brain tumors and a class representing normal brain images. The goal was to achieve acceptabe prediction accuracy.

## Technical stuff
This is a notebook containing commented code, feel free to tweak it.
Tensorflow, Keras, OpenCV and various other python libraries were used, make sure to pip install all the dependencies before you start.
The best accuracy was achieved after 12 epochs of training was ~98%.
Images were scaled down to 150px by 150px.
The subfolder '/checkpoint' contains the final model's weights that you can load into your own built module etc ...
  

Acknowledgements for the Dataset used for the training:
Navoneel Chakrabarty
Swati Kanchan

Dataset:https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri?resource=download
Inspiration: https://www.kaggle.com/code/jaykumar1607/brain-tumor-mri-classification-tensorflow-cnn
