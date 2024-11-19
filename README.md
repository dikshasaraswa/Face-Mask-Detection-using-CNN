# Face-Mask-Detection-using-CNN
This project focuses on developing an intelligent system that can detect whether a person is wearing a face mask using Convolutional Neural Networks (CNNs). The system is designed to aid in public health measures by ensuring compliance with mask-wearing protocols, particularly in high-risk or crowded areas.

### **Key Features**
1. **Dataset**: 
   - The model is trained on a diverse dataset containing images of individuals with and without masks, including variations in mask types, angles, lighting conditions, and facial features.
   - Data augmentation techniques are applied to increase the dataset's diversity and robustness.

2. **Model Architecture**: 
   - A CNN-based deep learning model is used for feature extraction and classification.
   - The architecture includes convolutional layers for detecting edges and patterns, pooling layers for dimensionality reduction, and dense layers for final classification.

3. **Performance Metrics**: 
   - The system achieves high accuracy by minimizing false negatives (mask-wearers classified as non-wearers) and false positives.
   - Metrics such as precision, recall, F1-score, and confusion matrix are used for evaluation.

4. **Real-Time Detection**:
   - The system integrates with a webcam or CCTV feed for real-time detection.
   - OpenCV is employed for image preprocessing and live video capture.

5. **Applications**:
   - Can be deployed in public places like airports, hospitals, shopping malls, and offices.
   - Useful for monitoring and enforcing mask-wearing protocols during pandemics or in hazardous environments.

6. **User Interface**:
   - A simple and intuitive GUI displays the results, showing whether a mask is detected or not, along with a confidence score.

This project demonstrates the effective use of CNNs in a real-world application, combining the power of machine learning with public safety measures.
