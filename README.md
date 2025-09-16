# 🧠 Stroke-Detection-CNN
Convolutional Neural Network (CNN) model for stroke detection using facial images.  

## 📌 Overview
This project explores the use of **Convolutional Neural Networks (CNNs)** to detect stroke risk by analyzing **facial expression images**.  
Unlike traditional stroke detection approaches that rely on **CT/MRI scans** or **tabular patient data**, this project focuses on **facial features** — making it a novel direction for early stroke screening and AI-based diagnostics.  

## ⚙️ Features
- Preprocessing of facial stroke/non-stroke image datasets  
- CNN-based deep learning model for classification  
- Training on stroke vs. non-stroke images  
- Testing on an external dataset to validate generalization  
- Performance evaluation with accuracy metrics  

## 📂 Datasets
- [Face Images of Acute Stroke and Non-Acute Stroke (Kaggle)](https://www.kaggle.com/datasets/danish003/face-images-of-acute-stroke-and-non-acute-stroke)  
- [Facial Droop and Facial Paralysis Image Dataset (Kaggle)](https://www.kaggle.com/datasets/kaitavmehta/facial-droop-and-facial-paralysis-image?select=Strokefaces)  

*(All dataset credits to respective Kaggle contributors)*  

## 🚀 How to Run
1. Open `stroke_detection_cnn.ipynb` in **Google Colab**.  
2. Upload/download the dataset as instructed in the notebook.  
3. Run all cells to train and evaluate the CNN model.  
4. View predictions and performance results.  

## 📊 Results
- CNN model trained on facial images achieved the following on the training dataset.
    - Accuracy: 95.58%
    - Precision: 89.69%
    - Recall (Sensitivity): 99.01%
    - F1-score: 94.12%  
- Successfully tested on an **external dataset**.   

## 🧑‍💻 Author
**CodeShockAI** – Biotech graduate exploring AI/ML in healthcare for novel diagnostic solutions.  
