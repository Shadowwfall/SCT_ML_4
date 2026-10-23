# SCT_ML_4
my 4th internship project!!
# ✋ SCT_ML_4 - Hand Gesture Recognition Using Convolutional Neural Networks (CNN)

This repository contains my **Task 4** submission for the **SkillCraft Technology Machine Learning Internship**.

The project uses a **Convolutional Neural Network (CNN)** to recognize different hand gestures from images. The model is trained on the **LeapGestRecog** dataset and can classify hand gestures into multiple categories.

---

# 📌 Project Objective

The objective of this project is to develop a deep learning model capable of recognizing various hand gestures from images using a Convolutional Neural Network (CNN).

Hand gesture recognition has applications in:

- Human-Computer Interaction
- Sign Language Recognition
- Virtual Reality
- Robotics
- Smart Devices
- Touchless Interfaces

---

# 📂 Dataset

**Dataset:** LeapGestRecog

The dataset contains thousands of images representing different hand gestures performed by multiple individuals.

### Gesture Classes

- Palm
- L
- Fist
- Fist Moved
- Thumb
- Index
- OK
- Palm Moved
- C
- Down

---

# 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- TensorFlow / Keras
- Scikit-learn
- KaggleHub
- Jupyter Notebook

---

# 🚀 Project Workflow

1. Import required libraries
2. Download the dataset using KaggleHub
3. Load gesture images
4. Resize images to **64 × 64**
5. Normalize pixel values
6. Encode gesture labels
7. Split data into training and testing sets
8. Build a CNN model
9. Train the model
10. Evaluate model performance
11. Predict hand gestures

---

# 🧠 Deep Learning Model

The CNN model consists of:

- Convolution Layers
- Max Pooling Layers
- Flatten Layer
- Dense Layers
- Softmax Output Layer

The model is trained using the **Adam Optimizer** and **Categorical Crossentropy Loss Function**.

---

# 📸 Project Results

### Dataset Preview

```markdown
![Dataset Preview](images/dataset_preview.png)
```

---

### Model Training

```markdown
![Training Accuracy](images/training_accuracy.png)
```

---

### Prediction Results

```markdown
![Prediction](images/prediction_results.png)
```

---

# 📁 Repository Structure

```
SCT_ML_4/
│
├── HandGestures.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```

---

# ▶️ Installation

Clone this repository

```bash
git clone https://github.com/shadowwfall/SCT_ML_4.git
```

Navigate to the project

```bash
cd SCT_ML_4
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

# 🎯 Future Improvements

- Improve model accuracy using data augmentation
- Train on larger gesture datasets
- Add real-time webcam prediction
- Deploy using Streamlit or Gradio
- Convert the model to TensorFlow Lite for mobile applications

---

# 📚 Learning Outcomes

Through this project, I learned:

- Image preprocessing using OpenCV
- Data normalization
- Building Convolutional Neural Networks
- Image classification using TensorFlow/Keras
- Training and evaluating deep learning models
- Gesture recognition techniques

---

# 👨‍💻 Author

**Prakhar Kaushik**

---

# 🙏 Acknowledgement

This project was completed as part of the **SkillCraft Technology Machine Learning Internship – Task 4**.

---
