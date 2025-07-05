# Microclimate Sensor Data Analysis

This project focuses on preprocessing and analyzing microclimate sensor data collected from various environmental sensors across Melbourne. The objective is to handle missing data effectively and apply clustering techniques to uncover patterns in environmental conditions.

## 📊 Project Tasks

- Identify and impute missing values using statistical methods (mean/median).
- Justify the choice of imputation strategy.
- Normalize and scale the dataset for clustering.
- Apply **K-Means Clustering** and **Hierarchical Clustering**.
- Visualize cluster assignments using dimensionality reduction (PCA).

## 📁 Files

- `microclimate_analysis.ipynb`: The main Jupyter Notebook with code and explanations.
- `microclimate_sensors_data.csv`: The dataset used (optional if not uploaded).
- `requirements.txt`: List of Python packages used (optional).
- `README.md`: Project overview and instructions.

## 📂 Dataset Source

- The dataset is publicly available on the City of Melbourne Open Data Portal:  
  👉 [Microclimate Sensors Data](https://data.melbourne.vic.gov.au/explore/dataset/microclimate-sensors-data/export/)

> 📌 **Note**: The dataset is used here for educational purposes only under the terms of the Open Government Licence.

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📌 How to Run

1. Download the dataset from the [official source](https://data.melbourne.vic.gov.au/explore/dataset/microclimate-sensors-data/export/).
2. Open the `microclimate_analysis.ipynb` notebook in Jupyter Notebook or Google Colab.
3. Follow the step-by-step analysis and visualization.

---

## 📈 Sample Output

- Heatmap of missing values
- Clusters of sensors based on environmental similarity
- PCA plots showing cluster separation

---

## 🤝 Acknowledgment

Thanks to the City of Melbourne for providing access to open microclimate sensor data.

