# road-safety-gear-detection
Computer Vision project that detects helmet or mask compliance using Machine Learning and webcam simulation.

# Helmet / Mask Safety Compliance Detection using Computer Vision

## Project Overview
This project uses Computer Vision and Machine Learning to detect whether a person is wearing safety equipment such as a helmet or mask.

The system is trained on a synthetic dataset and performs real-time prediction using webcam input. It demonstrates how AI can be used to improve safety compliance in environments like roads, construction sites, and public places.

---

## Features
- Synthetic dataset generation
- Image preprocessing
- Machine Learning classification model
- Real-time webcam simulation
- Structured and modular project design
- Easy to understand and extend

---

## Technologies Used
- Python
- OpenCV
- NumPy
- Scikit-learn
- Joblib

---

## Project Structure
helmet-mask-safety-detection
│
├── dataset
│ └── images
│ ├── with_helmet
│ ├── without_helmet
│ ├── with_mask
│ └── without_mask
│
├── src
│ ├── models
│ ├── utils
│ │ └── generate_dataset.py
│ │
│ ├── train_model.py
│ └── predict_webcam.py
│
├── outputs
├── requirements.txt

---

## Installation

Clone the repository:


git clone https://github.com/sans118/road-safety-gear-detection.git


Go inside project folder:


cd helmet-mask-safety-detection


Install dependencies:


pip install -r requirements.txt


---

## How to Run

Step 1: Generate dataset


python src/utils/generate_dataset.py


Step 2: Train the model


python src/train_model.py


Step 3: Run real-time detection


python src/predict_webcam.py


Press ESC to exit webcam.

---

## Applications

- Road safety monitoring
- Construction site compliance
- Industrial worker safety
- Public health monitoring

---

## Future Improvements

- Use real-world dataset
- Implement CNN deep learning model
- Use YOLO object detection
- Detect multiple safety equipment
- Deploy as web application
