# Understanding When Attention Helps: A Systematic Empirical Study of Attention Mechanisms in Medical Image Classification

This repository contains the partial implementation and experimental analysis of **Channel, Spatial, and Branch Attention Mechanisms** for **medical image classification** tasks.  
The project is based on our research paper and investigates how different attention strategies influence feature representation and classification performance in medical imaging scenarios.

---

##  Project Overview

Medical image classification often suffers from challenges such as subtle visual patterns, low contrast, class imbalance, and high inter-class similarity.  
Attention mechanisms help deep neural networks focus on diagnostically relevant features, improving robustness and interpretability.

In this project, we:

- Implement **Channel Attention**, **Spatial Attention**, and **Branch Attention** mechanisms
- Apply attention mechanisms to **medical image analysis**
- Integrate attention blocks into different backbone networks
- Evaluate performance on **multiple medical imaging datasets**
- Compare the effectiveness of different attention strategies in medical image classification

---

##  Medical Image Analysis Focus

This study specifically targets **medical imaging tasks**, where attention mechanisms help models:

- Emphasize clinically relevant regions
- Suppress background noise and irrelevant features
- Improve discriminative feature learning
- Enhance classification performance across different imaging modalities

The experiments analyze how each attention type contributes to improved representation learning in medical image classification pipelines.

---

##  Attention Mechanisms

### 1. Channel Attention
- Focuses on **what feature channels** are important
- Models inter-channel dependencies
- Enhances discriminative feature maps in medical images

### 2. Spatial Attention
- Focuses on **where important anatomical or pathological regions** are located
- Highlights spatially relevant areas in medical images

### 3. Branch Attention
- Learns importance across **multiple parallel feature branches**
- Facilitates multi-scale and multi-path feature fusion
- Useful for capturing diverse medical imaging patterns

>  **Note:**  
> The `Channel`, `Spatial`, and `Branch` folders contain **only attention block implementations**, not complete classification models.

---

##  Networks (Backbones)

The `Networks` folder contains backbone architectures that **import and integrate** the attention mechanisms from:

- Channel Attention
- Spatial Attention
- Branch Attention

Each notebook demonstrates how attention modules are embedded into the network architecture for medical image classification. **There are more experimentation and codes which will be shared later.


<img width="2128" height="1446" alt="eng270957-fig-0004-m" src="https://github.com/user-attachments/assets/dcc2e09d-f5de-45b6-8d4f-95f069348d11" />

---

##  Datasets

We used **three medical imaging datasets**, along with their preprocessed versions, for experimental evaluation.

📎 **Google Drive Dataset Link:**  
👉 https://drive.google.com/drive/folders/1rXFDp6YlvpCFrlFzow0LH3NE11l2lrKV?usp=sharing

The drive includes:
- Original medical image datasets
- Preprocessed datasets used in the experiments
<img width="703" height="436" alt="Screenshot from 2026-08-07 10-41-49" src="https://github.com/user-attachments/assets/f3b6d900-01f5-4d1c-a7fd-fc57a2f3ccd7" />


---

 Notes
This is the partial implementation and idea of how the proposed analysis can be done in different settings.
