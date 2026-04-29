#  Lung Cancer Detection using Deep Learning

##  Overview
This project focuses on detecting lung cancer from CT scan images using deep learning techniques. The system leverages advanced Convolutional Neural Networks (CNNs) and architectures like ResNet and EfficientNet to classify lung conditions into **Normal, Benign, and Malignant** categories.

The goal is to assist in **early diagnosis**, improve accuracy, and reduce the workload on radiologists.

---

##  Features
-  CT Scan Image Classification  
-  Deep Learning Models (CNN, ResNet, EfficientNet)  
-  Data Augmentation & Preprocessing  
-  Handling Class Imbalance  
-  Performance Evaluation (Accuracy, Precision, Recall, F1-Score)  
-  Medical-focused prediction system  

---

##  Dataset
- **Name:** LIDC-IDRI (Lung Image Database Consortium and Image Database Resource Initiative)  
- Contains annotated lung CT scans  
- Provided by expert radiologists  
- Includes nodule locations and malignancy ratings  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow / PyTorch, NumPy, OpenCV, Matplotlib  
- **Tools:** Jupyter Notebook / Google Colab  

---

## ⚙️ Methodology

1. **Data Acquisition**  
   - CT scan images collected from LIDC-IDRI dataset  

2. **Preprocessing**  
   - Hounsfield Unit normalization  
   - Image resizing and augmentation  

3. **Feature Extraction**  
   - CNN / ResNet / EfficientNet used to extract deep features  

4. **Classification**  
   - Softmax layer classifies into:
     - Normal  
     - Benign  
     - Malignant  

5. **Evaluation**  
   - Metrics used:
     - Accuracy  
     - Precision  
     - Recall (Sensitivity)  
     - F1-Score  

---

## 📊 Results
- Achieved strong classification performance on CT scan images  
- Improved detection of cancerous cases using class balancing techniques  
- Reduced false negatives (critical in medical diagnosis)  

> *(Update this section with your actual model accuracy and results)*

---

##  How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/lung-cancer-detection.git

# Navigate to project folder
cd lung-cancer-detection

# Install dependencies
pip install -r requirements.txt

# Run the model
python main.py
