# Unsupervised_Analysis_of_Chest_Radiograph
Our project explores predictive analytics classifying scans combined with text summarization of visual patterns. Together, this pipeline aims to replicate manual review more efficiently. We cluster images based on common anatomy, map new scans to these groups via algorithms, and generate summaries reflecting assigned clusters. Effectively we transform image insights into accessible data.

# Radiology Image Analysis

This Jupyter notebook performs unsupervised clustering and analysis on chest x-ray images and radiology reports.

## Contents

The key sections are:  

- **Data Loading**: Load image pixel data and metadata like radiology reports 
- **Preprocessing**: Clean missing text, extract captions by combining report columns  
- **Clustering**: Use k-means on image features extracted with VGG16 CNN
- **Text Analysis**: Summarize reports by cluster, compare problems and impressions
- **Visualizations**: t-SNE plots of clusters, co-occurrence networks, word clouds

## Usage

Main workflow to reproduce analysis:

1. Run data loading and preprocessing  
2. Extract features and cluster images
3. Analyze clusters and text patterns   
4. Generate summaries, visualizations
5. Cluster Analysis for new image

## Result
<img width="550" alt="Screenshot 2023-12-11 at 11 49 26 PM" src="https://github.com/jayathachan/Unsupervised_Analysis_of_Chest_Radiograph/assets/130102026/02167d5c-3673-4c7d-9ade-effaabc5d78f">


## Dependencies

- NumPy, Pandas, Scikit-Learn, Matplotlib
- NLTK, Transformers
- Keras, TensorFlow

## Dataset Source: [https://openi.nlm.nih.gov/faq#collection]

