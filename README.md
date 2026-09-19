
# 🌿 Plant Leaf Segmentation & Classification

An image processing and machine learning project for the automated segmentation and classification of plant leaves using image processing techniques and handcrafted visual features.

The system takes a plant leaf image as input and produces:

🖼️ A binary segmentation image containing only the plant leaf.
🌿 The predicted plant species/class.

The project is divided into two main phases:

Phase 1: Plant leaf segmentation
Phase 2: Feature extraction and plant classification

# 🌱 Plant Classes

The dataset contains 10 plant classes:


1	Alstonia Scholaris
2	Arjun
3	Basil
4	Chinar
5	Jamun
6	Jatropha
7	Lemon
8	Mango
9	Pomegranate
10	Pongamia Pinnata

# Phase 1 — Leaf Segmentation

The first phase focuses on automatically extracting the plant leaf from each input image.

The provided images contain:

Low contrast
Salt-and-pepper noise
Background regions
Variations in illumination

Therefore, preprocessing and segmentation are required before classification.

# Phase 2 — Feature Extraction & Classification

After segmentation, the binary leaf images are used to extract meaningful features.

The extracted features are organized into a feature table, where:

Each row represents an image.
Each column represents a feature.

The feature table is then divided into training and testing sets and used to train a classifier.

# Technologies Used

Python	
OpenCV	
NumPy	
Pandas	
Matplotlib	
Scikit-learn	
