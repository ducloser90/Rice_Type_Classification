## 📊 Dataset Overview

This project uses the **Rice Type Classification** dataset from Kaggle, which contains images of **five different rice varieties**. The objective is to train a deep learning model capable of identifying the type of rice grain based on its visual characteristics.

> **Dataset Source:** Kaggle — "Rice Type Classification"  
https://www.kaggle.com/datasets/mssmartypants/rice-type-classification
---

### 🏷️ Classes

The dataset contains **five** rice varieties:

- **Arborio**
- **Basmati**
- **Ipsala**
- **Jasmine**
- **Karacadag**

---

### 📁 Dataset Structure

- **Total images:** ~75,000  
- **Images per class:** ~15,000  
- **Image format:** RGB images  
- **Use case:** Single rice grain classification  

The dataset is suitable for both **training and benchmarking** image classification models.

---

### 🔍 Why This Dataset?

- Balanced class distribution  
- Sufficient data volume for deep learning  
- Real-world relevance for **agricultural technology**, **quality control**, and **automation**

---

### 🧹 Preprocessing Applied

- Image resizing (e.g., 224×224 for transfer learning models)
- Pixel normalization
- Data augmentation such as:
  - Horizontal/vertical flips
  - Random rotations
  - Color and brightness adjustments

---
`data_df.head()`
<img width="2302" height="384" alt="image" src="https://github.com/user-attachments/assets/3f7b1bb6-1b7c-4797-bb18-a1e64ea01c9d" />

