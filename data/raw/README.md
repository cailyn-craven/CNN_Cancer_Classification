The raw data for this project comes from the Kaggle competition, "Histopathologic Cancer Detection."
https://www.kaggle.com/c/histopathologic-cancer-detection
<br>
This dataset is a slightly modified version of the PatchCamelyon (PCam) dataset with duplicates removed. 
https://github.com/basveeling/pcam
<br>
## PCam 
PCam is benchmark medical imaging dataset of H&E stained WSIs of sentinel lymph node sections from breast cancer patients in the Netherlands in 2015. If cancer has metastasized, it is most likely to have spread to the sentinel lymph node. We are given a training set with 220,025 images, and a test set of 57.5k images. Both the training and testing set have the structure of a directory with .tif image files inside. The .tif file format is used for high resolution files that are not compressed. 
<br>
The images are RGB color images, 96 pixels by 96 pixels in size. Each image has a corresponding label of 0 for no metastatic tissue and 1 for metastatic tissue. A positive label means that the center 32 pixel by 32 pixel patch of the image contains at least one pixel with tumor tissue. 
