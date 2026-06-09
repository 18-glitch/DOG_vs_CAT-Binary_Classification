# 🐶 Dog vs Cat Classification

A binary image classifier built using a custom CNN in PyTorch, trained on real-world data from Kaggle.

## Results
- **Test Accuracy: 79.87%**
- Tested on real-world images (see `/data` folder)

## Dataset
- Source: [Kaggle - Dog and Cat Classification Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)
- 12,500 images per class, split 80/20 into train/test

## Implementation
- Built a 3-layer CNN from scratch with PyTorch
- Manual data pipeline using `os` and `shutil` for train/test splitting
- Handled corrupted images using PIL verification
- Evaluated with confusion matrix and real image inference

## Packages Used
`PyTorch` `torchvision` `PIL` `os` `shutil`

## Setup
1. Download the dataset from Kaggle and place `Cat/` and `Dog/` folders in the root directory
2. Uncomment the data splitting cells and run them once
3. Run remaining cells to train and evaluate