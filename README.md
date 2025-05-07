# Data Analysis and Trial Store Performance Evaluation

## Overview
This project performs exploratory data analysis (EDA) and evaluates the performance of a trial store compared to a control store. The analysis is conducted on a retail transaction dataset, focusing on total sales, customer transactions, and outlier detection. The objective is to derive insights for assessing the success of a trial store and to clean the dataset by removing any outliers.

## Technologies Used
- **Python**: For data manipulation and analysis.
- **Pandas**: For loading and handling the dataset.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating visualizations (e.g., boxplots, histograms).
- **Seaborn**: For statistical plots (e.g., KDE plots).

## Dataset
- **QVI_transaction_data.xlsx**: The dataset used contains transactional sales data with various columns, including:
  - `STORE_NBR`: Store number identifier.
  - `TXN_ID`: Transaction identifier.
  - `TOT_SALES`: Total sales for each transaction.
  - Other columns contain product information and sales data.

## Key Steps in the Analysis

### 1. **Loading Data**
The dataset is loaded into a Pandas DataFrame using `pd.read_excel()`.

```python
dataset = pd.read_excel("QVI_transaction_data.xlsx")
