# ✨ WMX Machine Learning: Anomaly Detection

WMX analytics shows peculiar patterns in data gathered from WMX masters.

Using the data (especially the DC diff), a new model is trained to detect anomalies from the analytic data of other systems.

## Prerequisites
Note that the Python environment where this notebook runs should already have **PyTorch** packages.

```sh
pip install scipy
pip install pandas
pip install seaborn
pip install -U scikit-learn
pip install -q -U watermark
pip install datasets
pip install huggingface-hub
pip install ipywidgets
```

## Datasets
**Normal DC diff** data for deep learning training can be loaded from the following the hugging face link. 

https://huggingface.co/datasets/Jake5/wmxdata

<img src="DC_Diff_normal.png" width="1500">

**Anomaly DC diff** data can be loaded from here. 

https://huggingface.co/datasets/Jake5/wmxdata
