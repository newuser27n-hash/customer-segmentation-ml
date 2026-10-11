# customer-segmentation-ml
Machine learning project comparing demographic and behavioural customer segmentation.
# Customer Segmentation Using Machine Learning

## Project Overview
This project compares demographic and behavioural customer segmentation using machine learning. It evaluates how feature selection affects clustering quality, stability, and marketing usefulness.

## Research Objective
To determine whether demographic, behavioural, or combined customer features produce more useful and reliable customer segments.

## Methodology
- Data cleaning and missing-value treatment
- Feature scaling using StandardScaler
- K-Means and hierarchical clustering using Ward linkage
- Evaluation using Silhouette Score, Davies–Bouldin Index, and Calinski–Harabasz Index
- Stability testing and external validation using campaign response
- Robustness and sensitivity analysis

## Key Findings
Behavioural features produced stronger internal clustering quality than demographic or combined features in the main three-cluster comparison. Demographic segmentation showed the widest spread in campaign response rates. The results are observational and should not be interpreted as evidence of causation.

## Repository Contents
- `Customer_Segmentation_Project.ipynb` — analysis notebook
- `Customer_Segmentation_Project.html` — notebook export
- `Customer_Segmentation_Research_Article.pdf` — research article
- `Literature_Review_Matrix_FINAL.xlsx` — literature review matrix
- `marketing_campaign.csv` — dataset
- `results_figures_and_tables/` — analysis outputs

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries listed in `requirements.txt`, once added.
3. Download or clone this repository.
4. Open the notebook and run its cells in order.
5. Ensure the dataset path in the notebook matches the local file location.

## Limitations
The original dataset's exact source and version have not been confirmed. Cluster profiles describe associations, not causal effects. Spending-related validation must be interpreted carefully when spending variables are also used to construct clusters.

## Team
Disha Srivastava, Ayush Tanwal, Bhavya Sharma, Kanishka Jain, and Rohit Joshi.
