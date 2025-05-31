
# LSTM Attribution Analysis for Univariate Time Series

This repository contains code and data to reproduce the experiments from the research paper:

**Title:** _Explaining LSTM Models for Univariate Time Series Classification: A Comparative Study of Attribution-Based XAI Methods_

## 🔍 Objective

To benchmark attribution-based XAI methods (DeepLIFT SHAP, Integrated Gradients, Saliency Maps) on LSTM models trained on UCR univariate time series datasets such as:

- ItalyPowerDemand
- ECG200

## 📁 Structure

- `data/` – Dataset sources and processing
- `notebooks/` – Analysis and visualization notebooks
- `src/` – Modular code for preprocessing, modeling, attribution
- `results/` – Output visualizations and evaluation metrics
- `figs/` – Final figures for paper

## 🛠️ Installation

```bash
git clone https://github.com/your-username/lstm-xai-timeseries.git
cd lstm-xai-timeseries
pip install -r requirements.txt
