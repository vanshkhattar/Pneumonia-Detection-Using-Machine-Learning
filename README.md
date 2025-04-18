
# Pneumonia Detection from Chest X-ray Images

This project contains three Jupyter notebooks used for training and testing a machine learning model to detect pneumonia from chest X-ray images.

## Contents

- `train_model.ipynb`: Trains a classification model using a chest X-ray dataset.
- `testing.ipynb`: Loads the trained model and performs inference on test data.
- `pnumonia.ipynb`: Additional exploratory analysis and experimentation.

## Requirements

Make sure to install the required dependencies using:

```
pip install -r requirements.txt
```

## Dataset

The dataset used for this project includes chest X-ray images and labels stored in NumPy arrays:

- `data/dataChestXray.npy`
- `data/targetChestXray.npy`

Due to file size restrictions (file exceeds 750MB), these datasets are not included in this repository.

### How to Use the Dataset

1. Obtain the dataset files (`dataChestXray.npy` and `targetChestXray.npy`) either from your own source or wherever they are hosted.
2. Place them in the following directory structure:

```
project-root/
├── data/
│   ├── dataChestXray.npy
│   └── targetChestXray.npy
├── train_model.ipynb
├── testing.ipynb
├── pnumonia.ipynb
├── requirements.txt
└── README.md
```

Ensure the `data` directory is at the root level of the project so the notebooks can load the files correctly.

## Notes

- The model architecture is built using TensorFlow/Keras and trained on preprocessed NumPy arrays.
- This repository does not include model weights or saved models. Modify the notebook to save and load models if needed.
