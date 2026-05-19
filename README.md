# CodeAlpha_TASK_3_HandwrittenCharacterRecognition
# Handwritten Character Recognition using CNN

## Project Overview

This project focuses on recognizing handwritten digits using Deep Learning and Convolutional Neural Networks (CNN). The model is trained on the MNIST dataset and can accurately classify handwritten digits from 0–9.

This project was developed as part of the CodeAlpha Machine Learning Internship.

---

## Objective

To build a deep learning model that identifies handwritten characters from images using image processing and CNN techniques.

---

## Dataset

Dataset Used: MNIST Handwritten Digits Dataset

Dataset Information:

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Classes: 10 digits (0–9)

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn

---

## Project Workflow

1. Load MNIST Dataset
2. Visualize Sample Images
3. Normalize Pixel Values
4. Reshape Images for CNN Input
5. Convert Labels using One-Hot Encoding
6. Build CNN Model
7. Train Model
8. Evaluate Performance
9. Make Predictions
10. Save Trained Model

---

## CNN Architecture

Input Layer (28×28×1)

↓

Conv2D (32 filters, 3×3)

↓

MaxPooling2D

↓

Conv2D (64 filters, 3×3)

↓

MaxPooling2D

↓

Flatten Layer

↓

Dense Layer (128 neurons)

↓

Dropout (0.3)

↓

Output Layer (Softmax)

---

## Model Performance

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score

Final Test Accuracy:

**98–99%**

(Note: Accuracy may vary slightly depending on training runs.)

---

## Visualizations

The project includes:

- Training Accuracy Curve
- Loss Curve
- Confusion Matrix
- Sample Predictions

---

## Files Included

```text
handwritten_character_recognition.ipynb
handwritten_model.h5
requirements.txt
README.md
images/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/CodeAlpha_HandwrittenCharacterRecognition.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Use EMNIST dataset for alphabet recognition
- Build real-time handwriting recognition using OpenCV
- Extend to sentence recognition using CRNN
- Deploy as a web application using Streamlit

---

## Conclusion

The CNN model successfully recognized handwritten digits with high accuracy. This project demonstrates the effectiveness of Convolutional Neural Networks in image classification tasks and provides a foundation for more advanced handwriting recognition systems.

---

## Author

Veldandi Prakarsha

Machine Learning Intern — CodeAlpha
