# coastline_extraction
This project is about implementing coastline segmentation using image level classification.

coastline_basic.ipynb contains some basic attempts such as exporting an image from the GEE dataset and converting it to an array, and training ResNet-18 using the CIFAR-10 dataset.

ee_classify.ipynb shows code for achieving supervised classification using GEE's Classifier package.

cnn_sea_land_classify.ipynb includes the construction of the sea and land dataset, and deep learning with it.

cnn_seg.ipynb presents the process of coastline segmentation using the trained neural network, including image dividing and stitching, and post-processing.

https://code.earthengine.google.com/?scriptPath=users%2Fjingyuhu98%2Fsea_land_classification%3ACART_algorithm is the code on GEE for performing CART.
