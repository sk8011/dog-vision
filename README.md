
# 🐶 Dog Vision: Dog Breed Classification

This project is a deep learning-based image classifier that identifies dog breeds from images using TensorFlow and TensorFlow Hub.

## 📌 Overview

Using a Convolutional Neural Network (CNN) and transfer learning from a pretrained model, this app can predict the breed of a dog from a given image.

The model is trained on a labeled dataset of dog images, processed with image augmentation and optimized using TensorFlow best practices.

## 🧠 Features

- 🔍 Predicts the **breed** of a dog from a PNG image
- 📊 Shows **prediction confidence** and top 10 probable breeds
- 🧠 Built with **TensorFlow**, **TensorFlow Hub**, and **Keras**
- 🌐 Includes a **Streamlit frontend** for user-friendly uploads

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- TensorFlow Hub
- NumPy & Matplotlib
- Streamlit (frontend)
- Google Colab / Jupyter

## 📁 Directory Structure

```
dog-vision/
│
├── dog_vision_mine.ipynb          # Main notebook: training and evaluation
├── model_full.h5                  # Final trained model
├── app.py                         # Streamlit frontend to upload image & predict
├── requirements.txt               # Dependencies for deployment
└── README.md                      # This file
```

## 🚀 How to Use

### 🔧 Setup

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/dog-vision.git
   cd dog-vision
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 📸 Upload a Dog Image

- Upload a PNG image.
- Wait for the prediction.
- Get the predicted breed with confidence!

## 🔬 Model Training

The model is based on a pre-trained feature extractor from TensorFlow Hub, fine-tuned on your dataset. Training includes:

- Train-validation split
- Batch preparation
- Early stopping
- Full-dataset retraining
- Model saved as `model_full.h5`

## 🧪 Evaluation

The notebook includes:

- Accuracy metrics
- Loss curves
- Sample prediction visualizations
- Top-10 class confidence bar charts

## 📦 Deployment

- Compatible with **Streamlit Cloud**
- Just upload your repo and set `app.py` as the main entry point

## 🐾 Sample Output

![sample](docs/sample_prediction.png)

## 📜 License

MIT License

## 👨‍💻 Author

Made with ❤️ by [Your Name]
