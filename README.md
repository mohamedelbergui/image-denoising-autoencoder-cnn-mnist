# Image Denoising with a Convolutional Autoencoder

This project implements a **convolutional autoencoder** using Keras,  
trained on noisy versions of the MNIST dataset to **restore degraded grayscale images**.

The model learns to remove different types of noise, including:
- Gaussian noise
- Salt & Pepper noise
- Speckle noise
- Poisson noise

## 📂 Structure

- `data_preparation`: loading, normalizing and reshaping MNIST images
- `noise_generator`: custom function to add random noise to inputs
- `autoencoder_model`: CNN-based encoder-decoder architecture
- `training`: model compilation, training, and loss visualization
- `evaluation`: visual comparison between noisy and denoised images

## 🧠 Technologies Used

- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab

## 📈 Results

- Training over 30 epochs with MSE loss and Adam optimizer  
- Final loss: **0.0087 (train)**, **0.0094 (validation)**
- Successful denoising with clear visual improvement




## 🧑‍🏫 Supervision

Project supervised by **Professor Nour Eddine Alaa**  
Faculty of Sciences and Techniques, Morocco.

