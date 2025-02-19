# Wine Dataset Clustering

This repository contains a Jupyter Notebook that demonstrates clustering on the Wine dataset using the K-Means algorithm. The Wine dataset consists of 178 samples with 13 features representing different chemical properties of wines.

## Dataset Description

The dataset contains 178 entries with the following columns:

| #   | Column                | Non-Null Count | Dtype  | Description |
| --- | --------------------- | -------------- | ------ | ----------- |
| 0   | Alcohol               | 178            | float64| The alcohol content in wine |
| 1   | Malic_Acid            | 178            | float64| The amount of malic acid in wine |
| 2   | Ash                   | 178            | float64| The ash content in wine |
| 3   | Ash_Alcanity          | 178            | float64| The alcalinity of ash in wine |
| 4   | Magnesium             | 178            | int64  | The magnesium content in wine |
| 5   | Total_Phenols         | 178            | float64| The total phenols content in wine |
| 6   | Flavanoids            | 178            | float64| The flavanoids content in wine |
| 7   | Nonflavanoid_Phenols  | 178            | float64| The nonflavanoid phenols content in wine |
| 8   | Proanthocyanins       | 178            | float64| The proanthocyanins content in wine |
| 9   | Color_Intensity       | 178            | float64| The color intensity of wine |
| 10  | Hue                   | 178            | float64| The hue of wine |
| 11  | OD280                 | 178            | float64| The OD280/OD315 of diluted wines |
| 12  | Proline               | 178            | int64  | The proline content in wine |

- **Non-Null Count**: All columns have 178 non-null values.
- **Dtype**: There are 11 columns of type `float64` and 2 columns of type `int64`.

## Clustering Model

The Jupyter Notebook in this repository performs K-Means clustering on the Wine dataset. Here is a summary of the steps:

1. **Data Loading**: The dataset is loaded into a pandas DataFrame.
2. **Data Standardization**: The features are standardized to have zero mean and unit variance.
3. **K-Means Clustering**: A K-Means model is trained to cluster the data into three clusters.
4. **Label Assignment**: The resulting cluster labels are added to the DataFrame.
5. **Visualization**: Various plots are created to visualize the clustering results.

## Results

After running the notebook, you will see the clustered data along with visualizations that help in understanding the distribution of clusters across different features. The clusters are labeled in the `Labels` column of the DataFrame.

## Conclusion

This project demonstrates how to perform clustering on a real-world dataset using the K-Means algorithm. The Wine dataset, with its various chemical properties, provides a good example for clustering analysis.

## License

This project is licensed under the MIT License.

## Acknowledgements

- The Wine dataset is sourced from the UCI Machine Learning Repository.
- Thanks to the developers of pandas, NumPy, Matplotlib, Seaborn, and scikit-learn for their excellent libraries.
