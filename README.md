# 🐾 Image Classification using CNN for Animal Dataset

## 📌 Project Overview
This project focuses on **Image Classification using Convolutional Neural Networks (CNNs)** for identifying different animal categories from image datasets.  
The model was trained using a **2-phase training strategy**, which significantly improved performance and achieved an impressive **97.88% accuracy**.

The project demonstrates the power of Deep  Learning and CNN architectures in solving real-world computer vision problems.

---

## 🚀 Features
- 📷 Animal image classification using CNN
- 🧠 Deep Learning-based feature extraction
- 🔄 Two-phase model training
- 📈 Achieved **97.88% accuracy**
- 🗂️ Dataset preprocessing and augmentation
- 📊 Training & validation performance visualization
- 💾 Model saving and prediction support

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

---

## 📂 Dataset
The dataset contains images of multiple animal categories used for training and testing the CNN model.

### Example Classes
- Cat
- Dog
- Lion
- Tiger
- Elephant
- Horse
- Deer
- Monkey

> Dataset images were preprocessed, resized, normalized, and augmented before training.

---

## 🧠 CNN Architecture
The CNN model includes:
- Convolution Layers
- Max Pooling Layers
- Dropout Layers
- Fully Connected Dense Layers
- Softmax Output Layer

The architecture was designed to efficiently learn spatial features from animal images.

---

# 🔥 Two-Phase Training Strategy

## Phase 1
- Initial CNN training on preprocessed dataset
- Data augmentation applied
- Basic feature learning

## Phase 2
- Fine-tuning and optimization
- Hyperparameter tuning
- Improved generalization
- Better validation performance

✅ Final Accuracy Achieved: **97.88%**

---

## 📊 Model Performance

| Metric | Value |
|--------|--------|
| Training Accuracy | 98.21% |
| Validation Accuracy | 97.88% |
| Loss Reduction | Significant |
| Training Phases | 2 |

---

## 📸 Sample Workflow

1. Load Dataset  
2. Preprocess Images  
3. Apply Data Augmentation  
4. Build CNN Model  
5. Train Model (Phase 1)  
6. Fine-tune Model (Phase 2)  
7. Evaluate Accuracy  
8. Predict Animal Class  

---

## ▶️ How to Run

### Clone Repository
```bash
git clone https://github.com/your-username/animal-image-classification-cnn.git
cd animal-image-classification-cnn
