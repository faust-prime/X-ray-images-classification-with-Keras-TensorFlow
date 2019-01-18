Setup Anaconda, pip, TF, Keras and Jupyter Notebook (executed in Ubuntu 18.04 LTS):

1. Download Anaconda + install the .sh-file using terminal: "bash filename.sh"
2. Validate installation, start AnacondaNavigator using terminal: "anaconda-navigator"
3. Install pip depending on your Python Version: conda install pip3

4. Install TensorFlow: pip3 install --upgrade tensorflow
5. Install keras: 	    pip3 install Keras
6. conda create -n tensorflow python=3.7
7. source activate tensorflow
8. conda install -c conda-forge tensorflow

9. Install Jupyter Notebook: conda install jupyter
10. Launch JN: jupyter notebook

11. Launch jupyter notebook from terminal: "jupyter notebook" 
12. Open the file "CNN.ipynb"

TODO: Train/Test Split of my example directory does not work until now, I tried using "validation_split" but it doesn't work.
