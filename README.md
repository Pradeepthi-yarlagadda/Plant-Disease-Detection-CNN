🌿 Plant Disease Detection using CNN
📌 Project Overview
This project uses Computer Vision and Deep Learning to automate the identification of 38 different categories of plant diseases. By analyzing leaf images, this tool provides a fast and accurate diagnosis to help farmers prevent crop loss.

📊 Model Performance & Results
Based on the final training results shown in the notebook:

Dataset Size: 87,000+ images (70,295 training / 17,572 validation).

Training Accuracy: 96.73%.

Validation Accuracy: 90.69%.

Optimization: Used Adam optimizer and Sparse Categorical Crossentropy loss.

Hardware: Accelerated training using a Google Colab T4 GPU.

🛠️ Tech Stack
Framework: TensorFlow / Keras.

Libraries: NumPy, Matplotlib, OS, Glob.

Data Source: New Plant Diseases Dataset (Kaggle).

🚀 How to Use
Download: Get the .ipynb notebook from this repository.

Kaggle Setup: Insert your KAGGLE_USERNAME and KAGGLE_KEY to download the 2.7GB dataset.

Inference: Use the saved plant_disease_model.h5 file to predict diseases on your own leaf images.

Kaggle Setup: Insert your KAGGLE_USERNAME and KAGGLE_KEY to download the 2.7GB dataset.

Inference: Use the saved plant_disease_model.h5 file to predict diseases on your own leaf images.
