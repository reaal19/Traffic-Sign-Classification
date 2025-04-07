# Traffic-Sign-Classification
🚦 Traffic Sign Classification using CNN
This project aims to build a robust deep learning model for classifying traffic signs using Convolutional Neural Networks (CNNs), which is a key component in autonomous driving and driver-assistance systems.

📚 Overview
Traffic sign recognition enables self-driving cars and smart driver alert systems to understand road conditions and comply with regulations. The model in this project was trained using the German Traffic Sign Recognition Benchmark (GTSRB) dataset to classify various types of traffic signs with high accuracy.

👨‍💻 Team Members
Reaal Mohamed – ID 20214167

Farida Mahmoud – ID 20210278

Ahmed Nasser – ID 20210087

Aysel Ashraf – ID 20192465

Kerelles Massak Rateb – ID 20212858

🎯 Objectives
Develop a CNN model capable of classifying traffic signs from images.

Preprocess and augment the GTSRB dataset for improved performance.

Achieve high accuracy suitable for real-time applications.

📈 Project Workflow
1. Data Collection & Preprocessing
Dataset: GTSRB with 50,000+ labeled images.

Preprocessing: Resizing to 32x32 pixels, normalization, and data augmentation (rotation, flipping, zooming).

2. Model Architecture
Built using CNN layers with activation and pooling.

Fully connected layers for final classification.

3. Training & Evaluation
Train/Val/Test split: 80% / 10% / 10%

Evaluation metrics: Accuracy, Precision, Recall, Confusion Matrix.

4. Deployment Readiness
Model optimized to run at 30 FPS on edge devices.

Saved in a deployable format.

💡 Challenges & Solutions
Challenge	Solution
Limited dataset	Used data augmentation to reduce overfitting
Real-time performance	Applied model quantization for speed without sacrificing accuracy
📊 Results
Model Accuracy: High accuracy on test data.

Performance: Real-time classification with optimized CNN.

Error Analysis: Misclassifications addressed with additional training data.

🔮 Future Improvements
Integrate region-specific traffic signs.

Enhance real-time detection with YOLO or SSD.

Expand training with real-world video feeds.

📷 Sample Code Snippet
plt.imshow(X_train[1000])
plt.axis('off')
print(X_train[1000].shape)
