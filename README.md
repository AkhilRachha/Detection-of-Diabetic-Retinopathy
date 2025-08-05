# Detection of Diabetic Retinopathy Using Machine Learning

## Pre-trained Models & Dataset

The trained model files and dataset are too large for GitHub.  
You can download them here:

- [Model: dr_model.h5]([https://drive.google.com/your_model_link](https://drive.google.com/file/d/1ahy-YAmKo3V1JsodIVvIgVh4S5sQhIO3/view?usp=drive_link))
- [Model: vgg16_weights_tf_dim_ordering_tf_kernels_notop.h5](https://drive.google.com/file/d/161Q5vtcYVtbztlIFxKBW466zHEcNgo1X/view?usp=drive_link))
- [Dataset]([https://drive.google.com/drive/folders/1M4wGg8YuCDB0B2wYyu8wXvFQfKiCsPxB?usp=drive_link])

After downloading, place them in the following directories:

---

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
