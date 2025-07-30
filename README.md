# BraTS_segmentation_Using_3D_UNet


## All BraTS multimodal scans are available as NIfTI files (.nii.gz) -> commonly used medical imaging format to store brain imagin data obtained using MRI and describe different MRI settings

## DataSet Link - https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation

### Dataset Info:-
#### Multimodal scans are available as NIfTI files (.nii.gz)
#### Four 'channels' of information - 4 different volumes of the same region
#### - Native (T1)
#### - Post-contrast T1-weighted (T1CE)
#### - T2-weighted (T2)
#### - T2 Fluid Attenuated Inversion Recovery (FLAIR) volumes

## T1: T1-weighted, native image, sagittal or axial 2D acquisitions, with 1–6 mm slice thickness.
## T1c: T1-weighted, contrast-enhanced (Gadolinium) image, with 3D acquisition and 1 mm isotropic voxel size for most patients.
## T2: T2-weighted image, axial 2D acquisition, with 2–6 mm slice thickness.
##FLAIR: T2-weighted FLAIR image, axial, coronal, or sagittal 2D acquisitions, 2–6 mm slice thickness.


## get_data_ready.py
### Load sample images and visualize
### Includes, dividing each image by its max to scale them to [0,1]
###Converting mask from float to uint8
### Changing mask pixel values (labels) from 4 to 3 (as the original labels are 0, 1, 2, 4)
