# Brain Tumour Analysis Using Lightweight Multimodal AI

## 📌 Project Description
Brain tumour diagnosis using MRI is a critical and time-sensitive medical task. Manual interpretation of MRI scans is often time-consuming, subjective, and dependent on expert radiologists. This project proposes a **lightweight multimodal artificial intelligence framework** that integrates **MRI imaging data and omics data** to improve diagnostic accuracy while maintaining low computational complexity.

The system supports **fast, accurate, and explainable brain tumour diagnosis**, making it suitable for real-time and resource-constrained clinical environments.

---

## 📖 About
**Brain Tumour Analysis Using Lightweight Multimodal AI** is a deep learning–based system that combines multiple data modalities to enhance tumour detection and risk prediction. The framework uses a **pretrained MobileNetV2** model for MRI feature extraction and a **dense neural network** for omics representation learning. These features are fused using an **asymmetric cross-attention mechanism**, enabling effective multimodal interaction.

Explainability is incorporated using **Grad-CAM** for MRI visualization and **attention-based omics feature importance**, improving transparency and clinical trust.

---

## ✨ Features
- Lightweight deep learning architecture  
- Multimodal fusion of MRI images and omics data  
- Cross-attention–based feature integration  
- Dual-task learning: tumour classification and risk prediction  
- Grad-CAM–based MRI explainability  
- Attention-based omics feature importance visualization  
- High accuracy with reduced inference time  
- Scalable and deployable in low-resource environments  

---

## 🛠️ Requirements

### Hardware
- Processor: Intel / AMD multi-core CPU  
- RAM: Minimum 8 GB (16 GB recommended)  
- GPU: NVIDIA GPU with CUDA support (optional)  

### Software
- Operating System: Windows 10 / Ubuntu (64-bit)  
- Programming Language: Python 3.8 or later  
- Deep Learning Framework: PyTorch  
- Pretrained Models: Torchvision (MobileNetV2)  
- Libraries: NumPy, Pandas, Scikit-learn, Matplotlib  
- IDE: VS Code / Jupyter Notebook  
- Version Control: Git  

---

## 🧠 System Architecture
The proposed architecture consists of:
- MRI Feature Encoder (MobileNetV2)  
- Omics Feature Encoder (Fully Connected Network)  
- Cross-Attention Fusion Module  
- Bottleneck Layer  
- Classification Head (Benign / Malignant)  
- Risk Prediction Head  
- Explainability Modules (Grad-CAM & Attention Heatmaps)  

*(Add architecture diagram image here)*

---

## 📊 Output

### Output 1: Omics Attention Heatmap
Visualizes attention-weighted importance of latent omics features contributing to diagnosis.

*(Add screenshot here)*

### Output 2: ROC Curve and Confusion Matrix
Shows classification performance and error distribution.

*(Add screenshot here)*

### Output 3: Grad-CAM MRI Visualization
Highlights tumour-relevant regions in MRI scans.

*(Add screenshot here)*

---

## 📈 Performance Metrics
- **Accuracy:** 90%  
- **Precision:** 93%  
- **Recall:** 92%  

> *Metrics may vary depending on dataset and experimental setup.*

---

## 🧪 Dataset
- Publicly available brain MRI datasets (e.g., BraTS)  
- Synthetic / experimental omics feature data  
- Preprocessed using normalization and resizing techniques  

---

## 🚀 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/your-username/brain-tumour-multimodal-ai.git

# Navigate to the project directory
cd brain-tumour-multimodal-ai

# Install dependencies
pip install -r requirements.txt

# Run the model
python main.py
