# Alzhimers Detection Using Matlab And Weka
## 🧠 Alzheimer's Disease Detection Using Machine Learning

This project aims to detect Alzheimer's Disease at early stages by applying machine learning techniques to both image-based and text-based datasets. It utilizes classification, clustering, and image processing methods to differentiate between normal and affected subjects.

---

## 🔍 Overview

Alzheimer’s Disease is a progressive neurodegenerative disorder characterized by memory loss and cognitive decline. Early detection is critical but often challenging. This project addresses that challenge by applying machine learning algorithms to identify patterns and features from medical imaging and clinical data.

---

## 🧪 Datasets Used

- **ADNI (Alzheimer's Disease Neuroimaging Initiative)**  
  - MRI images of the brain used for image-based analysis.
  - Five classes: CN (Cognitive Normal), EMCI, LMCI, MCI, AD.

- **OASIS & Kaggle Datasets**  
  - Structured, textual clinical data for classification and association rule mining.

---

## 🧰 Tools & Technologies

- 🧠 **Machine Learning:** KNN, Random Forest, Decision Tree  
- 📊 **Unsupervised Learning:** K-means, K-medoids, Association Rule Mining  
- 📸 **Deep Learning Models:** AlexNet, SqueezeNet (Convolutional Neural Networks)  
- 🧩 **Image Processing:** Skull stripping, segmentation, hippocampus ROI extraction  
- 🧪 **Feature Extraction:** GLCM, shape, texture, histogram-based features  
- ⚙️ **Tools Used:** WEKA, MATLAB, Eclipse, Google Colab

---

## 🧬 Methodology

### 1. **Preprocessing**
- Skull stripping using thresholding and morphological operations.
- Image enhancement and removal of noise.
- Manual and clustering-based segmentation of the hippocampus region.

### 2. **Feature Extraction**
- Extract statistical, texture, and histogram features from segmented images.
- Focused on the hippocampus region which is most indicative of Alzheimer's.

### 3. **Classification**
- Supervised models like KNN, Random Forest, Decision Tree applied on structured data and extracted features.
- CNNs (AlexNet & SqueezeNet) used for image classification based on MRI data.

### 4. **Clustering & Association Rule Mining**
- Unsupervised learning used to find groupings and correlations in textual datasets.
- Association rules help identify frequent patterns and relationships between symptoms and diagnosis.

---

## 🎯 Objectives

- Classify subjects as **Alzheimer’s Patient** or **Normal** based on image and clinical features.
- Detect the **hippocampus** region and use it as the key ROI for diagnosis.
- Improve diagnostic accuracy using both supervised and unsupervised methods.
- Encourage early detection with a hybrid ML and image processing approach.

---

## 📈 Results

- Multiple classifiers were compared for accuracy, precision, and recall.
- CNN models showed promising results on segmented hippocampus images.
- Association rules helped identify symptom clusters associated with AD stages.

---

## 📂 Project Structure

