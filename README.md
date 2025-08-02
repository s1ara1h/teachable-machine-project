# Kidney Classification using Teachable Machine

This project applies image classification to detect four kidney conditions using Google's Teachable Machine.  
It was implemented as part of a data analysis and AI training program.

## 🧪 Classes
The model classifies kidney ultrasound images into the following categories:
- Normal
- Kidney Cyst
- Kidney Stone
- Kidney Tumor

## 📂 Dataset
The dataset is a curated subset of a larger dataset available on [Kaggle](https://www.kaggle.com/), which includes thousands of ultrasound images.  
Only a limited number of images were used for this experiment:
- **Training:** 65 images per class  
- **Testing:** A few unseen images per class (manually selected)

The dataset was organized into `train/` and `test/` folders and used directly in Teachable Machine's image project interface.

## 📊 Results
Screenshots in the `screenshots/` folder show:
- Sample predictions from the model on test images  
- Classification results with confidence levels  
- Preview of the trained model in Teachable Machine

## 🛠️ Tools
- [Teachable Machine](https://teachablemachine.withgoogle.com/)
- Google Chrome for testing and screen capture


