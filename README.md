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
1. Open the Jupyter Notebook:
```sh
jupyter notebook TumorSegment001.ipynb
```
2. Run the cells sequentially to preprocess data, train the model, and evaluate performance.

## Results
The model achieves high segmentation accuracy, effectively distinguishing tumor regions from MRI scans. 

## Contributions
Feel free to contribute by improving the model, adding more datasets, or optimizing performance. Fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For queries, reach out via [your email] or connect on [LinkedIn/GitHub].
