
# Chest X-Ray Pneumonia Classification

This project uses deep learning (CNN) to classify chest X-ray images as Pneumonia or Normal.

## 📁 Project Structure

- `train_model.ipynb` – CNN model training using chest X-ray image data (.npy format).
- `testing.ipynb` – Model evaluation and confusion matrix.
- `pnumonia.ipynb` – Additional exploration or visualization of predictions.
- `data/` – Folder to hold input datasets (`dataChestXray.npy`, `targetChestXray.npy`).
- `requirements.txt` – Python dependencies.

## 📦 Dataset

Place the following files in the `data/` folder:
- `dataChestXray.npy`
- `targetChestXray.npy`

If you don't have these files, prepare or download them and place them manually.

## 🚀 Getting Started

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the training notebook:
Open `train_model.ipynb` in Jupyter or Colab and run all cells to train the model.

3. Evaluate the model:
Use `testing.ipynb` to test model accuracy and view the confusion matrix.

## 🧠 Model

The model is a convolutional neural network trained using Keras. It uses dropout and max pooling for regularization and downsampling.

## 📈 Results

Accuracy and loss are plotted during training, and evaluation is done using confusion matrix and test accuracy.

## 🛠️ Requirements

See `requirements.txt` for all dependencies.

---

Created for academic and research purposes.
