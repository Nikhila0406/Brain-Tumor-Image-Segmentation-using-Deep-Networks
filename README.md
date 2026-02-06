# Brain Tumor Image Segmentation Using Deep Networks

##  Overview
Brain tumor detection is a critical task in medical image analysis. 
This project uses a Convolutional Neural Network (CNN) model to analyze brain medical images and determine whether a patient has a brain tumor or not.

The system processes medical images, performs segmentation, and provides prediction results along with Dice Similarity Score for performance evaluation.

---

##  Problem Statement
Early detection of brain tumors is essential for proper treatment planning. 
Manual examination of medical images can be time-consuming and requires expert knowledge. 

This project aims to automate brain tumor detection using deep learning techniques to assist in faster and more accurate diagnosis.

---

##  Methodology

1. Input medical images (X-ray / MRI images) are collected.
2. Images are preprocessed (resizing, normalization).
3. A Convolutional Neural Network (CNN) model is used for tumor detection and segmentation.
4. The model predicts whether a tumor is present or not.
5. Segmentation output is generated.
6. Dice Similarity Coefficient is calculated to evaluate model performance.

---

##  Technologies Used
- Python
- Convolutional Neural Networks (CNN)
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

---

##  Project Structure
- BrainTumour.py
- test.py
- test1.py
- test2.py
- run (execution file)
- requirements.txt
- sample_images/

---

##  How to Run the Project

1. Install required libraries:
   pip install -r requirements.txt

2. Run the execution file:
   run

(The run file will execute the complete project workflow.)

---

##  Dataset
The project uses a Brain Tumor medical image dataset from Kaggle for training and testing.

---

##  Results
- The system predicts whether the patient has a brain tumor or not.
- Segmented output images are generated.
- Model performance is evaluated using Dice Similarity Score.

---

##  Future Improvements
- Improve segmentation accuracy using advanced architectures like U-Net.
- Deploy as a web-based application for clinical usage.
- Integrate real-time medical image analysis.

