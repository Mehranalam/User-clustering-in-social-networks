# User Clustering in Social Networks

## Overview
This project focuses on clustering users in social networks based on their interactions and features. The goal is to identify meaningful communities or groups of users with similar behaviors, which can be useful for recommendations, targeted marketing, and network analysis.

The core implementation is contained in the Jupyter Notebook [`Clustering.ipynb`](https://github.com/Mehranalam/User-clustering-in-social-networks/blob/main/Clustering.ipynb), where different clustering techniques are applied and evaluated.

## Features
- **Data Preprocessing**: Cleaning and transforming the dataset for clustering.
- **Feature Engineering**: Creating meaningful features from raw social network data.
- **Clustering Methods**: Implementation of clustering algorithms such as K-Means, DBSCAN, and Agglomerative Clustering.
- **Evaluation**: Measuring clustering performance using silhouette score, Davies-Bouldin index, and visualization techniques.

## Requirements
To run this project, you need the following Python libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn networkx
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Mehranalam/User-clustering-in-social-networks.git
   cd User-clustering-in-social-networks
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Clustering.ipynb
   ```
3. Run the cells step by step to preprocess the data, perform clustering, and visualize the results.

## Results
The notebook provides detailed visualizations and clustering analysis, including:
- Cluster distribution plots
- Network graphs
- Evaluation metrics comparison

## Future Work
- Improve feature selection for better clustering results.
- Experiment with deep learning-based clustering techniques.
- Apply clustering on larger-scale datasets.

## Author
- **Mehran Alam**
- GitHub: [Mehranalam](https://github.com/Mehranalam)

## License
This project is open-source and available under the MIT License.

