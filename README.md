# Overview

Text classification algorithm that predicts news topics on articles from the Reuters 21578 dataset

### To install all dependencies on ubuntu 16.04 run:

sudo apt-get update
sudo apt-get install python3 python3-dev python3-pip python3-h5py build-essential
sudo pip3 install pip --upgrade
sudo pip3 install keras sklearn nltk gensim numpy https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.10.0-cp35-cp35m-linux_x86_64.whl

### Run the training script to generate the models
python3 reuters-doc2vec-train.py

### Run the prediction script to view the predicted labels and the original labels
python3 reuters-doc2vec-predict.py