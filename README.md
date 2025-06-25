# Potato Leaf Disease Identifier 🌿

A Convolutional Neural Network (CNN) based deep learning model to classify potato leaf diseases from images. Built using TensorFlow/Keras and trained on a dataset of labeled potato leaf images.

## Project Overview

This project uses a CNN to classify potato leaves into different disease categories (e.g., Early Blight, Late Blight, Healthy). The model was trained on a labeled dataset of potato leaf images using standard deep learning practices such as data augmentation and model regularization.

## Contents

- `potato.ipynb` – Jupyter Notebook containing the training, evaluation, and prediction pipeline.
- `1/` – Folder containing the trained TensorFlow `saved_model.pb` and weights.
- `requirements.txt` – Python libraries needed to run the notebook.
- `README.md` – This file.

## Dataset

The dataset used was from [PlantVillage - Kaggle Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease). It includes labeled images of potato leaves under various disease conditions.

**Note:** The dataset is **not included** in this repository due to size limitations.

To run this notebook, you can download the dataset manually and place it in the following structure:
dataset/
├── Potato___Early_blight/
├── Potato___Late_blight/
├── Potato___Healthy/

(In my case, I had saved the dataset folder as "Diseases", but you may modify as you wish)


## 🧠 Model Architecture

The CNN model includes:
- Convolutional + ReLU layers
- MaxPooling
- Fully connected Dense layers
- Softmax output for multiclass classification

Detailed architecture is in the notebook.

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/potato-leaf-disease-cnn.git
   cd potato-leaf-disease-identification
   
2. Create a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # on Linux/Mac
   venv\Scripts\activate     # on Windows

3. Install Dependencies:
   pip install -r requirements.txt

4. Download the dataset (see above) and place it in dataset/ 

5. Open and run the notebook:
   jupyter notebook potato.ipynb

You can also load the saved model from the '1/' directory.  
