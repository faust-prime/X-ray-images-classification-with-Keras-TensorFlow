# NIH x-ray images classification

## About
We are using the NIH X-ray raw dataset at [NIH Clinical Center](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community). The code is inspired by the cat vs. dog image classificaton at [Machine Learning Crash Course by Google Developers](https://developers.google.com/machine-learning/practica/image-classification/).


## Requirements
Tested in Ubuntu Linux and Mac-OS:

1. Download and install Anaconda,
2. Start Anaconda Navigator,
3. Create TensorFlow environment (Tab "Environments"),
4. Select TensorFlow environment and install: keras, tensorflow, matplotlib, nomkl and pillow,
5. Install Jupyter Notebook (Tab "Home").


## Run
1. Activate TF environment (Tab "Environments"),
2. Launch Jupyter Notebook (Tab "Home"),
3. Open "CNN.ipynb"-file in Jupyter Notebook Browser-Tab and run all cells starting at the top.


## Improve
1. Create Deep CNN (more layers),
2. Add different Dropout layers, 
3. Less image-downscaling (variable: target_size), 
4. Create Transfer learning CNN from InceptionV3 by cutting at "mixed7" layer,
5. Use data augmentation,
6. Play with train/validation split.
