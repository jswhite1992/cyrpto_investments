# crypto_investments

This Python notebook presents a method for clustering crypto market data using K-Means and Principal Component Analysis (PCA). The data is first loaded into a DataFrame, and exploratory data analysis is performed. Data scaling is done before applying K-Means clustering. The optimal number of clusters is determined using the Elbow method. A scatter plot is then generated to visualize the identified clusters. The dimensionality of the data is further reduced using PCA, and K-Means clustering is again applied on the reduced data. The optimal number of clusters in the reduced feature space is identified, and a scatter plot of the clusters in the reduced dimension space is generated.

---

## Technologies

This project leverages the following technologies:

- Python 3.7+
- Pandas
- Numpy
- Matplotlib
- Hvplot
- Scikit-learn
- Jupyter Notebook

---

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt` in your terminal.
3. Make sure you have the necessary data file `crypto_market_data.csv` in a directory named `Resources` at the root of your project.
4. Open the Jupyter Notebook `crypto_clustering.ipynb` in Jupyter Lab or Notebook.
5. Run the cells in the Jupyter Notebook to perform data scaling, K-Means clustering, PCA for dimensionality reduction, and visualizations.

Please note that the results of the clustering and PCA are based on the specific data provided and the settings used, and may vary with different data or settings.

## Contributors

This was an effort made possible by the teachings of the wonderful instructor Firas, along with contributions by James White.

---

## License

You are free to use or modify this source code as needed. Your feedback, bug reports, and improvements are welcomed.
