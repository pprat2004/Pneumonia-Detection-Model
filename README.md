#Pneumonia Detection Using Deep Learning
This repository presents a complete deep learning pipeline for detecting pneumonia from chest X-ray images using Convolutional Neural Networks (CNNs). The project emphasizes reliability, strong evaluation, and clinical relevance, demonstrating the ability to build production-ready machine learning systems for healthcare.

##Project Overview
Pneumonia is a critical global health concern, and early identification significantly improves treatment outcomes. This project leverages modern computer vision techniques to classify chest X-ray images as Pneumonia or Normal. The workflow includes data preprocessing, augmentation, model training, evaluation, and threshold optimization for improved decision-making.

##Key Features
End-to-end deep learning pipeline using TensorFlow/Keras
Comprehensive data preprocessing and augmentation
Model performance analyzed using AUC, Cohen’s Kappa, Precision, Recall, and F1-score
Threshold tuning to maximize diagnostic reliability
Training metrics visualized for interpretability
Configurable and ready for deployment or further research

##Model Performance
###The final model achieved the following results on the test dataset:
Best threshold for Cohen's Kappa: 0.900
Cohen’s Kappa Score: 0.5375
Test AUC: 0.8990247644093798
Test F1-score: 0.856156501726122
Precision: 0.7766179540709812
Recall: 0.9538461538461539
Cohen’s Kappa (post thresholding): 0.5374653098982424

These results indicate a high-sensitivity model capable of detecting pneumonia effectively while maintaining strong overall diagnostic performance.

##Getting Started
Clone the repository
Install dependencies
Place or download the dataset into your working directory
Run the training notebook or scripts

pip install -r requirements.txt

##Future Improvements
Integration of attention-based architectures
Transfer learning experiments with advanced CNN backbones
Deployment using FastAPI, Streamlit, or Flask
Model explainability using Grad-CAM or similar methods

##Purpose
This project demonstrates strong technical capability in deep learning, medical imaging, model evaluation, and reproducibility. It reflects practical engineering skills and an understanding of real-world machine learning challenges, especially in safety-critical domains like healthcare.

##License
This project is licensed under the MIT License.
