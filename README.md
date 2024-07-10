
# Analysing mouse brain circadian rhythm using k-means for periodicity

## Description

This Jupyter notebook is designed to perform the following tasks:

- Perform the new $k$-means clustering.
- Plot the cluster label color map image for the data with 6 clusters.
- Plot the mean time series for each of the clusters.

Remember that you only use the first 800 samples, so it may be necessary to slice other arrays accordingly.

## Table of Contents

- [Description](#description)
- [Instructions](#instructions)
- [Data Handling](#data-handling)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [License](#license)

## Instructions

1. **$k$-means Clustering**:
   - Implement the $k$-means clustering algorithm in the designated cell(s).
   - Ensure that you configure the algorithm to use 6 clusters.

2. **Cluster Label Colormap**:
   - Plot the cluster label color map image using the results from the $k$-means clustering.
   - Use appropriate plotting libraries such as Matplotlib or Seaborn to visualize the clusters.

3. **Mean Time Series Plot**:
   - Compute the mean time series for each of the clusters.
   - Plot these mean time series to visualize the average behavior of the data within each cluster.

## Data Handling

- Only the first 800 samples are to be used for the clustering and subsequent plots.
- It may be necessary to slice other arrays to match this requirement.

## Dependencies

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Usage

To run this notebook, follow these steps:

1. Clone the repository and navigate to the directory containing the notebook.
2. Ensure you have all the dependencies installed. You can use the following command to install the necessary packages:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Open the notebook using Jupyter:

   ```bash
   jupyter notebook circadian_rhythm_using _k_means.ipynb
   ```

4. Execute the cells in the notebook sequentially to perform the $k$-means clustering, plot the colormap, and plot the mean time series for each cluster.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to edit or expand this `README.md` file as needed. If there are specific details or additional instructions you'd like to include, let me know!