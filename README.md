# 🫁 Automatic Image Segmentation for Lung using Deep Learning and CNN
**A deep learning-based project for automatic lung image segmentation using Convolutional Neural Networks (CNN).**

---

## 🚀 **Project Overview**
The main goal of this project is to develop an automated system for **lung image segmentation** using deep learning models. The model employs **Convolutional Neural Networks (CNNs)** to segment the lung from medical images such as CT scans. This model can be used in medical diagnostics to help doctors in identifying lung-related issues, including cancer and pneumonia. This repository contains a deep learning model for **automatic segmentation of lung images**, which is essential for detecting and analyzing lung diseases such as pneumonia, tuberculosis, and COVID-19. The model utilizes **Convolutional Neural Networks (CNN)** for accurate and efficient segmentation. 

✅ **Key Features:**
- Lung image segmentation using **CNN and deep learning** models.
- Supports **Lung CT Scans, X-ray, and other medical images**.
- Utilizes **Git LFS** for large file handling.
- Includes pre-trained models and evaluation metrics.

---

## ⚙️ Prerequisites
Before starting, ensure you have:
- Python 3.7+: Download from [Python's official website](https://www.python.org/downloads/)
- TensorFlow: Install using pip install tensorflow
- Keras: Install using pip install keras
- Git: Download from Git’s official website

---

## 📁 Dataset
- This project uses a publicly available lung CT scan dataset. You can find the dataset here.
  - Datasets: [Lung Image Segmentation Dataset](https://drive.google.com/drive/folders/1F1Sg6Bvdx0YC6Kpj5ycOvAF7KPcFbNso?usp=sharing)
- Make sure to download and place the images in the appropriate folder.
- The dataset contains images of CT scans of the lungs, and the task is to segment out the lungs from the rest of the image.

---

## Model Architecture
The model is based on a Convolutional Neural Network (CNN). It consists of the following layers:
1. Convolutional layers for feature extraction.
2. Max-pooling layers to reduce dimensionality.
3. Fully connected layers for classification.
4. Output layer for segmentation.

The model uses ReLU activation for hidden layers and Sigmoid activation for the output layer.

---

## 🛠️ Setup Instructions
### Step 1: Clone the repository:
```bash
git clone https://github.com/Utsav-Dharani/Automatic-Image-Segmentation-for-Lung-using-Deep-Learning-and-Convolutional-Neural-Network.git
```

### Step 2: Navigate to the project folder:
```bash
cd Automatic-Image-Segmentation-for-Lung-using-Deep-Learning-and-Convolutional-Neural-Network
```

### Step 3: Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run the Model?
### Step 1: Train the Model:
Run main.py to train the model using the lung dataset:
```bash
python main.py
```

### Step 2: Segment Lung Images:
After training, you can use the same main.py file to perform lung image segmentation:
```bash
python main.py --image_path path_to_your_image
```

---

## 🖼️ Results
Here is an example of the output from the lung segmentation model:

- Input Image (CT Scan):
  
  <img src="https://github.com/user-attachments/assets/aa5f998d-51b5-42c4-a931-0c3f50af2007" width="150"/>

  
- Segmented Output Image (Lungs):

  <img src="https://github.com/user-attachments/assets/9e9600fa-a3e6-4ab6-bff2-0cab1f5a3d30" width="300"/>


These images demonstrate the ability of the model to correctly segment lung regions from CT scans, enabling automated lung disease diagnosis.



---

## 📝 License
This project is licensed under the MIT License 🔓. Check the LICENSE file for more info.

---

## 🔮 Future Work
- Enhance the model to detect more lung diseases 💔.
- Improve the CNN model for higher accuracy 🎯.
- Integrate into a web or mobile app for real-time diagnostics 📱.

---

## 🙏 Acknowledgements
- TensorFlow and Keras for providing the powerful libraries and tools used to build the deep learning models in this project.
- Open source contributors for datasets and research that inspired the architecture and methods used.
- Google Drive for hosting the dataset used in this project.
- The medical community for continuous advancements in medical image analysis, aiding early detection and diagnosis of diseases.

---

## 📞 Contact
For inquiries or feedback, please contact:
- Name: Utsav Dharani
- Email: utsavdharani96@gmail.com

---

## ✍️ Signature
- This project is developed and maintained by Utsav Dharani.
- Date: March 2023 - September 2023

---


  
