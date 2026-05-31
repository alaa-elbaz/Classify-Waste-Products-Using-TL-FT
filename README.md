# Waste Classification Using Deep Learning & Transfer Learning

## 📌 Project Overview
This project focuses on automated **Waste Classification** to support recycling processes and environmental sustainability. It uses Deep Learning to analyze and classify images of waste into two primary categories:
* **Organic (O):** Biodegradable waste like food scraps, fruits, and vegetables.
* **Recyclable (R):** Recyclable materials like plastics, paper, cardboard, glass, and metals.

## 🛠️ Tech Stack & Libraries
* **Framework:** TensorFlow & Keras
* **Environment:** Jupyter Notebook / Skills Network Labs
* **Core Concepts:** Deep Learning, Computer Vision, Dataset Augmentation (`ImageDataGenerator`), Transfer Learning, Fine-Tuning.

## 🚀 Workflow & Implementation
1. **Data Preprocessing:** Utilized `ImageDataGenerator` for data loading, pixel rescaling, and splitting dataset partitions.
2. **Base Model Setup (Transfer Learning):** Leveraged a powerful pre-trained convolutional neural network, freezing early feature-extraction layers while attaching custom dense layers on top.
3. **Training Phase:** Trained the network over multiple epochs while monitoring training vs. validation loss and accuracy curves.
4. **Fine-Tuning:** Unfroze selective top layers and retrained with a very small learning rate to adapt the model more tightly to the custom waste dataset.
5. **Evaluation:** Evaluated and compared prediction results before and after fine-tuning on unseen test images.

## 📈 Key Results
* Successfully generated **Loss and Accuracy curves** showing steady model convergence.
* The **Fine-Tuned Model** exhibited significantly higher classification confidence and better prediction capabilities compared to the base transfer learning model.
*
