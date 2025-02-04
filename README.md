🎨 **PCA Visualization of MNIST Dataset**

Explore the fascinating world of dimensionality reduction with Principal Component Analysis (PCA), applied to the well-known MNIST dataset. This project demonstrates how to simplify high-dimensional data (784 features per image) into a 2D space while preserving its structure, making it easy to visualize.

🚀 **Project Highlights**

Dataset: MNIST – A collection of handwritten digit images.

Goal: Reduce 784-dimensional data into 2D using PCA and visualize digit classes in the reduced space.

**Tools Used:**

🐍 Python

📦 Libraries: numpy, matplotlib, scikit-learn

**📖 What’s Inside**

🔍 Key Steps:

1.Dataset Loading:

Fetch the MNIST dataset and extract a subset of 1000 samples for simplicity.

2.Dimensionality Reduction with PCA:

Transform the dataset from 784 features to just 2 principal components while retaining maximum variance.

3.Visualization:

Generate a scatter plot where each point represents a digit, colored according to its class.

**🌈 Visualization Output**

Here's an example of the PCA Scatter Plot:

Clusters: Each color represents a digit (e.g., purple for '0', yellow for '1', etc.).

Insight: Even in just 2 dimensions, PCA captures the separation between digit classes!

**🧠 Key Learnings**

Dimensionality Reduction: PCA helps reduce complex datasets while retaining meaningful information.

Visualization: With PCA, high-dimensional data like MNIST can be intuitively visualized.

Applications: PCA is widely used for feature reduction, exploratory data analysis, and noise reduction.
