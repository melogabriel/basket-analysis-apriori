# README

This code performs association analysis on a sales dataset, using the Apriori algorithm. The dataset is loaded from an Excel file, and a basket of items is created for each transaction. The Apriori algorithm is then applied to find frequent itemsets and association rules based on the support, confidence, and lift metrics. Finally, the top 10 associations based on lift are plotted in a scatter plot, and the results are saved to an Excel file.

## Installation

This code requires the following packages:

- `numpy`
- `pandas`
- `mlxtend`
- `apriori`

## Usage

1. Download the `perfumes.xlsx` file or replace it with your own dataset.
2. Run the `Market_Basket_Analysis.ipynb` jupyter notebook.
3. The results will be saved to an Excel file named `product_categories_correlations.xlsx`.

## Results

The results of the association analysis are saved in the `product_categories_correlations.xlsx` file. The file contains a table of frequent itemsets and their associated metrics (support, confidence, and lift), as well as a table of association rules and their associated metrics.

In addition, a scatter plot is generated showing the top 10 associations based on lift. The plot shows the antecedents and consequents of each association, with the lift value represented by the color of each point.

## Future Improvements

- Include more metrics for association analysis such as conviction, leverage, and Kulczynski measure.
- Implement different algorithms for association analysis such as FPGrowth, Eclat.
- Use a web interface to make it easier for users to upload their datasets and run association analysis.
