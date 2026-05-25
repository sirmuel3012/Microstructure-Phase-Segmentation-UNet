# Microstructure Phase Segmentation using U-Net

## Project Description
This project uses a U-Net deep learning model to analyze microstructure images and identify material phases such as ferrite, pearlite, and martensite.

## Features
- Image segmentation using U-Net
- Microstructure phase detection
- Image upload functionality
- Predicted phase mask generation
- Overlay visualization
- Phase percentage estimation
- GUI interface using Gradio

## Technologies Used
- Python
- TensorFlow
- OpenCV
- Google Colab
- CVAT
- Gradio

## Workflow

Collect images
↓
Label images in CVAT
↓
Generate segmentation masks
↓
Train U-Net model
↓
Apply weighted loss and Dice loss
↓
Evaluate model
↓
Build GUI interface

## Results
- Mean IoU ≈ 0.246
- Weighted loss improved prediction behavior
- GUI implemented for image upload and analysis

## Limitations
- Small dataset (~25 images)
- Class imbalance
- Reduced performance on unseen images

## Future Improvements
- Larger dataset
- Improved labeling
- Live camera support
- Better model generalization
