# NIX x-ray images classificaton

## About
We are using the NIH X-ray raw dataset from  NIH Clinical Center:
https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community
The code is inspired by the cat vs. dog image classificaton from the Machine Learning Crash Course by Google Developers:
https://developers.google.com/machine-learning/practica/image-classification/

## Setup
Setup Anaconda, pip, TensorFlow, Keras and Jupyter Notebook (executed in Ubuntu 18.04 LTS):
1.  Download Anaconda & install the .sh-file by terminal:          "bash filename.sh".
2.  Validate installation, start AnacondaNavigator:                "anaconda-navigator".
3.  Install pip depending on your Python Version:                  "conda install pip3".
4.  Install TF:                                                    "pip3 install --upgrade tensorflow".
5.  Install Keras: 	                                           "pip3 install Keras".
6.  Create TF instance:                                            "conda create -n tensorflow python=3.7".
7.  Install environment:                                           "conda install -c conda-forge tensorflow".
8.  Install jupyter notebook:                                      "conda install jupyter".
9.  Install pillow:                                                "conda install pillow".
10. Install SciPy:                                                 "conda install -c anaconda scipy".
11. Activate TF:                                                   "source activate tensorflow".

## Make 
12. Launch JN:                                                     "jupyter notebook".
13. Open file in JN:                                               "CNN.ipynb".

## TODO
1. Create Deep CNN, 
2. Droput Layer, 
3. less image downscaling (taget_size), 
4. transfer learning from InceptionV3 (cut at mixed7 layer), improve GPU (cuDNN for Nvidia). 
