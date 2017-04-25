Deep learning notebooks
=======================
Jupyter notebooks with reading notes from the Deep Learning textbook and code
for simple projects.


Install
-------
On Mac OS X:

    virtualenv -p python3.5 .pydl
    source .pydl/bin/activate
    pip -r requirements.txt

Note tensorflow version for Mac is hard-wired in  `requirements.txt`.  
On Linux use `pip install tensorflow==1.0.1` instead.


Project 01
----------
Start a notebook server

    jupyter notebook

then go to the `project01_MNIST_digit_recognizer/` directory.

Currently `mxnet` and `tensorflow` sample code is provided.
