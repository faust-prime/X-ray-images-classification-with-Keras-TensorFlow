# NIH ChestXray14 image classification

## About
We are using the ChestXray14 raw chest x-ray dataset at [NIH Clinical Center](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community). The code is inspired by the cat vs. dog image classificaton at [Machine Learning Crash Course by Google Developers](https://developers.google.com/machine-learning/practica/image-classification/).


## Requirements
Tested in Ubuntu 18.04.1 and MacOS:

1. Download image data from [ChestXray14 source](https://nihcc.app.box.com/v/ChestXray-NIHCC) and decompress,
2. Download and install Anaconda,
3. Start Anaconda Navigator,
4. Create TensorFlow environment (Tab "Environments"),
5. Select TensorFlow environment and install: keras, tensorflow, matplotlib, nomkl and pillow,
6. Install Jupyter Notebook (Tab "Home").


## Run
1. Activate TF environment (Tab "Environments"),
2. Launch Jupyter Notebook (Tab "Home"),
3. Open "CNN.ipynb"-file inside the Jupyter Notebook and run all cells starting at the top.


## Improve
1. Create Deep CNN (more layers),
2. Add different Dropout layers, 
3. Less image-downscaling (variable: target_size), 
4. Create Transfer learning CNN from InceptionV3 by cutting at "mixed7" layer (VGG, AlexNet, ResNet, GooLeNet),
5. Use data augmentation to balance underrepresented classes,
6. Play with train/validation split,
7. Implement 14 binary classifiers (one versus all).
