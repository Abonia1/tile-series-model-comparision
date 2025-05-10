
# 🌟 **A Taxonomy of Time Series Forecasting Models**

### 📚 **Abstract**

This repository presents a systematically curated taxonomy of **time series forecasting models**, tailored for both **theoretical research** and **industrial applications**. Time series analysis is a critical component in domains such as **predictive maintenance**, **supply chain optimization**, and **financial econometrics**. Selecting an appropriate model requires a nuanced understanding of the data structure (e.g., **univariate vs. multivariate**), the need for **probabilistic forecasts**, multi-series generalization, and the incorporation of **covariates**.

This repository provides a comparative analysis of state-of-the-art time series models, including **classical statistical methods**, **Bayesian approaches**, **machine learning algorithms**, **deep learning architectures**, and **hybrid frameworks**.

---

### 🧠 **Research Motivation**

The rapidly evolving landscape of time series forecasting necessitates a **systematic taxonomy** to facilitate model selection based on data characteristics and forecasting requirements. This repository aims to bridge the gap between theoretical research and practical implementation by categorizing models according to their structural and functional properties.

---

### 📝 **Model Taxonomy**

The table below presents a comprehensive comparison of time series forecasting models, structured by their **key capabilities**:

| Model                                  | Univariate | Multivariate | Probabilistic | Multiple Series (Global) | Past-Observed Covariates | Future-Known Covariates | Static Covariates | Reference                                              |
| -------------------------------------- | ---------- | ------------ | ------------- | ------------------------ | ------------------------ | ----------------------- | ----------------- | ------------------------------------------------------ |
| **Classical Statistical Models**       |            |              |               |                          |                          |                         |                   |                                                        |
| ARIMA                                  | ✅          |              | ✅             |                          | ✅                        |                         |                   | Box & Jenkins (1976)                                   |
| VARIMA                                 | ✅          | ✅            |               |                          | ✅                        |                         |                   | Lütkepohl (2005)                                       |
| AutoARIMA                              | ✅          |              |               |                          | ✅                        |                         |                   | Hyndman & Khandakar (2008)                             |
| StatsForecastAutoARIMA                 | ✅          |              | ✅             |                          | ✅                        |                         |                   | Nixtla’s statsforecast                                 |
| Exponential Smoothing                  | ✅          |              | ✅             |                          |                          |                         |                   | Hyndman et al. (2008)                                  |
| Holt-Winters                           | ✅          |              |               |                          |                          |                         |                   | Holt (1957), Winters (1960)                            |
| STL (Seasonal-Trend Decomposition)     | ✅          |              |               |                          |                          |                         |                   | Cleveland et al. (1990)                                |
| **Bayesian and State-Space Models**    |            |              |               |                          |                          |                         |                   |                                                        |
| KalmanForecaster                       | ✅          | ✅            | ✅             |                          | ✅                        |                         |                   | Kalman (1960)                                          |
| BSTS (Bayesian Structural Time Series) | ✅          | ✅            | ✅             |                          | ✅                        |                         |                   | Scott & Varian (2014)                                  |
| DLM (Dynamic Linear Models)            | ✅          | ✅            | ✅             |                          | ✅                        |                         |                   | West & Harrison (1997)                                 |
| GPR (Gaussian Process Regression)      | ✅          |              | ✅             |                          |                          |                         |                   | Rasmussen & Williams (2006)                            |
| **Machine Learning Models**            |            |              |               |                          |                          |                         |                   |                                                        |
| RandomForest                           | ✅          | ✅            |               | ✅                        | ✅                        | ✅                       | ✅                 | Breiman (2001)                                         |
| LightGBM                               | ✅          | ✅            | ✅             | ✅                        | ✅                        | ✅                       | ✅                 | Ke et al. (2017)                                       |
| **Deep Learning Models**               |            |              |               |                          |                          |                         |                   |                                                        |
| RNNModel (LSTM, GRU, DeepAR)           | ✅          | ✅            | ✅             | ✅                        |                          | ✅                       |                   | Hochreiter & Schmidhuber (1997), Salinas et al. (2020) |
| TransformerModel                       | ✅          | ✅            | ✅             | ✅                        | ✅                        |                         |                   | Vaswani et al. (2017)                                  |
| TFTModel                               | ✅          | ✅            | ✅             | ✅                        | ✅                        | ✅                       | ✅                 | Lim et al. (2021)                                      |
| **Hybrid Models**                      |            |              |               |                          |                          |                         |                   |                                                        |
| ARIMA-LSTM                             | ✅          | ✅            | ✅             | ✅                        | ✅                        |                         |                   | Zhang (2003), Qin et al. (2017)                        |
| **Anomaly Detection Models**           |            |              |               |                          |                          |                         |                   |                                                        |
| LSTM-Autoencoder                       | ✅          | ✅            |               |                          |                          |                         |                   | Malhotra et al. (2016)                                 |
| VAE (Variational Autoencoder)          | ✅          | ✅            | ✅             |                          |                          |                         |                   | Kingma & Welling (2014)                                |



---

### 🌍 **Research Contributions**

This repository aims to foster collaboration among researchers by consolidating foundational and advanced models. Feel free to open issues for:

* Suggesting new models or categorizations
* Providing feedback on existing comparisons
* Sharing your experimental results

---

### 📜 **Citing this Repository**

If you find this taxonomy useful, please cite it as:

```
@misc{TimeSeriesTaxonomy2025,
  author = {Abonia Sojasingarayar},
  title = {A Taxonomy of Time Series Forecasting Models - Industrial Applications},
  year = {2025},
  howpublished = {GitHub repository},
  url = {https://github.com/Abonia1/time-series-taxonomy}
}
```

---

### 🤝 **Connect**

For academic discussions or potential collaborations, please contact me via GitHub or LinkedIn.


