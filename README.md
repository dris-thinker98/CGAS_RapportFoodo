# 🍴 CGAS_RapportFoodo

This repository presents an **end-to-end concept and implementation** of **Rapport Foodo**, an innovative take on **social media–based food recognition** and **intelligent food assistance**.  
The app leverages deep learning–based **image recognition** to identify dishes from user-uploaded photos and assists users by providing **ordering links**, **nutritional information**, or **recipes** for the detected items.

---

## 🚀 Project Overview

**Rapport Foodo** combines computer vision and social engagement by allowing users to:
- Snap or upload images of food items.
- Get instant identification of the dish.
- Explore related recipes or order the same dish online.

This project demonstrates the **fusion of AI, UX, and food discovery** into one cohesive experience.

---

## 🧠 Models Tested

To identify and classify food images efficiently, several **deep learning architectures** were explored and benchmarked.  
Below is a list of models used along with their brief descriptions and relevance for **image classification/recognition** tasks.

### 1. 🧩 TensorFlow Model Maker
**Description:**  
TensorFlow Model Maker simplifies the process of **training custom image classification models** using transfer learning. It allows quick experimentation by fine-tuning pre-trained models (like MobileNet, EfficientNet, etc.) on a smaller, domain-specific dataset.

**Why it’s used:**  
- Ideal for rapid prototyping and deployment.  
- Abstracts away low-level TensorFlow complexities.  
- Great for mobile-friendly applications like Rapport Foodo.

---

### 2. 🔍 Inception V3
**Description:**  
Inception V3 is a **deep convolutional neural network** designed by Google, known for its efficiency and reduced computational cost. It uses **Inception modules** that combine multiple convolutional filters in parallel to capture multi-scale features.

**Why it’s used:**  
- Excellent balance of **accuracy vs. speed**.  
- Handles **high-resolution image features** effectively.  
- Performs well in identifying complex textures like food ingredients.

---

### 3. ⚡ ResNet-50
**Description:**  
ResNet-50 (Residual Network with 50 layers) introduced **skip connections**, enabling much deeper networks by addressing the **vanishing gradient problem**. This architecture can learn complex representations while maintaining stable training.

**Why it’s used:**  
- Very strong **feature extractor** for fine-grained visual details.  
- Handles datasets with **many classes and subtle variations** (ideal for differentiating similar dishes).  
- Often used as a **backbone model** in production-grade image recognition systems.

---

### 4. 🍔 VGG-19
**Description:**  
VGG-19 is a **deep CNN** with 19 layers, known for its **simplicity and uniform architecture** — using only 3×3 convolution filters and max pooling layers. Despite being computationally heavier, it provides robust and clean feature representations.

**Why it’s used:**  
- Reliable and interpretable baseline for image recognition tasks.  
- Performs well on datasets with **consistent, clean images**.  
- Great for transfer learning and comparison studies.

---

### 5. 🍕 VGG-16
**Description:**  
VGG-16 is a slightly shallower variant of VGG-19 with 16 layers. It maintains the same elegant architecture but with reduced computational demand.

**Why it’s used:**  
- Provides a **benchmark reference model** for CNN performance.  
- Useful for smaller datasets due to its moderate complexity.  
- Excellent for **transfer learning** and visual feature extraction.

---

## 📊 Model Comparison Summary

| Model | Depth | Key Feature | Pros | Cons |
|-------|--------|--------------|------|------|
| TensorFlow Model Maker | Variable | Transfer learning wrapper | Easy to use, fast prototyping | Limited architecture control |
| Inception V3 | 48 layers | Multi-scale feature extraction | Efficient, high accuracy | Complex structure |
| ResNet-50 | 50 layers | Residual skip connections | Deep learning stability | Slightly higher training cost |
| VGG-19 | 19 layers | Uniform deep CNN | High accuracy | Computationally heavy |
| VGG-16 | 16 layers | Simpler deep CNN | Easier to train | Less feature diversity |

---

## 🧩 Tech Stack

- **Frameworks:** TensorFlow, Keras  
- **Language:** Python  
- **Deployment:** Java Android Studio App (repo link: https://github.com/dris-thinker98/RapportFoodo)
- **Dataset:** Custom curated food image dataset (multi-cuisine)  
- **Tools:** Google Colab, Jupyter Notebooks  

---

### 🌐 Created by the IIITD-CGAS Team  
Bringing intelligence to your plate — one bite at a time. 🍽️
