# Brain Tumor Segmentation using 3D U-Net

## Overview
This project implements a deep learning-based brain tumor segmentation model using a 3D U-Net architecture. The model processes MRI scans to classify and segment tumor regions, aiding in medical image analysis.

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

## Dataset
The project uses publicly available MRI datasets for training and validation. Ensure the dataset is in NIfTI format (.nii) before processing.

## Installation
```sh
# Clone the repository
git clone https://github.com/Reranko05/Brain-Tumor-Segmentation.git
cd Brain-Tumor-Segmentation

# Install dependencies
pip install -r requirements.txt
```

## Usage
```sh
# Run data preprocessing
python preprocess.py

# Train the model
python train.py

# Evaluate the model
python evaluate.py
```

## Results
The model achieves high segmentation accuracy, effectively distinguishing tumor regions from MRI scans. 

## Contributions
Feel free to contribute by improving the model, adding more datasets, or optimizing performance. Fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For queries, reach out via email - aadityasri03@gmail.com or connect on LinkedIn - www.linkedin.com/in/aaditya-srinivasan-0b6902288.
