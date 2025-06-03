
# 🛍️ Customer Segmentation using Clustering - Online Retail

This repository provides a comprehensive notebook that performs customer segmentation using clustering techniques (like KMeans) on online retail transaction data. This type of analysis is widely used in marketing and business intelligence.

## 📁 Project Structure

- `Clustering Python Online Retail.ipynb`: Main Jupyter Notebook that includes:
  - Data loading and cleaning
  - Exploratory Data Analysis (EDA)
  - Feature engineering (RFM - Recency, Frequency, Monetary)
  - KMeans clustering
  - Visualizations and evaluation

## 🔧 Requirements

Install the necessary dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can create a `requirements.txt` using:

```bash
pip freeze > requirements.txt
```

## 📊 Dataset

This analysis uses the **Online Retail Dataset** available on the UCI Machine Learning Repository or [Kaggle](https://www.kaggle.com/datasets).

It contains transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

**Key Fields**: `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/retail-clustering.git
   cd retail-clustering
   ```

2. Open the notebook:
   ```bash
   jupyter notebook
   ```

3. Run all cells in `Clustering Python Online Retail.ipynb`

## 📈 Techniques Used

- RFM (Recency, Frequency, Monetary) Analysis
- KMeans Clustering
- Elbow Method to find optimal clusters
- PCA (optional) for dimensionality reduction
- Visualizations using seaborn and matplotlib

## 🧠 Future Improvements

- Try DBSCAN or Hierarchical clustering
- Deploy as a dashboard (Streamlit/Flask)
- Add automated cluster profiling

## 📬 Contact

For queries or collaborations:
- Email: vaibhavdesai682@gmail.com


⭐️ Star this repo if it helped you learn!
