# Optimized Cellular Traffic Prediction
---

##  Overview

With the rapid growth in mobile data usage (streaming, gaming, IoT), cellular networks face dynamic load patterns. This project proposes a hybrid approach combining:

- **LSTM-based deep learning** for time-series forecasting  
- **Data reduction techniques** (feature selection, PCA) to improve efficiency  

The goal is to provide network operators with accurate traffic predictions and efficient models suitable for deployment.

---

##  Features & Contributions

- Preprocessing: missing data handling, normalization, outlier removal  
- Dimensionality reduction: PCA + correlation-based feature selection  
- LSTM architecture (with dropout, etc.) for sequential prediction  
- Comparative benchmarking: ARIMA, SVM, XGBoost, Decision Trees, etc.  
- Visualization of results: loss curves, feature distributions, error metrics  

---

## Repository Structure

```
.
├── IEEE.pdf
├── Project_Report.pdf
├── optimized_cellular_traffic.ipynb
├── README.md
├── data/                    
├── results/                 
└── requirements.txt         
```


---

## Getting Started

### Prerequisites

- Python 3.x  
- Jupyter Notebook / JupyterLab  

### Installation Steps

```bash
git clone https://github.com/reachvickie/optimized-cellular-traffic-prediction.git
cd optimized-cellular-traffic-prediction
pip install -r requirements.txt
```

### Running the Notebook

Launch Jupyter:

```bash
jupyter notebook optimized_cellular_traffic.ipynb
```

The notebook walks through the entire pipeline: data loading, preprocessing, model training, evaluation, and visualization.

---

## Experimental Results & Metrics

Key results:

- LSTM Accuracy: **98.84%**  
- XGBoost: 98.23%  
- RBF-SVM: 96.55%  
- Decision Tree: 96.28%  
- Logistic Regression: 83.69%  
- Naive Bayes: 71.29%  

LSTM consistently outperforms traditional models in accuracy and scalability. Real-time prediction latency < **0.2s**.

---

## Future Work & Extensions

- Extend to **5G / 6G** datasets  
- Real-time streaming / online learning  
- Multi-variate forecasting (weather, mobility, user behavior)  
- Deployment pipeline (API, microservice)  
- Model pruning, quantization for edge deployment  

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## Contact

- **Vignesh A. (reachvickyy@gmail.com)**  
- Project Repo: [Optimized Cellular Traffic Prediction](https://github.com/reachvickie/optimized-cellular-traffic-prediction)
