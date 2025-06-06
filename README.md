# 📦 FedEx EDA (Exploratory Data Analysis)

This project performs an in-depth Exploratory Data Analysis (EDA) on the **SCMS Delivery History Dataset** related to FedEx logistics. The goal is to derive insights into the shipping patterns, costs, and performance metrics to assist in making data-driven decisions.

## 📁 Dataset

The dataset used is `SCMS_Delivery_History_Dataset.csv`, which contains shipment and delivery records, including:
- Country  
- Shipment mode  
- Product group/type  
- Delivery status  
- Lead time  
- Freight cost  
- Planned vs actual delivery dates  

## 🧰 Libraries Used

```python
import numpy as np  
import pandas as pd  
import matplotlib.pyplot as plt  
import seaborn as sns  
import plotly.express as px  
import plotly.graph_objs as go  
```

## 🔍 Key Explorations

- Data overview and cleansing  
- Value counts and null analysis  
- Shipment mode and cost breakdown  
- Delivery time distributions  
- Country-level delivery performance  
- Correlation analysis and heatmaps  
- Visualizations with Seaborn and Plotly  

## 📊 Visual Insights

The project includes interactive and static plots to explore:
- Shipment mode vs freight cost  
- Country-wise delivery volume  
- Delay patterns and their impact  
- Relationships between financial and delivery metrics  

## 🧠 Key Takeaways

- Certain countries show consistently higher freight costs.  
- Air shipments, while faster, tend to be significantly more expensive.  
- Delays are more common in specific regions or shipment modes.  
- Strong correlation between delivery time and shipment method.  

## 📝 How to Run

1. Clone the repository  
2. Open the `Fed-ex-EDA.ipynb` notebook in Jupyter/Colab  
3. Ensure the dataset file is present in the same directory  
4. Run the cells step by step  

## 📌 Requirements

- Python 3.7+  
- pandas, numpy  
- matplotlib, seaborn  
- plotly  
