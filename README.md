# R E-Commerce Clothing Review Analysis

This project analyzes women's e-commerce clothing reviews using R and Quarto.

The analysis explores customer review text, ratings, recommendation behavior, and review patterns using text mining and statistical modeling methods.

## Files

```text
r-ecommerce-review-text-mining/
├── README.md
├── clothing_review_analysis.qmd
└── report.pdf
```

## Data

This project uses the **Women's E-Commerce Clothing Reviews** dataset from Kaggle:

https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews

The CSV file is not included in this repository.

To run the analysis, download the dataset from Kaggle and place the CSV file in the same folder as the `.qmd` file.

The expected file name is:

```text
Womens Clothing E-Commerce Reviews.csv
```

## Methods Used

This project includes:

- data cleaning
- exploratory data analysis
- text preprocessing
- TF-IDF
- SVD
- k-means clustering
- logistic regression
- model evaluation
- Quarto report writing

## How to Run

Make sure R and Quarto are installed.

Install the required R packages:

```r
install.packages(c(
  "tidyverse",
  "tidytext",
  "ggplot2",
  "broom",
  "cluster",
  "Matrix",
  "irlba",
  "MASS",
  "knitr",
  "scales",
  "forcats"
))
```

Render the Quarto file:

```bash
quarto render clothing_review_analysis.qmd
```

## Notes

This project focuses on using text mining and statistical modeling to understand customer review patterns and predict whether a customer recommends a product.
