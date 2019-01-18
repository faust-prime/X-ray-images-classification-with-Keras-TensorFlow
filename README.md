Setup Anaconda, pip, TF, Keras and Jupyter Notebook (executed in Ubuntu 18.04 LTS):

1. Download Anaconda + install the .sh-file using terminal: "bash filename.sh"
2. Validate installation, start AnacondaNavigator using terminal: "anaconda-navigator"
3. Install pip depending on your Python Version: conda install pip3

4a: Install TensorFlow: pip3 install --upgrade tensorflow
4b: Install keras: 	    pip3 install Keras
4c: conda create -n tensorflow python=3.7
4d: source activate tensorflow
4d: conda install -c conda-forge tensorflow

5a: Install Jupyter Notebook: conda install jupyter
5b: Launch JN: jupyter notebook

6a: Launch jupyter notebook from terminal: "jupyter notebook" 
6b: Open the file "CNN.ipynb"

TODO: Train/Test Split of my example directory does not work until now, I tried using "validation_split" but it doesn't work.
