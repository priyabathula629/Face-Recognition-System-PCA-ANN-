Face Recognition System using PCA and ANN
📌 Overview

This project implements a Face Recognition System using Principal Component Analysis (PCA) for feature extraction and an Artificial Neural Network (ANN) for classification. The model is trained on grayscale facial images to recognize different individuals.

🚀 Features
Image preprocessing (resize, grayscale conversion, normalization)
Dimensionality reduction using PCA
Face classification using ANN (TensorFlow/Keras)
Model evaluation with accuracy metrics
Visualization of training performance
📂 Dataset
Total Images: 450
Number of Classes: 9
Images are organized into folders (one folder per person)
🛠️ Technologies Used
Python
OpenCV
NumPy
Scikit-learn
TensorFlow / Keras
Matplotlib
⚙️ Project Workflow
Load and preprocess images
Normalize data using StandardScaler
Apply PCA for feature extraction
Split data into training and testing sets
Train ANN model
Evaluate model performance
🧪 Model Architecture
Input Layer: PCA components (100 features)
Hidden Layer 1: Dense (128 neurons, ReLU)
Hidden Layer 2: Dense (64 neurons, ReLU)
Dropout Layers (0.3) to prevent overfitting
Output Layer: Softmax activation
📊 Results
Achieved ~74% accuracy on test data
Improved performance through preprocessing and feature reduction
📈 Output Visualization
Accuracy vs Epochs
Loss vs Epochs
▶️ How to Run
Clone the repository
git clone https://github.com/your-username/face-recognition-pca-ann.git
Install dependencies
pip install numpy opencv-python scikit-learn tensorflow matplotlib
Update dataset path in the code
DATASET_PATH = "your/dataset/path"
Run the script
python main.py
📌 Future Improvements
Improve accuracy using CNN models
Add real-time face recognition using webcam
Increase dataset size for better performance
👩‍💻 Author

Naga Priya Bathula

If you want, I can also:

Create a GitHub repo structure (folders + files)
Or make this README more attractive with badges & images 👍
