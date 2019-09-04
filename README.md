# pytorch_unet_crack
This is a repository for crack segmentation task.


This repository is yet to be 'tested' and is in training phase.

The research is being conducted under the facult of Civil Engineering and Geoscience, at Delft University of Technology.

## Thesis Title: A deep learning approach for pavement distress classification.

# About the model: The Dense Neural Network (DNN) used in this research is based on the U-Net architecture
which was created by Olaf Ronneberger, Philipp Fischer, Thomas Brox in 2015 at the paper “UNet: Convolutional Networks for Biomedical Image Segmentation”.

Primarily, this Deep Neural Network (DNN) is also been trained on  for Biomedical Imagae diagnosis for cell detection, autonomous vehicle,
geo-sensing etc. The architecture has contraction path ENCODER and Expansion path DECODER.

The Dataset comprises of 11,298 images of cracks and 11, 298 masks created for them.
Each image is in of size of 512x512x3 and of .png format.

The data.rar file comprises of train, test and val folders, each has sub-folders in the name: Images and Masks.
The data.rar file needs to be in the main directory.

#To train the mode, go into the "U-net model" folder and run the sccript: python main.py.

..................
...............
...........
.......
....
..
.
