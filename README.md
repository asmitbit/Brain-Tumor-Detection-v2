This project focuses on detecting brain tumors in MRI images using deep learning techniques. It leverages Convolutional Neural Networks (CNNs) to classify MRI images into tumor or non-tumor categories, achieving a high accuracy of 97%. The model is integrated into a user-friendly web application using Flask, enabling users to upload MRI images and receive real-time predictions.

🚀 Features
High-Accuracy Detection: Achieves 97% accuracy on test data using a CNN-based model (VGG-like architecture).

End-to-End Pipeline: Includes image preprocessing, model training, evaluation, and deployment.

Web Application: Flask-based interface allowing users to upload MRI images and get instant results.

Data Augmentation: Utilizes image augmentation to enhance model generalization and robustness.

Explainable AI (optional): Visualizes model predictions using Grad-CAM or similar techniques (if implemented).

Model Architecture
Convolutional Neural Network (CNN): Based on VGG architecture with multiple convolutional layers followed by fully connected layers.

Input: Preprocessed MRI images resized to 224x224 pixels.

Output: Class Labels:['pituitary', 'glioma','meningioma', 'notumor'] (tumor / no tumor).




For any inquiries, please reach out to:

Email: asmitadesh945@gmail.com

