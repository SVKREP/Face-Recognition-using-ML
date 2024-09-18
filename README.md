Facial Recognition System
Overview
This project presents an advanced facial recognition system using machine learning techniques, such as MTCNN for face detection, data augmentation, and various classification models. The models are trained and tested on datasets with extensive data preprocessing and feature extraction for accuracy in face recognition.

Pipeline Overview
The system follows a structured pipeline:

Data Curation: Images grouped by person, stored in folders named after the individual.
Face Detection: Using MTCNN for precise facial landmark localization.
Data Augmentation: Horizontal flip, brightness, zoom, and rotation techniques are applied to increase dataset volume.
Feature Extraction: Utilizes models like FaceNet and ResNet50.
Dimensionality Reduction: PCA and LDA are applied for reducing the complexity.
Model Training: Trained on classifiers like KNN, SVM, Bayesian, and Decision Tree.
Evaluation Metrics: Accuracy, precision, recall, and F1 score.
Key Features:
MTCNN Face Detection: Detects faces and extracts key features with high accuracy.
Data Augmentation: Techniques applied to increase training data from 274 to 1644 images.
Feature Extraction Models: Uses FaceNet and ResNet50 for creating face embeddings and identifying patterns.
Dimensionality Reduction: Applies PCA and LDA for reducing feature dimensions and improving model efficiency.
Classification Algorithms: KNN, SVM, Bayesian, and Decision Tree models trained on extracted features for face recognition.
Performance Metrics: High recognition accuracy, with FaceNet+PCA achieving 100% accuracy in several scenarios.
Project Structure:
Data Curation: Grouping and preprocessing images based on individuals.
Model Training: Training using KNN, SVM, Bayesian, and Decision Tree classifiers on processed datasets.
Evaluation: Models evaluated using metrics like accuracy, recall, precision, and F1 score.
Results:
The project achieved impressive results, with the following accuracy rates:

FaceNet + PCA: 100% accuracy for face recognition.
ResNet50 + PCA: 93.55% accuracy, showing high performance but slightly lower than FaceNet.
Combined Approach: Using PCA+LDA further improved the results, making the recognition system highly efficient.
Challenges and Solutions:
Low Data Quantity: Resolved using extensive data augmentation.
Curse of Dimensionality: Overcome with dimensionality reduction techniques like PCA and LDA.
Multiple Faces in Single Image: Handled by cropping the largest face.
Poor Image Quality: Filtered out poor-quality images for better model training.
Task Distribution:
Sai Revanth Sivaraju: Data Curation, Data Augmentation, MTCNN, PCA, LDA, Fine Tuning.
Vamsi Krishna Satyasi: FaceNet experiments, PCA+LDA, Data Augmentation, Fine Tuning.
Rajashekar Vennavelli: ResNet50 experiments, PCA+LDA, Fine Tuning.
