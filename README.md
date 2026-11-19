# 📊 Human Gender Detection Using CNN

Human Gender Detection Using CNN is a deep learning project that classifies facial images into two categories: **Male** and **Female** using a custom Convolutional Neural Network (CNN).

The project uses Python, TensorFlow, Keras, and OpenCV to preprocess facial images, train a CNN model, evaluate its performance, and detect faces for gender classification.

The model was trained on a dataset containing **27,167 facial images** and achieved **91.9% test accuracy** with a **0.91 macro F1-score**.

---

## 🚀 Core Features

The project implements a complete deep learning workflow:

### Data Preprocessing
- Loaded and processed facial image data.
- Organized images into Male and Female categories.
- Resized images to 64 × 64 pixels.
- Normalized pixel values for model training.
- Applied stratified 80:20 train-test splitting.

### CNN Model Development
- Built a custom Convolutional Neural Network.
- Implemented 3 convolutional layers for feature extraction.
- Used dropout layers to help reduce overfitting.
- Trained the model using TensorFlow and Keras.
- Evaluated model performance on test data.

### Face Detection
- Implemented face detection using OpenCV Haar Cascade.
- Detected and cropped facial regions from input images.
- Prepared detected faces for CNN prediction.

### Gender Classification
- Classified facial images into Male and Female categories.
- Generated prediction confidence scores.
- Used the trained CNN model for image classification.

### Model Evaluation
- Evaluated the trained model using test data.
- Analyzed training and validation accuracy.
- Examined training and validation loss.
- Generated a confusion matrix to evaluate classification performance.

---

## 📈 Key Performance Metrics

| Evaluation Metric | Result |
|---|---:|
| Total Facial Images | 27,167 |
| Image Dimensions | 64 × 64 |
| Train-Test Split | 80:20 |
| CNN Convolutional Layers | 3 |
| Test Accuracy | **91.9%** |
| Macro F1-Score | **0.91** |

---

## 🛠️ Technology Stack

| Category | Technology | Description |
|---|---|---|
| Programming Language | Python | Core programming language |
| Deep Learning | TensorFlow | Deep learning framework |
| Neural Networks | Keras | CNN model development |
| Computer Vision | OpenCV | Face detection and image processing |
| Numerical Computing | NumPy | Numerical operations |
| Data Analysis | Pandas | Data handling and processing |
| Visualization | Matplotlib | Training and evaluation visualizations |
| Development Environment | Jupyter Notebook | Model development and experimentation |

---

## 📂 Project Structure

```text
Gender_Detection_Using_CNN/
│
├── documentation/
│   └── Gender_Detection_CNN_Report.pdf
│
├── notebook/
│   └── Human_Gender_Detection_Using_CNN.ipynb
│
├── presentation/
│   └── Gender_Detection_CNN_Presentation.pptx
│
├── screenshots/
│   ├── CNN Training and Validation Accuracy.png
│   ├── CNN Training and Validation Loss.png
│   └── Confusion Matrix - CNN.png
│
├── .gitignore
├── README.md
└── requirements.txt
```

**Note:** The dataset ZIP file is excluded from this GitHub repository because of its large file size. It is stored locally and is not deleted.

---

## 🔄 Deep Learning Workflow

```text
Facial Image Dataset
        ↓
Data Loading
        ↓
Image Preprocessing
        ↓
Image Resizing (64 × 64)
        ↓
Pixel Normalization
        ↓
Stratified Train-Test Split
        ↓
CNN Model Development
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Face Detection using OpenCV
        ↓
Gender Classification
        ↓
Prediction Confidence
```

---

## 🧹 Data Preprocessing

The facial image dataset was prepared for CNN model training through the following steps:

- Loaded facial images from the dataset.
- Organized images into Male and Female categories.
- Resized images to 64 × 64 pixels.
- Normalized pixel values.
- Prepared image arrays for model input.
- Split the dataset into training and testing sets using an 80:20 stratified split.

---

## 🧠 CNN Model Architecture

A custom Convolutional Neural Network was developed for facial image classification.

The model includes:

- **Convolutional Layers:** Three convolutional layers for extracting facial features.
- **Dropout:** Used to help reduce overfitting during training.
- **Classification Layer:** Predicts one of the two dataset categories.

The model was developed and trained using TensorFlow and Keras.

---

## 📊 Model Evaluation & Visualization

The trained model was evaluated using test data and performance metrics.

The project includes the following visualizations:

1. CNN Training and Validation Accuracy
2. CNN Training and Validation Loss
3. Confusion Matrix

These visualizations help understand model learning performance and classification results.

---

## 👤 Face Detection Using OpenCV

OpenCV Haar Cascade was used to detect faces from input images.

The face detection workflow includes:

- Detecting facial regions in input images.
- Cropping detected faces.
- Preparing cropped images for CNN prediction.
- Generating gender classification predictions with confidence scores.

---

## 💡 Key Outcomes

The project successfully demonstrates a deep learning-based facial image classification workflow.

Major outcomes:

- Processed 27,167 facial images.
- Developed a custom CNN with 3 convolutional layers.
- Applied image preprocessing and normalization.
- Implemented stratified 80:20 train-test splitting.
- Achieved 91.9% test accuracy.
- Obtained a macro F1-score of 0.91.
- Implemented face detection using OpenCV Haar Cascade.
- Generated training, validation, and confusion matrix visualizations.

---

## 📦 Requirements

The project uses the following Python libraries:

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/kagawadesneha1104-ai/Gender_Detection_Using_CNN.git
cd Gender_Detection_Using_CNN
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Prepare the Dataset

The dataset ZIP file is not included in the repository.

Place the dataset in the appropriate local folder and ensure the notebook dataset paths match your local directory structure.

### 4️⃣ Start Jupyter Notebook

```bash
jupyter notebook
```

### 5️⃣ Open the CNN Notebook

Open:

`notebook/Human_Gender_Detection_Using_CNN_Model.ipynb`

Run the notebook cells sequentially to reproduce the preprocessing, model training, and evaluation workflow.

---

## 🎯 Project Objective

The primary objective of this project is to demonstrate the application of Convolutional Neural Networks and computer vision techniques for facial image classification.

The project showcases practical skills in image preprocessing, CNN architecture development, deep learning model training, model evaluation, and face detection using OpenCV.

---

## 👩‍💻 Author

**Sneha Bahubali Kagawade**

GitHub: [kagawadesneha1104-ai](https://github.com/kagawadesneha1104-ai)
