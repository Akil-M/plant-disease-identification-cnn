# 🥔 Potato Leaf Disease Detection using CNN

This project implements a **Convolutional Neural Network (CNN)** to classify diseases in potato leaves using image data. It includes training notebooks, result visualizations, and saved model files for reproducibility and deployment.

---

## 📁 Project Structure

```
project-cnn/
│
├── Dataset.rar                          # Raw image dataset (Potato leaves)
├── Model code/
│   ├── potato_disease_classification_model.ipynb  # Jupyter notebook
│   └── sample code.png                  # Sample image of the code
│
├── Result/
│   ├── Result.png                       # Final prediction results
│   └── Training and Validation - Accuracy and Loss.png
│
├── Trained Models/
│   ├── 1.h5                             # Trained model (HDF5)
│   └── 1.keras                          # Saved Keras model format
│
├── flow-diagram.png                     # Flow diagram of CNN pipeline
├── model summary.png                    # CNN model architecture summary
├── sample dataset.png                   # Example images from dataset
└── README.md                            # Project documentation
```

---

## 🚀 Features

- ✅ CNN-based image classification
- 🔍 Focused on potato leaf disease detection
- 🧪 Includes training and validation graphs
- 📁 Model checkpoints (`.h5`, `.keras`) for reuse
- 📷 Easy to swap in new potato leaf images for prediction

---

## 🛠️ Tech Stack

- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas
- OpenCV / PIL
- Matplotlib / Seaborn

---

## 🧪 Dataset

The dataset includes potato leaf images categorized into:
- Healthy leaves
- Early blight
- Late blight

> Replace or extend the dataset by extracting and organizing images in subfolders as per class.

---

## 📌 How to Run

1. Clone the repository:
```bash
git clone https://github.com/Akil-M/plant-disease-identification-cnn.git
cd plant-disease-identification-cnn
```

2. (Optional) Create a virtual environment:
```bash
python -m venv cnn-env
cnn-env\Scripts\activate      # On Windows
# or
source cnn-env/bin/activate     # On Linux/macOS
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Open the Jupyter notebook and run:
```bash
jupyter notebook
```

---

## 📊 Results

Training and validation accuracy/loss graphs are saved in the `Result/` folder. Final model accuracy: **99.1%** (update with your result).

---

## 📬 Contact

Created by **Akil M**  
📧 akilmasiv@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/akil-m-343359254)

---
