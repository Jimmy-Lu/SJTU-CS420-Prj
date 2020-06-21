# SJTU-CS420-Prj
The project is inspired by ISBI Challenge and designed for students to learn to build a model for a segmentation task.

Dataset
ISBI2012: http://brainiac2.mit.edu/isbi_challenge/

Data Preprocessing
Download ISBI2012 Dataset from http://brainiac2.mit.edu/isbi_challenge/
Put data into corresponding file folder in '/data'

Augmentation(optional)
$python augentation.py
Result will be stored in '/data/aug'

Train
$ python train.py

Test
$ python predict.py

Reference
https://github.com/hanyoseob/youtube-cnn-002-pytorch-unet
https://github.com/zhixuhao/unet