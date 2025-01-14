# Binary Leaves Classification

## Overview
This project aims to classify five types of leaves using binary image processing techniques. The dataset consists of binary images of leaves, which vary in rotation, scale, and natural shape differences. The classification can be approached using handcrafted features, machine learning algorithms, or advanced models.

## Dataset
The dataset is organized into folders, each representing a leaf type. A `labels.json` file maps numeric labels to leaf names.

### Leaf Types
1. Japanese Maple  
2. Chinese Cinnamon*  
3. Ginkgo (Maidenhair Tree)  
4. Chinese Tulip Tree*  
5. Tangerine  

(*Optional: These can be omitted for initial analysis.)

## Tasks
1. **Extract Features**  
   Use binary image properties like area, perimeter, circularity, and Hu moments to describe the leaves.  

2. **Classification**  
   - Handcrafted rules  
   - Machine learning (e.g., K-Nearest Neighbors)  
   - Advanced models (e.g., Multi-Layer Perceptron)  

3. **Evaluation**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  

## Getting Started

### Prerequisites
- Python 3.8+
- Libraries: `numpy`, `matplotlib`, `opencv-python`


### Setting Up
1. Clone the repository or download the dataset.  
2. Install dependencies using `pip install -r requirements.txt`.

## Key Steps

### 1. Load and Display Images
Visualize sample images from the dataset to understand its structure.

### 2. Feature Extraction
Compute binary image properties:
- Area
- Perimeter
- Circularity
- Hu Moments

### 3. Classification
- Start with 2-3 leaf types, then expand to all 5.
- Use classification algorithms to distinguish between leaf types.

### 4. Evaluation
Analyze and summarize results, focusing on:
- Leaf types that are easy/difficult to classify
- Overall performance metrics

## Hints
- Combine multiple features for better results.  
- Normalize or scale features if combining them.  
- Avoid sensitive moments like `hu_3` and `hu_4`.

## Results
Include a summary of the classification results here, such as:
- Accuracy for each leaf type
- Confusion matrix
- Insights into difficult-to-classify leaves

## License
This project is for educational purposes. Use the code and dataset responsibly.

