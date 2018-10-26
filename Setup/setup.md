参考
https://medium.com/@margaretmz/anaconda-jupyter-notebook-tensorflow-and-keras-b91f381405f8

1. Install Conda

2. Create a new virutal env
$  conda create -n env-name

3. Activate the virtual env
$  activate env-name

4. Install pip under env
$  conda install pip

5. Install tensorflow
$ pip install --upgrade tensorflow # for python 2.7
$ pip3 install --upgrade tensorflow # for python 3.*

6. Install Keras (Note: please install TensorFlow first)
$ pip install Keras

7. Install nb_conda for easily managing/switching notebook kernel [Note install this in virtual env]
$ conda install nb_conda

8. Start jupyter notebook in virtual, then we could choose the env
