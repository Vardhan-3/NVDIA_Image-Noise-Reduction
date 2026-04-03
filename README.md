# NVDIA_Image-Noise-Reduction

 Image Noise Reduction using Autoencoders (TensorFlow)
📌 Project Overview

This project focuses on image denoising using Deep Learning Autoencoders built with TensorFlow/Keras. The goal is to reconstruct clean images from noisy inputs by training a neural network to learn meaningful representations of image data.

This project was developed as part of my college lab work and represents a hands-on implementation of GPU-accelerated deep learning.

🚀 Key Highlights
🔍 Implemented Autoencoder architecture for image denoising
🧪 Worked with the MNIST dataset for training and evaluation
⚡ Leveraged GPU acceleration using NVIDIA SMI
🧮 Utilized CUDA 12.2 for faster computation
🧑‍💻 One of the first implementations in my college lab using GPU resources
📈 Demonstrated performance improvements over CPU-based training
🏗️ Project Workflow
Data Loading
Used MNIST dataset from TensorFlow/Keras
Data Preprocessing
Normalization of image pixel values
Artificial noise added to images for training
Model Architecture
Built a Deep Autoencoder
Encoder compresses the image
Decoder reconstructs the denoised image
Training
Model trained to minimize reconstruction loss
GPU acceleration used for efficient training
Evaluation
Compared noisy vs reconstructed images
Visualized denoising performance
🧠 Model Architecture (Autoencoder)
Input Layer (Noisy Image)
Encoder Layers (Compression)
Bottleneck Layer (Feature Representation)
Decoder Layers (Reconstruction)
Output Layer (Denoised Image)
🛠️ Technologies Used
Python
TensorFlow / Keras
NumPy, Matplotlib, Seaborn, Pandas
NVIDIA GPU (via NVIDIA SMI)
CUDA 12.2
⚙️ Hardware Acceleration

This project was executed using:

✅ NVIDIA GPU (monitored via nvidia-smi)
✅ CUDA Version: 12.2

This allowed significantly faster training compared to CPU-based execution and provided practical exposure to real-world deep learning infrastructure.

📊 Results
Successfully reduced noise from corrupted images
Autoencoder learned meaningful latent representations
Visual outputs show clear improvement in image quality
📸 Sample Output

(You can add before/after images here from your notebook)

🎯 Learning Outcomes
Practical understanding of Autoencoders
Experience with GPU-based deep learning
Knowledge of CUDA and NVIDIA GPU utilization
Hands-on exposure to image preprocessing and reconstruction
🌟 Unique Contribution

I was among the first students in my college lab to utilize NVIDIA GPU (via nvidia-smi) with CUDA 12.2 for a deep learning project, making this a significant milestone in my academic journey.
