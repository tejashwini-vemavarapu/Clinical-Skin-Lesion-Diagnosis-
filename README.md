# Deep Learning - Clinical Skin Lesion Diagnosis

## Overview
Clinical Skin Lesion Diagnosis using Neural Networks.

## Objective
This project aims to build a Machine Learning model for the diagnosis of pigmented skin lesions through dermatoscopic image analysis. The goal is to significantly improve early detection and diagnostic precision, ensuring the reliable differentiation of benign and malignant lesions to enhance patient care and dermatological diagnosis.

## Problem Statement
Skin cancer accounts for one-third of all cancer cases, making it the most common type of cancer worldwide. While many skin cancers are treatable, aggressive melanoma in its advanced stage has a survival rate of less than five years if not identified early. Clinical processes for diagnosis have an accuracy range of 49% to 81%, which is not optimal. Dermoscopy has improved diagnostic accuracy but remains prone to human error. Deep learning techniques can provide a more efficient and accurate method to classify skin lesions and aid in early detection.

## Related Work
Deep learning, particularly Convolutional Neural Networks (CNNs), has demonstrated significant potential in enhancing the accuracy and efficiency of skin cancer diagnosis. This project explores the use of CNNs and VGG-inspired models for improved classification of skin lesions.

## Dataset: HAM10000
- The dataset includes diverse and demographically representative dermatoscopic images.
- It is used for training and testing deep learning models to classify skin lesions.
- Uneven class distribution in the dataset necessitated oversampling of underrepresented classes to balance the dataset.

## Methodology
- Utilized CNN-based models, including a VGG-inspired architecture.
- Evaluated model architectures and performance to determine the most effective approach for medical image classification.
- Addressed data imbalance through oversampling techniques.

## Results
### Dataset Evaluation
- The dataset was imbalanced, requiring oversampling of underrepresented classes to improve classification performance.

### Model Performance
| Model              | Training Accuracy | Validation Accuracy | Test Accuracy |
|--------------------|------------------|---------------------|--------------|
| Custom CNN        | 81.51%            | 76.23%              | 61.41%       |
| VGG-like Model    | 89.67%            | 75.11%              | 56.27%       |

- Both models exhibited overfitting, as indicated by validation loss trends.
- The moderate test set accuracy suggests the need for further model optimization.

## Conclusion
- Deep learning-based CNN models show promise in enhancing the diagnostic process for skin cancer classification.
- Addressed dataset imbalance and achieved moderate accuracy, highlighting foundational success in generalization.
- Automatic classification of skin lesions can help improve early detection and reduce diagnostic errors.

## Installation Guide
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- TensorFlow/Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn

### Steps to Install
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/Clinical-Skin-Lesion-Diagnosis.git
   cd Clinical-Skin-Lesion-Diagnosis
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the training script:
   ```sh
   python train.py
   ```
5. Evaluate the model:
   ```sh
   python evaluate.py
   ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The HAM10000 dataset contributors.
- Open-source deep learning frameworks such as TensorFlow and Keras.
- Researchers and developers working on AI-driven dermatology solutions.

---
