# Classify-Students-Based-on-Study-Methods_202401100400056
Classify Students Based on Study Methods
Introduction
Understanding how students learn can significantly enhance educational outcomes. This project aims to categorize students into different learning styles using unsupervised machine learning. Using data from a questionnaire with scores on visual, auditory, and kinesthetic preferences, we apply clustering to group students based on learning behaviours.

 Methodology
1.	Dataset: The dataset includes scores representing student preferences for visual, auditory, and kinesthetic learning styles. Each student has a known label, which is used only for evaluation.
2.	Preprocessing:
o	Standardize feature data using Standard Scaler to normalize scale.
3.	Clustering Model:
o	Use K Means with k=3 to identify learning style clusters.
4.	Evaluation:
o	Map clusters to known labels via majority voting.
o	Compute a confusion matrix, and visualize it as a heatmap.
o	Calculate accuracy, precision, recall, and F1-score using classification report.
