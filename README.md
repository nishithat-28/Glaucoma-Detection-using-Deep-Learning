# **📌 Glaucoma Detection using Deep Learning**
🔬 **Early diagnosis of glaucoma is crucial to prevent vision loss!** This project leverages **Deep Learning (ResNet50)** for automated glaucoma detection using fundus images.



## **🚀 Project Overview**
Glaucoma is a **chronic eye disease** that damages the **optic nerve**, leading to irreversible blindness if untreated. Our project uses a **Convolutional Neural Network (CNN)** based on **ResNet50** to classify images into:

✅ **Normal**  

⚠️ **Glaucoma-Affected**



## **🛠️ Tech Stack**
- **Programming Language:** Python 🐍  
- **Deep Learning Framework:** TensorFlow & Keras 🔥  
- **Model Architecture:** ResNet50 🏗️  
- **Preprocessing:** OpenCV (CLAHE, Image Augmentation) 📸  
- **Deployment:** Streamlit 🎛️  



## **📂 Dataset**
We used **3 combined datasets** containing **fundus images** labeled as:
- **"Normal"** 🟢 (Healthy eyes)
- **"Glaucoma"** 🔴 (Affected eyes)

📌 **Preprocessing Techniques:**  
✅ **CLAHE** - Enhances contrast  
✅ **Data Augmentation** - Random rotations, translations  
✅ **Resizing** - Standardizing images to **256x256**  



## **📊 Model Training**
We fine-tuned **ResNet50** (pretrained on ImageNet) by:
- Freezing initial layers  
- Fine-tuning the last **10 layers**  
- Using **Adam Optimizer** with **learning rate = 0.0001**  

## **🔢 Training Results**
- **Final Training Accuracy:** **88.06%**
- **Final Validation Accuracy:** **85.96%**
- **Test Accuracy:** **81.37%**

📈 **Confusion Matrix & Classification Report:**  
The model achieves high **precision** and **recall**, making it reliable for real-world usage.



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
🔍 **Upload a fundus image**  
🖼️ **Preview the image**  
🧠 **Get instant glaucoma detection results**  





