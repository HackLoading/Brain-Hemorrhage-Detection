# Brain-Hemorrhage-Detection
This project develops a deep learning system to classify brain CT scans as normal or hemorrhagic using MobileNet V2. It processes a dataset of 71,491 DICOM images, achieving ~90% accuracy. The system includes a preprocessing pipeline for efficient data handling and is designed for real-time clinical use.

# Dataset :
71,491 DICOM images (35,539 normal, 35,952 hemorrhagic) from hospital CT scans.

# Results :
Training Accuracy: 90.40%
Validation Accuracy: 89.27%
Training Loss: 0.245
Validation Loss: 0.240

# Technologies :
Python, TensorFlow, Keras, OpenCV, pydicom, NumPy, Matplotlib, Scikit-learn
MobileNet V2 architecture
Adam optimizer, Binary Cross-Entropy loss

# GPU Configuration used :
Two Quadro RTX 6000, 24 GB GDDR6 VRAM per GPU




## 🛠️ Installation

Follow these steps to set up the project on your local machine.

### ✅ Prerequisites

- Python 3.8 or higher  (preferable- Python 3.9.11) 
- TensorFlow-gpu 2.10.0  
- pip (Python package installer)

Make sure these are installed before continuing.

---

### 📥 Clone the Repository

```bash
git clone https://github.com/yourusername/brain-hemorrhage-detection.git
cd brain-hemorrhage-detection


