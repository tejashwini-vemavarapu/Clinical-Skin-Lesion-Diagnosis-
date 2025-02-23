# Deep Learning - Clinical-Skin-Lesion-Diagnosis -
Clinical Skin Lesion Diagnosis using Neural Networks

# Objective
Building a Machine Learning Model for the Diagnosis of Pigmented Skin Lesions through
Analysis of Dermatoscopic Images, Aiming to Significantly Improve Early Detection and
Diagnostic Precision. This project focuses on the reliable differentiation of benign and malignant
lesions, with the goal of enhancing patient care and dermatological diagnosis.
# What Problem Is Being Addressed
One-third of all cancer cases are skin cancer, making it the most common type of cancer in the
world. Normal skin cancers are not deadly and can be healed with the right medicine. But it's
more dangerous, if have aggressive melanoma in its advanced state, you have less than or equal
to 5 years to survive. It can be cured, if identified early. Even there are lot of clinical processes,
the recognition is only 49% to 81% accurate and takes lot of time. Dermoscopy helped to make
diagnoses more accurate, but it couldn't get rid of the behavior that led to mistakes. To identify
this skin cancer that is spreading very quickly and with fewer mistakes, we need an efficient
method. This project is about using deep learning to sort skin lesions into different groups.
# Relation to Existent Work:
The need for accurate, timely skin cancer diagnoses and the role of deep learning and CNN in
improving diagnostic efficiency.

# Dataset Analysis: (HAM10000 dataset)
• Characteristics the diversity and demographic information of
the dataset.
• dermatoscopic images for training and testing Deep Learning
models to classify skin lesions.
# Methodological approach: 
• Approach emphasizes the use of CNN, and VGG-inspired
model, to diagnose skin lesions.
• Architectures of the models and its perfromance to ascertain
the most effective method in medical image analysis

# Results
# Dataset evaluation :
Image dataset included uneven data, hence underrepresented classes were
oversampled. This method artificially increased the amount of samples in less common skin
lesion categories to balance class distribution. After this, CNN models were trained on the
rebalanced dataset.
# Performance Measures:
CNN model achieved a training accuracy of 81.51% and a validation
accuracy of 76.23%. The VGG-like model showed a training accuracy of 89.67% and a
validation accuracy of 75.11%. However, both models indicated potential overfitting, as
suggested by the trends in validation loss. When evaluated on the test set, the custom CNN
model had an accuracy of 61.41%, and the VGG-inspired model had 56.27%, pointing to
moderate performance

# Results
# Model Prediction:
The custom-built CNN model achieved a training accuracy of 81.51% and a validation accuracy of 76.23%.
The VGG-like model showed a training accuracy of 89.67% and a validation accuracy of 75.11%.
However, both models indicated potential overfitting, as suggested by the trends in validation loss.
When evaluated on the test set, the custom CNN model had an accuracy of 61.41%, and the VGG-inspired model
had 56. 27%, pointing to moderate performance on unseen data

# Conclusion
 What was Achieved:
• The deployment of CNNs demonstrated the potential of deep learning in enhancing diagnostic processes in
clasfication of skin cancer.

• handled a diverse and imbalanced in dataset, and achieving a commendable level of accuracy on the test set
and indicating foundational success in their ability to generalize from training .

• Automatic classification helps in accurately identifing suspected skin cancer.

