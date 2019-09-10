# Mask-RCNN
Basics and Hand-On 
NOTE : All the actions and works have been done on Ubuntu Virtual Machine



TO INSTALL Mask_RCNN : 

OPEN TERMINAL,
TYPE THE FOLLOWING
sudo su
(enter ur password)

# git clone https://github.com/matterport/Mask_RCNN.git   (without '#')
# cd Mask_RCNN
# apt-get install python-pip
# apt-get install python3-pip
# hash -d pip [Incase of error with pip]
# pip install -r requirements.txt 
# pip3 install imgaug
# python setup.py install
# pip show mask-rcnn

Now, download the weights (https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5)

Copy the downloaded weights file to the Mask_RCNN/samples/ folder,
Now, make a new folder named 'sandbox' in Mask_RCNN folder. This sandbox folder would be the one that would contain all the files that you are going to work with and also the notebooks that would be created.


# Working with Custom Datasets and Classes
There are a total of 81 predefined and pretrained classes available in MaskRCNN. To use maskrcnn for classes apart from these 81 classes, follow the steps mentioned in the document : https://docs.google.com/document/d/1wwZPsBMmVs4u0Lf-mHKBjEzvm7FPvcomLftiDb2zIfU/edit?usp=sharing.
