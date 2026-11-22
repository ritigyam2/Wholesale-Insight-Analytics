# Wholesale Insight Analytics

A notebook-based customer segmentation project using wholesale purchasing data. It explores customer spending patterns and applies K-Means clustering and Principal Component Analysis (PCA) to examine groups with similar purchasing behaviour.

## Repository Contents

- `Wholesale Insight Analytics.ipynb` — data exploration, preprocessing, clustering, and visual analysis
- `wholesale_customers.csv` — dataset used by the notebook

## Requirements

Python 3 and the following packages:

- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

Install the dependencies:

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

## Run the Notebook

Clone the repository and move into its directory:

```bash
git clone https://github.com/ritigyam2/Wholesale-Insight-Analytics.git
cd Wholesale-Insight-Analytics
jupyter notebook "Wholesale Insight Analytics.ipynb"
```

Run the notebook cells in order. Keep `wholesale_customers.csv` in the repository root so the notebook can load the dataset.

## Method

The analysis uses exploratory data analysis to understand spending distributions, then applies K-Means to group customers. PCA is used to project the feature space for visual inspection.

Clustering results depend on preprocessing choices, scaling, and the selected number of clusters; the resulting groups should be interpreted as exploratory segments rather than fixed customer categories.

## License

See [LICENSE](LICENSE).
