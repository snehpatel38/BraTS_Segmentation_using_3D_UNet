# BraTS_segmentation_Using_3D_UNet

### All BraTS multimodal scans are available as NIfTI files (`.nii.gz`) — a commonly used medical imaging format to store brain imaging data obtained using MRI, describing different MRI settings.

### 📂 Dataset Link: [Kaggle - BraTS20 Training & Validation Dataset](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation)

---

### 📊 Dataset Info:
Multimodal scans are provided as NIfTI files (`.nii.gz`) with four 'channels' of information — 4 different volumes of the same brain region:
- **Native (T1)**
- **Post-contrast T1-weighted (T1CE)**
- **T2-weighted (T2)**
- **T2 Fluid Attenuated Inversion Recovery (FLAIR)**

All imaging datasets were manually segmented and approved by experienced neuro-radiologists.

---

### 🏷️ Annotations (Labels):
- **Label 0**: Unlabeled volume  
- **Label 1**: Necrotic and non-enhancing tumor core (NCR/NET)  
- **Label 2**: Peritumoral edema (ED)  
- **Label 3**: Missing (no pixels in any volume contain label 3)  
- **Label 4**: GD-enhancing tumor (ET)  

---

## ⚙️ Approach (High-Level):
- **Step 1**: Get the data ready  
- **Step 2**: Define a custom data generator  
- **Step 3**: Define the 3D U-Net model  
- **Step 4**: Train and predict  

---

### 📚 Reference:
- [3D U-Net Paper (arXiv)](https://arxiv.org/abs/1606.06650)  
- [YouTube: Digital Sreeni](https://www.youtube.com/@DigitalSreeni)  
- [Real Python: Introduction to Python Generators](https://realpython.com/introduction-to-python-generators/)  
- [Focal + Dice Loss Reference (Bioinformatics Advances)](https://academic.oup.com/bioinformaticsadvances/article/4/1/vbae169/7907198)  

---

### 🔍 View More Details: [Project Page](https://snehpatel38.github.io/BraTS_segmentation_Using_3D_UNet/)
