# ARTI560 Road Damage Classification

## Project Overview
This project presents a computer vision approach for binary road damage classification using deep learning models. The objective is to classify Saudi road images into two categories: damaged roads and non-damaged roads. Three different deep learning approaches were implemented and compared to evaluate classification performance.

## Implemented Models
- Simple CNN
- CNN with Data Augmentation
- EfficientNet-B0 (Transfer Learning)

## Dataset
The project uses the Saudi Road Damage Dataset from Roboflow.

Dataset Source:
https://universe.roboflow.com/manalbitesbytes/saudird-2

Classes:
- Damage
- No Damage

## Repository Structure
- rddetection-simplecnn.ipynb → Simple CNN implementation
- rddetection-simplecnn-with-aug.ipynb → CNN with data augmentation
- rddetection-efficientnet.ipynb → EfficientNet-B0 implementation
- README.md

## Requirements
Required libraries:
- Python 3.x
- PyTorch
- torchvision
- NumPy
- Matplotlib
- scikit-learn
- pandas

Install dependencies using:

```bash
pip install torch torchvision numpy matplotlib scikit-learn pandas
```

## How to Run
1. Clone this repository.
2. Download the dataset from the provided source.
3. Update dataset paths in the notebooks.
4. Open the notebooks in Jupyter Notebook, Kaggle, or Google Colab.
5. Run each notebook to train and evaluate the models.

## Results
The three models were evaluated for road damage classification performance. EfficientNet-B0 achieved the highest classification accuracy compared to the Simple CNN and CNN with data augmentation models.

## Reproducibility
- Ensure all required dependencies are installed.
- Use the correct dataset path before execution.
- GPU is recommended for faster training.
- Random seeds should be fixed for reproducible results.
