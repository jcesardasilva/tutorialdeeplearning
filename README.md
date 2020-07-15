Tutorial Deep Learning
======================

Introduction
------------
Jupyter notebooks in Python to assist the tutorial on basics of Deep Learning.
The present notebooks are intended for educational reasons only. They are not be perfect, 
but keep been gradually improved. Apologies for possible mistakes and missing 
references.

It is important to mention that the Python codes were
inspired by the "Tutorial TensorFlow" provided by TensorFlow Core by TensorFlow authors. 
Modifications have been made on the original code for educational reasons and 
Python compatibility. Further information and more tutorials are available at:

https://www.tensorflow.org/tutorials

and 

https://github.com/tensorflow/examples


Getting started
---------------

Throughout this tutorial, we will run some python scripts using Jupyter 
Notebook. You can either download the files from this Gitlab repository and copy them in 
a folder of your choice or, if you prefer, you can clone it by typing:

git clone https://gitlab.esrf.fr/jdasilva/tutorialdeeplearning.git

Once the files are in your computer, you can open Jupyter Notebook by:
- Windows: click on the Jupyter Notebook icon installed in the start menu.
- Linux/Mac OS: open the terminal and type jupyter notebook at the prompt.

Concerning the use of Jupyter Notebooks, the website:

https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html
 
shows how to install it and to start it in the different Operational Systems (Linux/Mac OS, Windows). 
Additionally, some Python packages are required: Numpy, IPython, Matplotlib, and scikit-image. 

Dependencies
------------
* python >= 3.6
* numpy
* matplotlib
* scipy
* Tensorflow
* Tensorflow-datasets
* Tensorflow_hub
* Keras

If you do not have such packages installed, I recommend the installation via pip install:

pip3 install --user numpy, ipython, matplotlib, scipy, tensorflow, tensorflow-datasets, tensorflow_hub, keras

