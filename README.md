# BraTS_segmentation_Using_3D_UNet


### All BraTS multimodal scans are available as NIfTI files (.nii.gz) -> commonly used medical imaging format to store brain imagin data obtained using MRI and describe different MRI settings

### DataSet Link - https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation

### Dataset Info:-
#### Multimodal scans are available as NIfTI files (.nii.gz)
#### Four 'channels' of information - 4 different volumes of the same region
#### - Native (T1)
#### - Post-contrast T1-weighted (T1CE)
#### - T2-weighted (T2)
#### - T2 Fluid Attenuated Inversion Recovery (FLAIR) volumes

## All the imaging datasets have been segmented manually and were approved by experienced neuro-radiologists. 

### Annotations (labels): 
#### - Label 0: Unlabeled volume
#### - Label 1: Necrotic and non-enhancing tumor core (NCR/NET)
#### - Label 2: Peritumoral edema (ED)
#### - Label 3: Missing (No pixels in all the volumes contain label 3)
#### - Label 4: GD-enhancing tumor (ET)

## Approach (High Level):
### Step 1: Get the data ready 
### Step 2: Define custom data generator
### Step 3: Define the 3D U-net model
### Step 4: Train and Predict

### Reference:
#### - https://arxiv.org/abs/1606.06650
#### - [Youtube: ](https://www.youtube.com/@DigitalSreeni)
#### - https://realpython.com/introduction-to-python-generators/
#### - Focal and dice loss works better together - https://academic.oup.com/bioinformaticsadvances/article/4/1/vbae169/7907198

### View More detailed: https://snehpatel38.github.io/BraTS_segmentation_Using_3D_UNet/
