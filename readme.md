# Multivariate Time Series Anomaly Detection

This repository explores **various types of anomalies** that can occur in multivariate time series data, including but not limited to:

- Peripheral points  
- Local density anomalies  
- Global density anomalies  
- Local additive anomalies  
- Deviant cycles 
and others

These anomalies are demonstrated and analyzed in `Anomalies.ipynb`.  

## Anomaly Detection Methods

The repository provides implementations of **different methods for detecting anomalies** in multivariate time series data, including both **machine learning** and **deep learning** approaches:

### Machine Learning Methods
- **DBSCAN / DDBSCAN** – Density-based clustering methods  
- **EIF** – Extended Isolation Forest  
- **VAR / VECM / VARMAX** – Vector Autoregressive models for multivariate time series  

### Deep Learning Methods
- **INRAD** – Time-Series Anomaly Detection using Implicit Neural Representations  
  - Reference: [INRAD Paper](https://arxiv.org/pdf/2201.11950)  
- **USAD** – Unsupervised Anomaly Detection on Multivariate Time Series  
  - Reference: [USAD Paper](https://dl.acm.org/doi/pdf/10.1145/3394486.3403392)  

Each method is implemented in its own Jupyter Notebook, clearly named according to the technique.