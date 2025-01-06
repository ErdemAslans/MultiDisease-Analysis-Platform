# MultiDisease Analysis Platform

## Overview

**MultiDisease Analysis Platform** is an innovative platform designed for medical professionals, offering both a secure login system and multi-disease detection capabilities. The platform leverages state-of-the-art AI technologies to ensure accurate diagnoses and streamline medical workflows.

### How It Works

1. **Secure Login with Face Recognition**:
   Doctors authenticate themselves using a face recognition system built with ViT (Vision Transformer) and Swin models. Once verified, the system issues a security token that grants access to the platform.

2. **Medical Data Analysis**:
   The platform provides doctors with multiple medical analysis options, such as:
   - **EEG Analysis**: Detecting epilepsy and other neurological disorders.
   - **Breast Cancer Detection**: Segmenting and identifying anomalies in MRI scans.
   - **Pulmonary Hypertension Detection**: Analyzing CT images for pulmonary abnormalities.

   Doctors upload their medical data (e.g., EEG recordings, MRI or CT scans), which the system processes and returns results with detailed visualizations.

3. **Modular Design for Flexibility**:
   The platform is designed to be extensible, allowing the integration of additional disease detection modules in the future.

---

## Features

- **Face Recognition Security**:
  Implements a robust authentication system using ViT and Swin models to ensure secure access for medical professionals.

- **AI-Powered Medical Analysis**:
  Utilizes advanced segmentation and disease detection models for accurate results.

- **Multi-Disease Support**:
  Supports analysis across different medical domains, including neurology, oncology, and cardiology.

- **Extensible Architecture**:
  A modular structure allows for the seamless addition of new disease detection capabilities.

- **Time Efficiency**:
  Reduces the time required for medical diagnostics, enabling quicker decision-making.

---

## Technologies Used

- **Python 3.8+**
- **PyTorch**: Deep learning framework for model development.
- **Gradio**: Interactive web interface for doctors to upload data and view results.
- **Timm**: Pre-trained models for ViT and Swin Transformers.
- **Scikit-Image**: Image processing for pre-processing medical data.
- **OpenCV**: Additional image processing capabilities.
- **PyWavelets**: Wavelet transforms for EEG signal analysis.

---
