# Overview
- This repository provides an overview of implementing a Mask-RCNN on a custom image dataset to detect 2 classes of damages to automobile exterior bodies - DENT and SCRATCH
  
# Custom Dataset
- 100 images of damaged automobiles with scratches and dents were collected from google (Training-80; Validation-20)
- The regions of damages were annotated using the VIA annotation tool (https://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.1.html)
- The annotations were downloaded as a json file and stored in the Training and Validation folders

# Environment
- This code was executed in an environment which has Tensorflow 1.13.1 and Keras 2.2.5

# Training Model on Custom Dataset
- Download and save the 'mask_rcnn_coco.h5' weights file in the project folder
- Refer to the custommaskrcnn.pynb notebook to see how the model was trained on 2 custom classes 

# Using Model Trained on Custom Dataset
- Sample outputs available in the folder
