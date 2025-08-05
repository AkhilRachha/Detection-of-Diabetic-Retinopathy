# Detection of Diabetic Retinopathy Using Machine Learning

This project provides a web-based tool to detect diabetic retinopathy using deep learning techniques. It uses a fine-tuned VGG16 model trained on labeled retina images to classify the severity into one of the following categories:
- No_DR
- Mild
- Moderate
- ERRORDATA

## 🚀 Features
- Retina image upload and classification
- Real-time prediction with confidence score
- Model performance visualization (Accuracy, Precision, Recall, F1-Score)
- Confusion Matrix and Chart
- User-friendly Flask web interface

## 🧠 Model
- Pretrained VGG16 CNN model
- Fine-tuned with augmented retina images
- Class-weighted loss handling to balance dataset
