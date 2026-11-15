# Data Mining and Statistical Analysis

A collection of academic Data Mining projects exploring statistical analysis, data preprocessing, dimensionality reduction, anomaly detection, association rules, web scraping and unsupervised learning.

## Academic Achievement

**Grade: Distinction**

Awarded a **Distinction for this Data Mining coursework** as part of my MSc Data Science programme at Queen Mary University of London.

The coursework involved applying data mining methods to diverse datasets, identifying patterns and relationships, and communicating findings through statistical analysis, machine learning techniques and visualisations.

## Project Overview

This repository contains two Data Mining assignments demonstrating practical applications of data analysis and machine learning techniques.

### Assignment 1 – Data Mining and Statistical Analysis

The first assignment explores fundamental data mining techniques across different datasets.

**Topics covered:**

- Descriptive and exploratory data analysis.
- Categorical feature identification and frequency analysis.
- Univariate and multivariate statistical summaries.
- Correlation analysis and scatterplot visualisation.
- Equal-frequency binning and smoothing by bin boundaries.
- Missing-value imputation using SimpleImputer.
- Categorical feature encoding using LabelEncoder.
- Income analysis by region, age and online shopping activity.
- Shoe size and height correlation analysis.
- Principal Component Analysis (PCA), with and without standardisation.
- Data cube creation and aggregation using the Cubes library.
- 1-Nearest Neighbour classification.

**Key techniques and tools:**

Python, Pandas, NumPy, Matplotlib, Scikit-learn, SciPy, PCA and data preprocessing.

### Assignment 2 – Advanced Data Mining Techniques

The second assignment explores advanced data mining concepts, including association rule evaluation, outlier detection, dimensionality reduction, web scraping and document clustering.

**Tasks covered:**

1. **Association Rule Mining:** Implementation of the Kulczynski measure to evaluate association rules using conditional probabilities and support values.

2. **Itemset Combinatorics:** Mathematical derivation of the total number of possible itemsets for a set of N items, expressed as 2^N.

3. **Univariate Outlier Detection:** Identification of outliers in monthly Paris rainfall data using the 1.5 × IQR method.

4. **Multivariate Outlier Detection:** Application of One-Class SVM with an RBF kernel to identify unusual patterns in daily stock returns for MSFT, Ford and Bank of America.

5. **PCA and kNN Outlier Detection:** Dimensionality reduction of housing data using PCA, followed by k-nearest-neighbour distance-based outlier scoring.

6. **Web Scraping and Data Cleaning:** Extraction of an online income and shopping habits table using BeautifulSoup, followed by cleaning and numerical conversion of the income column.

7. **Document Clustering:** Application of TF-IDF and K-means clustering to Wikipedia articles, using the elbow method to select the number of clusters.

## Selected Results and Findings

### Assignment 1

- Explored statistical relationships within the Wine dataset.
- Applied missing-value imputation and categorical encoding to country-income data.
- Investigated the relationship between shoe size and height using Pearson correlation.
- Compared PCA representations before and after feature standardisation.
- Created a data cube with region, age and online shopping dimensions.

### Assignment 2

- Identified rainfall of 5.49 mm as an outlier using the IQR method.
- One-Class SVM identified 124 outliers among 2,517 stock-return observations, representing approximately 4.93%.
- The first two PCA components of the housing dataset explained approximately 58% of the variance.
- Used TF-IDF and K-means to organise 11 Wikipedia articles into three semantic clusters.
- Identified thematic groupings around business intelligence, machine learning and unsupervised learning.

## Technologies and Tools

- Python
- Google Colab
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn
- BeautifulSoup
- Cubes
- Statistical Analysis
- Data Preprocessing
- Principal Component Analysis
- One-Class SVM
- k-Nearest Neighbours
- TF-IDF
- K-means Clustering
- Association Rule Mining

## Repository Structure

```text
data-mining-and-statistical-analysis/
│
├── assignment-1/
│   └── data_mining_assignment_1.ipynb
│
├── assignment-2/
│   └── advanced_data_mining_assignment_2.ipynb
│
└── README.md
```

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/anvithasubramani/data-mining-and-statistical-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd data-mining-and-statistical-analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib scipy scikit-learn beautifulsoup4 requests
   ```

4. Install the Cubes library if running the data cube section:

   ```bash
   pip install cubes
   ```

5. Open the relevant notebook using Jupyter or Google Colab.

6. Obtain the required datasets and update file paths where necessary.

**Note:** Some datasets are external or local coursework files and are not included in this repository. The notebooks may require path updates before execution.

## Author

**Anvitha Priyaa Vellal Subramani**

MSc Data Science | Queen Mary University of London

- GitHub: [anvithasubramani](https://github.com/anvithasubramani)
- LinkedIn: [Anvitha Priyaa Subramani](https://www.linkedin.com/in/anvitha-subramani-717356305/)

---

*This repository showcases practical experience in statistical reasoning, data mining, data preprocessing, anomaly detection, dimensionality reduction, web scraping and unsupervised machine learning.*
