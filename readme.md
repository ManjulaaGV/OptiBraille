# OptiBraille  
### AI-Powered Braille Recognition System using Computer Vision

---

## Abstract

OptiBraille is a deep learning–based computer vision system designed to recognize and translate Braille patterns into readable digital text. The project aims to bridge the accessibility gap for visually impaired communities by enabling automated interpretation of Braille documents using image processing and neural network architectures.

This system focuses on accurate Braille dot detection, robust feature extraction, and high-performance classification under varying lighting and noise conditions.

---

## Problem Statement

Despite Braille being a critical literacy medium for visually impaired individuals, digitizing physical Braille documents remains challenging.

Key difficulties include:
- Variations in lighting conditions
- Image noise
- Dot spacing inconsistencies
- Partial occlusions

OptiBraille addresses these challenges using a structured computer vision pipeline combined with deep learning.

---

##  Proposed Solution

The system performs:

1. **Image Acquisition**
2. **Preprocessing**
   - Grayscale conversion
   - Noise reduction
   - Thresholding
3. **Braille Dot Detection**
4. **Feature Extraction**
5. **Neural Network Classification**
6. **Character-to-Text Conversion**

---

##  Model Architecture

![Model Architecture](model_architecture.png)


<img width="757" height="1353" alt="image" src="https://github.com/user-attachments/assets/7283d8c7-837b-422f-b82d-9c872bc4df30" />


The classification model leverages a convolutional neural network architecture optimized for:
- Spatial feature extraction
- Pattern generalization
- Robust classification accuracy

---

## Experimental Results

![Results](results.png)


<img width="1000" height="800" alt="image" src="https://github.com/user-attachments/assets/901ec7c1-d8c8-421c-956c-94c4e4fe1ba9" />


- High classification accuracy achieved on validation data
- Stable performance under illumination variations
- Low misclassification rate across tested samples

---

##  Sample Predictions

![Predictions](sample_predictions.png)


<img width="1200" height="1000" alt="image" src="https://github.com/user-attachments/assets/b2edff5a-c65d-423f-b27b-308c881c327f" />


The model successfully converts detected Braille cells into readable alphanumeric output.

---

## 🛠 Tech Stack

- Python
- OpenCV
- NumPy
- TensorFlow / PyTorch
- Matplotlib
- Google Colab

---

##  Innovation Highlights

✔ Automated Braille-to-text conversion  
✔ Noise-robust preprocessing pipeline  
✔ Optimized CNN-based classification  
✔ End-to-end recognition pipeline  

---

##  Future Work

- Mobile application deployment  
- Real-time Braille scanning  
- Multi-language Braille support  
- Edge-device optimization  

---

##  Code Availability

The complete training pipeline and implementation are not publicly available.

For academic collaboration or demonstration inquiries, please contact the author.

---

##  Author
Manjulaa G V
SRM Institute of Science and Technology

**Manjulaa GV**  
Artificial Intelligence & Machine Learning Enthusiast  
Focused on Accessible AI Solutions
