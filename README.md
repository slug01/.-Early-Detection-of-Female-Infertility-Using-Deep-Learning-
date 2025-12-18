🧬 Early Detection of Female Infertility Using Deep Learning
Inception & Xception with Attention Mechanisms
📌 Overview

This repository contains my MSc Computer Science dissertation project, which focuses on the early detection of infertility-related conditions in women using ultrasound imaging and deep learning techniques. The study leverages InceptionV3 and Xception architectures enhanced with attention mechanisms to improve diagnostic accuracy, robustness, and interpretability.

The project demonstrates an end-to-end machine learning pipeline, from data preprocessing and model training to evaluation and explainability, aimed at supporting non-invasive, AI-driven clinical decision-making.

🎯 Research Objectives

Develop deep learning models for early infertility detection using ultrasound images

Enhance feature extraction using attention mechanisms

Improve diagnostic accuracy, precision, recall, and interpretability

Compare baseline CNN models with attention-augmented architectures

Address ethical considerations in medical AI applications

🧠 Methodology

Data Preprocessing
      Image resizing and normalization
      Data augmentation (rotation, zoom, flipping, brightness adjustment)
      Duplicate image removal using perceptual hashing

Model Architectures
      InceptionV3
      Xception
      Inception + Attention
      Xception + Attention
      
Training Strategy
      Transfer learning (ImageNet weights)
      Cross-validation
      Adam optimizer with tuned hyperparameters
      
Evaluation Metrics
      Accuracy, Precision, Recall, F1-score
      ROC-AUC
      Confusion Matrix

📊 Key Results
Xception with Attention achieved the best performance
Accuracy reached ~95% with strong precision and recall
Attention mechanisms improved:
Model stability
Focus on clinically relevant regions
Interpretability via visual explanations (Grad-CAM)

🔍 Model Explainability
To address the “black-box” nature of deep learning:
Attention layers highlight diagnostically relevant regions
Grad-CAM visualizations show how the model makes predictions
Supports transparency and clinical trust

🛠️ Tech Stack

Programming: Python
Deep Learning: TensorFlow, Keras
Data Handling: NumPy, Pandas
Computer Vision: OpenCV
Visualization: Matplotlib, Seaborn
Environment: Jupyter Notebook / Google Colab

⚖️ Ethical Considerations
Used anonymized, publicly available datasets
Followed GDPR and HIPAA principles
Focused on responsible AI deployment and bias awareness
AI is positioned as decision-support, not a replacement for clinicians



👤 Author

Arabindra Dhami
MSc Computer Science
York St John University

📧 Email: arabindradhami11@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/arabindra-dhami-a00906216/
