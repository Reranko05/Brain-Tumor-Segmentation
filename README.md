# Brain Tumor Segmentation using 3D U-Net

## Overview
This project implements a deep learning-based brain tumor segmentation model using a 3D U-Net architecture. The model processes MRI scans to classify and segment tumor regions, aiding in medical image analysis. The implementation is provided in a Jupyter Notebook (`TumorSegment001.ipynb`).

## Features
- Preprocesses NIfTI medical imaging data
- Uses a 3D U-Net model for segmentation
- Optimized with Dice Loss for improved accuracy
- Evaluates performance using IoU, sensitivity, and precision metrics
- Implements data augmentation for enhanced model generalization

## Technologies Used
- Python
- TensorFlow, Keras
- OpenCV, Nibabel
- SciPy, Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset
This project uses the BraTS 2020 (Brain Tumor Segmentation) dataset, a benchmark dataset provided by the Medical Image Computing and Computer Assisted Intervention (MICCAI) society.

Key Details:

Source: BraTS 2020 Challenge
Format: All volumes are in NIfTI (.nii) format

Modalities per case:
T1-weighted (T1)
T1-weighted post-contrast (T1CE)
T2-weighted (T2)
FLAIR

Segmentation Labels:
Label 0: Background
Label 1: Necrotic and Non-Enhancing Tumor Core (NCR/NET)
Label 2: Peritumoral Edema (ED)
Label 3: Enhancing Tumor (ET)

Note: Only the FLAIR and T1CE modalities are used in this project for input, and the segmentation mask is used as the ground truth.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Reranko05/Brain-Tumor-Segmentation.git
   cd Brain-Tumor-Segmentation
  ```
2. Or download the Jupyter notebook directly from GitHub and open it manually in Jupyter Lab or Notebook.

## Usage
1. Open the Jupyter Notebook:
```sh
jupyter notebook TumorSegment001.ipynb
```
2. Run the cells sequentially to preprocess data, train the model, and evaluate performance.

Note: This notebook contains the output from a successful run. Later code edits caused errors which I’m debugging — but this version showcases the working pipeline and predictions

## Results
The model achieves high segmentation accuracy, effectively distinguishing tumor regions from MRI scans. 

## Contributions
Feel free to contribute by improving the model, adding more datasets, or optimizing performance. Fork the repository and submit a pull request.

## Contact
For queries, reach out via aadityasri03@gmail.com


