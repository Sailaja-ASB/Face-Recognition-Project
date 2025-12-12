# Face Recognition Project 👤🔍  

This project implements a deep-learning-based **face recognition** system using a Convolutional Neural Network (CNN).  
It includes image preprocessing, model training, evaluation, and insights into model performance and limitations.

---

## 📁 File Included

- **Face-Recognition.ipynb** *(your uploaded notebook name)*  
  Contains:
  - Image loading and preprocessing  
  - Train/test split  
  - CNN model architecture  
  - Training for 30 epochs  
  - Accuracy & loss plots  
  - Classification report  
  - Predictions  

> If you renamed your file, replace the name above.

---

## 🧠 Model Overview

This project uses a **custom CNN** for image-based face recognition.  
The pipeline includes:

- Convolution + MaxPooling layers  
- Flatten & Dense layers  
- Softmax output layer  
- Adam optimizer  
- Categorical cross-entropy loss  

The notebook demonstrates a complete ML workflow from raw images to predictions.

---

## 📊 Model Performance

- **Training Accuracy:** ~76%  
- **Validation Accuracy:** ~57%  
- Validation loss increases in later epochs  
- This indicates **overfitting**, which is expected for small datasets in face recognition tasks  

### Why this is normal  
Face datasets with limited samples per class often cause the model to memorize training data rather than generalize.  
This is a realistic challenge in computer vision and strengthens the learning value of the project.

---

## 🔍 Key Features

- Image preprocessing (resize, normalization, encoding)  
- Custom CNN architecture implemented from scratch  
- Training on labelled face images  
- Accuracy & loss visualization  
- Classification report with precision, recall, and F1-score  
- Discussion of overfitting and future improvements  

---

## 🛠️ Requirements

Install the typical dependencies:

```
numpy  
pandas  
matplotlib  
tensorflow  
opencv-python  
sklearn  
```

If your notebook uses more, they can be added.

---

## ▶️ How to Run

1️⃣ **Clone the repository**

```bash
git clone https://github.com/Sailaja-ASB/Face-Recognition-Project.git
cd Face-Recognition-Project
```

2️⃣ **Install dependencies**

```bash
pip install -r requirements.txt
```

3️⃣ **Open the notebook**

```bash
jupyter notebook "Face-Recognition.ipynb"
```

*(Face-Recognition-Project.ipynb)*

---

## 🚀 Future Improvements

To reduce overfitting & improve validation accuracy:

- Add image augmentation (rotation, zoom, brightness, flip)  
- Add **dropout** and **L2 regularization**  
- Increase dataset size  
- Use **transfer learning** (MobileNetV2, VGG16, ResNet50)  
- Apply **EarlyStopping** callback  
- Balance dataset classes  

---

## 👩‍💻 Author

**Sailaja Morrennagari**  
GitHub: https://github.com/Sailaja-ASB  
LinkedIn: https://www.linkedin.com/in/sailajamorrennagari  

