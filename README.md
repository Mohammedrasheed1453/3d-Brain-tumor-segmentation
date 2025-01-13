# 3d-Brain-tumor-segmentation
First i have collected the BRATS 2020 dataset from kaggle which is  a 3D dataset and consists of training and validation sets. 
As the raw datasets is not in crct size both the masks and images are in different sizes so i resized all them to 128x128x128
next step i have applied cropping
next i have applied intermodality fusion beacuse in image set i have 4 images of different modality like Flair, T1ce,t2 etc and a mask image
next i have normalized them using zscore normalization
next created labels for mask images like whole tumor ,tumor core,enhancing tumor
finally i trained the model that is my 3dunet
and my loss was pretty decreasing after each epoch but since it is 3D processsing computer requirements are not enough for still validating 
