# NIH x-ray images classificaton

## About
We are using the NIH X-ray raw dataset at [NIH Clinical Center](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community). The code is inspired by the cat vs. dog image classificaton at [Machine Learning Crash Course by Google Developers](https://developers.google.com/machine-learning/practica/image-classification/).


## Setup Anaconda, TensorFlow, Keras and JupyterNotebook
Tested in Ubuntu Linux and Mac-OS.

1. Download and install Anaconda   "Linux terminal: bash filename.sh",
2. Start Anaconda-Navigator:       "Linux terminal: anaconda-navigator",
3. Create TF environment (Tab "Environments") or multiple for GPU-configurations,
4. Select TF environment and Install keras, tensorflow, matplotlib, nomkl and pillow unsing the "Search Packages" field,
5. Install Jupyter Notebook (Tab "Home").


## Launch
1. Activate TF environment in (Tab "Environments"),
2. Launch JN (Tab "Home"),
3. Open "CNN.ipynb"-file in Jupyter Notebook.


## Improve
1. Create Deep CNN,
2. add Droput Layer, 
3. Less image-downscaling (variable: target_size) depending on machine, 
4. Create Transfer learning CNN from InceptionV3 by cutting at "mixed7" layer. 
