# Home Assignment 2 - Convolution, Sobel Filtering, and Data Normalization

## Student Info
**Name:** CHINTALA SAI SRAVAN  
**Student ID:** 700773836

---

## Overview

This assignment includes three tasks related to deep learning and machine learning preprocessing techniques:

1. **Convolution Operations with Different Parameters**
2. **Sobel Filtering and Edge Detection**
3. **Data Normalization and Classification**

---

## Task Breakdown

### 🧠 Q1: Convolution with Custom Parameters

- A 5x5 matrix is convolved using a 3x3 kernel.
- Different combinations of stride (`1`, `2`) and padding (`'VALID'`, `'SAME'`) are demonstrated using TensorFlow.
- Output feature maps for each configuration are printed.

**Technologies:** TensorFlow, NumPy

### 🧠 Q2: Sobel Filtering and Edge Detection

- A grayscale image is used to compute horizontal and vertical edge gradients using Sobel filters.
- Edge magnitude is visualized using `matplotlib`.


**Technologies:** OpenCV, NumPy, Matplotlib

### 🧠 Q3: Data Normalization Techniques

- The Iris dataset is normalized using:
  - No normalization (original),
  - StandardScaler (Z-score),
  - MinMaxScaler (0 to 1 scaling).
- Each normalization method is evaluated using Logistic Regression.
- Accuracy, confusion matrix, and classification report are printed.
- Feature distributions are visualized using histograms.

**Technologies:** scikit-learn, Matplotlib

---

## Running Instructions

1. Make sure you have the required dependencies:
    ```bash
    pip install numpy tensorflow scikit-learn opencv-python matplotlib
    ```

2. Place `test_image.jpg` in the same folder as `Home Assignment 2 Solution.py`.

3. Run the Python script:
    ```bash
    python "Home Assignment 2 Solution.py"
    ```

---

## Output Demonstration

This script will output:
- 2D convolution feature maps under different stride and padding conditions.
- Visualizations of Sobel-filtered images.
- Histograms for each normalization technique.
- Accuracy and detailed classification metrics for each preprocessing method.

---

## Video Submission

A short 2–3 minute video is created showing:
- Code walkthrough
- Visual output demonstration
- Explanation of the results for each task

---

## Comments

- All major code blocks are commented for better clarity.
- File is organized into clear sections for each question.

---

## Submission Checklist

- ✅ Code pushed to GitHub repository.
- ✅ Student details added to this README.
- ✅ Code thoroughly commented.
- ✅ Output demo video recorded and submitted via Brightspace.
