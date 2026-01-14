# X-Ray Image Classification Using CNN

This repository contains a deep learning project that classifies chest X-ray images using a **Convolutional Neural Network (CNN)**. The goal of this model is to distinguish between categories such as **Pneumonia** and **Normal** using medical X-ray imagery.

The code and experiments are implemented in a Jupyter Notebook. It uses image preprocessing, CNN model building, training, validation, and testing steps.

---

## 📁 Project Contents

- **X_ray_Image_Classification.ipynb** — The main notebook with the full implementation of the X-ray classification pipeline.  
- **README.md** — This file (you’re reading it) explaining the purpose, setup, and usage of the project.

---

## 🧠 About the Model

This project uses a **Convolutional Neural Network (CNN)** to learn patterns from chest X-ray images and classify them into categories like *normal* or *diseased*. CNN models are widely used for medical image classification tasks because they can automatically extract features from raw pixel inputs. :contentReference[oaicite:1]{index=1}

Typical steps involved include:

1. Loading and preprocessing the X-ray dataset  
2. Defining the CNN architecture  
3. Training the model on labeled images  
4. Evaluating performance on a test dataset  
5. (Optional) Saving and using the trained model for predictions

---

## 🚀 How to Use

1. **Clone the repo:**
   git clone https://github.com/Prabhatrai7/X-Ray-Image-Classification-Using-CNN.git
   cd X-Ray-Image-Classification-Using-CNN

2. **Install dependencies:**
    Make sure you have Python installed and then install:

    pip install numpy pandas matplotlib scikit-learn tensorflow keras notebook

3. **Launch the notebook:**
    jupyter notebook X_ray_Image_Classification.ipynb

🧪 Dataset

The notebook expects a dataset of chest X-ray images organized in folders by class label (for example, Normal/ and Pneumonia/). Public datasets such as the Kaggle Chest X-Ray Pneumonia dataset can be used.

📊 Expected Outcomes

  After training, the CNN model should be able to:
  
  Differentiate between normal and pneumonia-affected chest X-rays
  
  Show metrics such as accuracy, loss curves, and confusion matrices
  
  (Optional) Save the trained model for reuse
