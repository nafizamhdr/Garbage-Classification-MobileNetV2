# Garbage Classification MobileNetV2 🌿

Hi there! This repository contains a Deep Learning project built to classify images of garbage into 10 different categories. The goal is to assist in automated waste sorting using computer vision.

I used **Transfer Learning** with the **MobileNetV2** architecture because it's lightweight, efficient, and perfect for mobile deployment.

##  About the Project
Proper waste sorting is key to a cleaner environment. This project attempts to automate that process. The model is trained on a dataset containing **19,762 images** across **10 categories**:

*   Battery
*   Biological
*   Cardboard
*   Clothes
*   Glass
*   Metal
*   Paper
*   Plastic
*   Shoes
*   Trash

##  Tools & Tech
*   **Python**
*   **TensorFlow & Keras**
*   **MobileNetV2** (Base model for Transfer Learning)
*   **Data Augmentation** (To improve model generalization)
*   **Matplotlib & Seaborn** (For visualization)

##  Key Features
*   **`Submission_Akhir.ipynb`**: The main notebook containing the full workflow (Data Loading -> Preprocessing -> Modeling -> Evaluation).
*   **Callbacks**: Implements `EarlyStopping` and `ModelCheckpoint` to prevent overfitting and save the best model.
*   **Deployment Ready**: Includes scripts to convert the trained model to **TFLite** and **TensorFlow.js** formats.

##  Results
Check the notebook to see the **Accuracy/Loss plots** and the **Confusion Matrix**, which give a clear picture of how well the model performs on test data.

---
*Created by Nafiza Mahadri Widyatamaka*
