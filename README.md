Setup Anaconda, pip, TensorFlow, Keras and Jupyter Notebook (executed in Ubuntu 18.04 LTS):

1.  Download Anaconda + install the .sh-file using terminal:       "bash filename.sh"
2.  Validate installation, start AnacondaNavigator using terminal: "anaconda-navigator"
3.  Install pip depending on your Python Version:                  "conda install pip3"
4.  Install TF:                                                    "pip3 install --upgrade tensorflow"
5.  Install keras: 	                                               "pip3 install Keras"
6.  Create TF instance:                                            "conda create -n tensorflow python=3.7"
7.  Install environment:                                           "conda install -c conda-forge tensorflow"
8.  Install jupyter notebook:                                      "conda install jupyter"
9.  Activate TF:                                                   "source activate tensorflow"
10. Launch JN:                                                     "jupyter notebook"
11. Open the file:                                                 "CNN.ipynb"

TODO: Train/Test Split of my example directory does not work until now, I tried using "validation_split" but it doesn't work.
When all steps up to and including #8 have been completed, you can start working with #9: activate TF and start the notebook.
