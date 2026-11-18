# Human Gender Detection Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify human facial images into two categories: **Male** and **Female**.

The model is trained on facial image data and uses deep learning techniques to learn visual features for gender classification.

## Technologies Used
- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Features
- Facial image preprocessing and normalization
- Custom CNN architecture with 3 convolutional layers
- Dropout for reducing overfitting
- Face detection and cropping using OpenCV Haar Cascade
- Gender classification with confidence scores
- Model performance evaluation

## Dataset
The project uses a facial image dataset containing two categories:
- Man
- Women

The images were resized to 64 × 64 pixels and normalized before training.

**Note:** The dataset ZIP file is not included in this repository because of its large file size. It is stored locally.

## Model Details
- Model: Custom Convolutional Neural Network (CNN)
- Train-test split: 80:20
- Data split: Stratified
- Input image size: 64 × 64 pixels

## Model Performance
- Test Accuracy: **91.9%**
- Macro F1-Score: **0.91**

## Project Structure
```text
Gender_Detection_Using_CNN/
│
├── notebook/
│   └── Human_Gender_Detection_Using_CNN_Model.ipynb
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

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/kagawadesneha1104-ai/Gender_Detection_Using_CNN.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Gender_Detection_Using_CNN
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Download or place the dataset locally and prepare the required folder structure.
5. Open the Jupyter Notebook and run the cells.

## Results
The CNN model achieved 91.9% test accuracy and a macro F1-score of 0.91 on the test dataset.

## Author
**Sneha Bahubali Kagawade**

GitHub: [kagawadesneha1104-ai](https://github.com/kagawadesneha1104-ai)
