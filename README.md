# FaceBlur  
AI Privacy Filter for Sensitive Images  

## 📌 Overview  
FaceBlur is an AI-powered system that detects and protects sensitive information in images, such as ID cards, passports, and faces. It uses computer vision to identify these regions and applies automatic blurring, ensuring user privacy in both static images and live video feeds.  

## ✨ Features  
- Detects sensitive regions (faces, ID cards, passports)  
- Automatically applies blur to hide private information  
- Works on both images and real-time camera streams  
- Includes visualization tools for bounding boxes and brightness analysis  

## 🗂 Dataset 

The dataset used in this project is available on Hugging Face:

👉 [TrialforGeneratedIDs on Hugging Face](https://huggingface.co/datasets/AmAFakePerson123/TrialforGeneratedIDs)

### Description
- **Size:** 3,000 images  
- **Format:** Images (JPG/PNG) + VGG Image Annotator (VIA) JSON annotations  
- **Classes:** 10 types of ID cards and passports  
- **Variants:** Templates, upright scans, rotated scans, and real photos  

⚠️ Note: The dataset is hosted externally and **not included directly** in this repository.  

## 🚀 Project Workflow  
1. **Data Preparation & Visualization**  
2. **Model Training**
3.  **Testing & Evaluation**
4. **Deployment & Execution**  


## 📊 Visualizations  
- **Bounding Box Analysis** → checks annotation quality  
- **Aspect Ratios** → identifies object shapes  
- **Brightness Comparison** → face vs document lighting across datasets  

Example output plots:  
## **Bounding Box Scatter**![WhatsApp Image 2025-08-20 at 09 28 24](https://github.com/user-attachments/assets/c48f5222-91e5-477c-a6a1-c2a1a8a22160)

## **Brightness Comparison**![WhatsApp Image 2025-08-20 at 09 28 34](https://github.com/user-attachments/assets/a2c50a08-5e27-410f-aaa2-b0df2a9304c8)

