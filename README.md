# Image Classification using CNN

This repository demonstrates how to train a Convolutional Neural Network (CNN) on the CIFAR-10 dataset using PyTorch. The code includes a custom dataset class, data augmentation, and a CNN architecture that achieves reasonable accuracy on CIFAR-10 images.

## Features
- Utilizes PyTorch for deep learning model development and training.
- Custom dataset class for loading images in a folder structure.  
- Data augmentation (random horizontal flip, random rotation, color jittering).  
- Model evaluation metrics and prediction function for new images.

## Requirements
- Python 3.x  
- PyTorch  
- torchvision  
- NumPy  
- pandas  
- matplotlib  
- OpenCV (optional if not visualizing images with cv2)  
- PIL  

## Directory Structure
1. The training set is stored under:  
   /kaggle/input/cifar10/cifar10/train  
2. The testing set is stored under:  
   /kaggle/input/cifar10/cifar10/test  
3. The CIFAR-10 image folders have subdirectories named after the class categories (e.g., bird, cat, dog).

## Usage
1. Place the CIFAR-10 training and testing images in the specified directories.  
2. Run the script below in a Python environment (e.g., Kaggle Notebook, Google Colab, or local setup with appropriate library versions).
3. Adjust the hyperparameters such as batch size, epochs, learning rate, and transforms as desired.
4. Inference can be performed with the provided predict function on any image from your local system.


## Results
- After training for 25 epochs, the CNN typically achieves a decent accuracy on the CIFAR-10 test set depending on hyperparameters and data augmentations.
- The provided script prints training loss, accuracy, and testing metrics (loss and accuracy).

## License
This project is licensed under the MIT License.  
