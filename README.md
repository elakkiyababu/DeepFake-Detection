# DeepFake-Detection
Deepfakes are synthetic media in which a person in an existing image or video is replaced with someone else’s likeness using advanced artificial intelligence techniques. While these technologies can be used for creative and educational purposes, they also pose significant threats in the form of misinformation, fraud, and privacy violations.
DeepHug is a deep learning project built using *PyTorch, **timm, and **Hugging Face Hub*.  
This repository provides a notebook-based workflow for training, evaluating, and running inference with state-of-the-art vision models. 
🚀 Features
- Pretrained model integration via [timm](https://github.com/huggingface/pytorch-image-models)  
- Easy Hugging Face Hub model loading and saving  
- Custom dataset support (image classification or other vision tasks)  
- Simple, notebook-driven workflow  
📦 Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/your-username/deephug.git
cd deephug
pip install -r requirements.txt
# LUMINARA - DeepHug AI Image Detection System

LUMINARA (powered by *DeepHug*) is a hybrid project that combines deep learning and a modern web interface to detect whether an image is AI-generated or human-created.  
The backend is built with *PyTorch* and *timm*, while the frontend provides an interactive drag-and-drop detector.  

🚀 Features
- *Deep Learning Backend (deephug.ipynb)*  
  - Model training, fine-tuning, and inference using PyTorch + timm  
  - Hugging Face Hub integration for model loading/saving  
  - Dataset-agnostic (works with your own images)  

- *Frontend Web App (deepfake-detector.html)*  
  - Clean and responsive UI  
  - Drag-and-drop or file upload support  
  - Displays classification result (AI vs Human) with confidence score  
  - Can be connected to backend model predictions  

---
📦 Installation
Clone this repository:

```bash
git clone https://github.com/your-username/deephug.git
cd deephug
📊 Results

Accuracy and loss plots from training

Example predictions on test images
(Add your results here)

🔧 Tools & Technologies

PyTorch – Deep learning framework

timm – State-of-the-art pretrained models

Torchvision – Image transformations and augmentation

Hugging Face Hub – Model hosting & sharing

Pillow (PIL) – Image processing

NumPy – Numerical operations

HTML, CSS, JavaScript – Frontend UI
