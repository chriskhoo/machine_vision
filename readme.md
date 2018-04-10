# Name this expression
A Computer Vision Project predicting emotions based on images of facial expressions.

Author: Christopher Khoo

Project: Springboard Capstone Project 2

------
## Summary
This report guides the reader through the development of a facial expressions (limited to neutral, happy, sad, contempt, surprise, anger, and disgust) classifier. A practical application of the classifier is its use in games on mobile or web applications to assist in developing practicing social skills of children with autism in environments with less pressure.

The final model achieved an accuracy of ~91%. Whilst this level of accuracy might be insufficient for a fully automated labelling system, flagging ambiguous images for manual labelling could provide a very workable compromise of a computer aided solution.

This reports covers aspects of data acquisition from the CK+ dataset, facial image processing and the training and evaluation of KNN and CNN classification models.

The project uses OpenCV for the image processing and Keras’ deep learning for the model.

The raw data (CK+ dataset) maybe be found [here](http://www.consortium.ri.cmu.edu/ckagree/).

------
## Contents of repository
- [Final Report](https://github.com/chriskhoo/machine_vision/blob/master/11_Writeup/04_FinalReport.pdf)
- Jupyter Notebooks:
  - [Data exploration](https://github.com/chriskhoo/machine_vision/blob/master/21_Jupyter_notebooks/01_data_exploration.ipynb)
  - [Image processing](https://github.com/chriskhoo/machine_vision/blob/master/21_Jupyter_notebooks/02_image_processing.ipynb)
  - [Data Wrangling](https://github.com/chriskhoo/machine_vision/blob/master/21_Jupyter_notebooks/03_data_wrangling.ipynb)
  - [KNN Classification](https://github.com/chriskhoo/machine_vision/blob/master/21_Jupyter_notebooks/04_knn_classification.ipynb)
  - [CNN Classification](https://github.com/chriskhoo/machine_vision/blob/master/21_Jupyter_notebooks/05_cnn_classification.ipynb)
  - [Data wrangling miniset](https://github.com/chriskhoo/machine_vision/blob/master/21_Jupyter_notebooks/06_data_wrangling_miniset.ipynb)
  - [CNN Classification miniset](https://github.com/chriskhoo/machine_vision/blob/master/21_Jupyter_notebooks/07_cnn_classification_mini.ipynb)
