# 🌸 Flower Recognition Using Vision Transformer (ViT)
## 📖 Overview
This project is a Flower Recognition System that classifies flower images into five different categories using a Vision Transformer (ViT) deep learning model. The model leverages transfer learning from Google's pre-trained Vision Transformer model, enabling accurate flower classification while reducing training time.
## ✨ Features
• Classifies flower images into 5 categories.
• Uses Vision Transformer (ViT) architecture.
• Transfer learning with a pre-trained model.
• Image preprocessing using Hugging Face ViT Image Processor.
• Model evaluation on validation and test datasets.
• Predicts flower species from new images.

## 🛠 Technologies Used
• Python 3
• TensorFlow
• Hugging Face Transformers
• NumPy
• Matplotlib
• Google Colab
• Google Drive

## 📂 Dataset Structure

dataset/
│
├── flower/      # Training images
├── val/         # Validation images
└── test/        # Testing images

Each folder contains subfolders representing different flower classes.

## 🤖 Model Configuration

Model       : google/vit-base-patch16-224-in21k
Image Size  : 224 × 224
Batch Size  : 32
Transfer Learning : Enabled

## ⚙️ Installation

Clone the repository

git clone https://github.com/your-username/flower-recognition-vit.git

Move to project directory

cd flower-recognition-vit

Install required packages

pip install tensorflow transformers numpy matplotlib

## 🚀 Training

Run the training script

python train.py

Or execute all cells in the Google Colab notebook.

---

## 🧪 Testing

Evaluate the trained model

python test.py

---

## 🔍 Prediction

Predict the class of a flower image

python predict.py --image sample.jpg

---

## 📁 Project Structure

Flower-Recognition-ViT/
│
├── dataset/
├── models/
├── train.py
├── test.py
├── predict.py
├── requirements.txt
└── README.md

---

## 📈 Results

The Vision Transformer model successfully classifies flower images into five categories using transfer learning. The model performs well on validation and testing datasets and can be further improved with additional data and hyperparameter tuning.

---

## 🚀 Future Enhancements

• Deploy using Flask or Streamlit.
• Add support for more flower species.
• Real-time webcam prediction.
• TensorFlow Lite deployment for mobile devices.
• Improve accuracy using data augmentation and hyperparameter tuning.

---

## 👨‍💻 Author

Miriyala Dasharatham

B.Tech Student

Institute of Aeronautical Engineering (IARE)

---

## 📜 License

This project is developed for educational and academic purposes. It may be freely modified and used for learning, research, and personal projects.
