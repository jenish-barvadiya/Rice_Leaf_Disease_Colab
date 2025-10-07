# Rice_Leaf_Disease_Colab

# 📊 Data Analysis Report for Rice Leaf Disease Dataset

---

## 1. 📂 Dataset Overview

The dataset consists of **119 images** of rice leaves categorized into three classes:

- **Bacterial Leaf Blight**: 40 images  
- **Brown Spot**: 40 images  
- **Leaf Smut**: 39 images  

These images are collected from infected rice plants, each showing distinct symptoms. The objective is to classify these images into the correct disease categories.

---

## 2. 🧾 Dataset Characteristics

- **Small dataset size**: Only 119 images, which is limited for deep learning.  
- **Class distribution**: Nearly balanced (around 40 images per class).  
- **Image quality**: Varies in lighting, background, and leaf orientation.  
- **Image format**: RGB images with 3 color channels (important for disease spot detection).

---

## 3. ⚠️ Challenges with the Dataset

- **Limited sample size** → Higher risk of overfitting.  
- **Variability** → Differences in angles, lighting, and background make learning harder.  
- **Visual similarity** → Some diseases look quite similar, leading to possible misclassification.

---

## 4. 🛠️ Data Preprocessing & Cleaning

- **Resizing** → All images resized to a uniform size (e.g., 255x255 pixels).  
- **Normalization** → Pixel values scaled between 0 and 1.  
- **Shuffling and batching** → Applied for better training and to avoid bias.

---

## 5. 🔁 Data Augmentation

To improve model performance and reduce overfitting, augmentation techniques were used:

- Random **horizontal/vertical flips**  
- Random **rotations**  
- These simulate real-world variations and help the model generalize better.

---

## 6. 🔎 Exploratory Data Analysis (EDA)

- **Class count visualization** → Checked if data is balanced.  
- **Sample visualization** → Displayed images from each class to understand appearance.  
- **Label verification** → Ensured correct labeling of images.

---

## 7. ✅ Summary & Insights

- Dataset is small but usable for training with augmentation and preprocessing.  
- Data augmentation is **necessary** to improve learning and generalization.  
- Preprocessing brings uniformity to image inputs.  
- **Deep models or transfer learning** may be required due to visual similarity between disease classes.

---


