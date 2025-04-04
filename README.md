# **🩺 Glaucoma Detection using Deep Learning**
🔬 **Early diagnosis of glaucoma is crucial to prevent vision loss!** This project leverages **Deep Learning (ResNet50)** for automated glaucoma detection using fundus images.

Glaucoma is a **chronic eye disease** that damages the **optic nerve**, leading to irreversible blindness if untreated. Our project uses a **Convolutional Neural Network (CNN)** based on **ResNet50** to classify images into:
- ✅ **Normal**  
- ⚠️ **Glaucoma-Affected**

## **🛠️ Tech Stack**
- **Programming Language:** Python  
- **Deep Learning Framework:** TensorFlow & Keras   
- **Model Architecture:** ResNet50   
- **Preprocessing:** OpenCV (CLAHE, Image Augmentation)   
- **Deployment:** Streamlit   

## **📂 Dataset**

### 📌 **Source**
- Kaggle: [Glaucoma Classification Datasets](https://www.kaggle.com/datasets/ayush02102001/glaucoma-classification-datasets)

This dataset contains **fundus images** from *3 combined sources** (ACRIMA, DRISHTI-GS, ORIGA). It includes:
- **"Normal"** 🟢 (Healthy eyes)
- **"Glaucoma"** 🔴 (Affected eyes)

🔄 **Preprocessing Techniques:**  
- **CLAHE** - Enhances contrast  
- **Image Augmentation** -  Random rotations, flips, and zooms to improve generalization
- **Resizing** - Standardizing images to **256x256**  

## **🔢 Training Results**
- **Final Training Accuracy:** **98.86%**
- **Final Validation Accuracy:** **88.89%**
- **Test Accuracy:** **77.64%**

## **📌 How to Run the Project**
### **🔧 Install Dependencies**
```sh
pip install -r requirements.txt
```

### **🏃 Run the Streamlit App**
```sh
python -m streamlit run app.py
```

## **🎛️ Streamlit UI**
We developed an **interactive UI** using **Streamlit**, allowing users to:
- 🔍 **Upload a fundus image**  
- 🖼️ **Preview the image**  
- 🧠 **Get instant glaucoma detection results with confidence score**  





