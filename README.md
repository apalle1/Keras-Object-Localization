# Object-localization
This project shows how to localize objects in images by using simple convolutional neural networks.

# Dataset
Before getting started, we have to download a dataset and generate a csv file containing the annotations (boxes).

* Download The Oxford-IIIT Pet Dataset
* Download The Oxford-IIIT Pet Dataset Annotations

# Single-object detection

Choose a model from Keras Applications i.e. 
feature extractor
Remove the dense layer
Freeze some/all/no layers
Add one/multiple/no convolution block (or _inverted_res_block for MobileNetv2)
Add a convolution layer for the coordinates

The code in this repository uses VGG16, because it is faster than other models and the performance can be adapted. 
