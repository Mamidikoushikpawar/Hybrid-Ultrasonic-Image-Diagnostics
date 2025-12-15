**Hybrid Ultrasonic Image Diagnostics System**

**📌 Project Overview**

A deep learning–based medical image diagnostics system designed to classify ultrasound images using hybrid modeling and transfer learning techniques. The project leverages MobileNet architecture for efficient feature extraction and robust classification on limited medical datasets.


**🧠 Key Features**

Hybrid AI model for ultrasonic image classification
Transfer learning with MobileNet
Medical image preprocessing and normalization
Model training and evaluation using TensorFlow/Keras
Deployable trained model artifacts


**🛠 Technologies Used**

Python
TensorFlow / Keras
Flask
NumPy
HTML / CSS
Medical Image Processing
Jupyter / Google Colab

**📦 Model**

best_hybrid_weighted.h5
best_model.h5
best_transfer_vecalpha.h5
hybrid_model_export.h5
hybrid_model.keras
transfer_mobilenet_vecalpha.keras


**📊 Dataset & Training Details**

Dataset size: 600+ ultrasound images
Image resolution: 224 × 224
Batch size: 32
Training epochs: ~20


**⚙️ Installation**

Clone the repository:
git clone https://github.com/<your-username>/Hybrid-Ultrasonic-Image-Diagnostics.git
cd Hybrid-Ultrasonic-Image-Diagnostics
Install dependencies:
pip install -r requirements.txt
Run the Flask app:
python app.py
Open in browser
http://127.0.0.1:5000/


**🚀 How to Run**

pip install -r requirements.txt     #command
jupyter notebook notebooks/Hybrid_Ultrasonic_Image_Diagnostics.ipynb      #command


**🧪 Usage**

Upload a breast ultrasound image
The model predicts: Benign / Malignant / Normal
Displays probability scores


**📈 Results**

Achieved stable convergence and reliable classification performance
Model evaluated using accuracy-based metrics


**🔮 Future Enhancements**

Extend to multi-class medical diagnosis
Integrate real-time ultrasound stream processing
Deploy as a web or mobile diagnostic tool


**Commit Message**

#sql
Initial commit: Hybrid ultrasonic image diagnostics system using MobileNet
#nginx
Added preprocessing pipeline and model training workflow
#nginx
Uploaded trained models and evaluation metrics


**Description**

Hybrid deep learning system for ultrasonic medical image diagnostics using MobileNet transfer learning.


**Summary**

A deep learning–based medical imaging project focused on automated ultrasonic image classification using hybrid modeling and MobileNet transfer learning. The system processes and normalizes 600+ ultrasound images, extracts high-level visual features, and trains optimized models using TensorFlow/Keras in a Jupyter/Google Colab environment. The project demonstrates practical application of computer vision, medical image processing, and AI-driven diagnostics, producing deployable trained model artifacts suitable for further research or healthcare applications.
