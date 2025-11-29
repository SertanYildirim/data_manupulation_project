# 📈 Data Master: Advanced Time Series & ETL Platform

A comprehensive, **No-Code Data Analysis Platform** built with **Python & Streamlit**. This application facilitates the entire **ETL (Extract, Transform, Load)** and **Predictive Modeling** lifecycle through an intuitive, modular interface. This project demonstrates expertise in building production-ready data pipelines and quantitative analysis tools.

## 🚀 Architectural Highlights

* **End-to-End Pipeline:** Covers the complete workflow: from **Inference (Loading)** to **Advanced Transformation** to **Persistence (Exporting)**.
* **Deep Learning & Econometrics:** Integrates both traditional models (ARIMA/SARIMAX) and deep learning models (LSTM/GRU) for forecasting sequential data.
* **MLOps Readiness:** Modular architecture ensures scalability and ease of integration into larger MLOps/Data Engineering workflows.

## 🧠 Feature Matrix (Technical Scope)

| Phase | Module Focus | Advanced Capabilities & Tools |
| :--- | :--- | :--- |
| **Data Ingestion** | Loader | Auto-detects delimiter, supports CSV, JSON, XLSX, and SQLite DB files. |
| **Data Cleaning** | Missing Data & Outliers | **KNN Imputer** (AI-based missing value replacement) and **DBSCAN** (Clustering for outlier detection). |
| **Feature Engineering** | Transformation | **One-Hot Encoding, Min-Max Scaling,** and **Dynamic Feature Creation** (generating custom features using `exec()`). |
| **Forecasting** | Time Series | **6 Diverse Models:** **LSTM, GRU, Prophet, SARIMAX, ARIMA, TES.** |
| **Persistence (Export)** | Exporter | Direct data transfer to **PostgreSQL, MSSQL, MongoDB,** and Parquet file formats. |

## 🛠️ Technical Stack

* **Frontend:** Streamlit (Interactive UI)
* **Core Logic:** Python 3.10+, Pandas, NumPy
* **Machine Learning:** Scikit-learn, Keras/TensorFlow (**LSTM/GRU**), Statsmodels
* **Visualization:** Plotly, Matplotlib, Seaborn
* **Database Connectors:** SQLAlchemy (PostgreSQL, MSSQL), PyMongo (MongoDB)

## 📦 How to Run

1.  **Clone the repository.**
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Start Application:**
    ```bash
    streamlit run main.py
    ```

---
*This project demonstrates expertise in Full-Stack Data Engineering, Advanced Statistical Modeling, and MLOps Readiness.*

![System Architecture](Data_Manipulation_Architecture.png)

## 📂 Project Structure

```bash
├── main.py              # Application Entry Point & Navigation Logic
├── modules/             # Core Functional Modules
│   ├── loader.py        # Data Import Logic
│   ├── cleaner.py       # Missing Value Handling
│   ├── eda.py           # Exploratory Analysis
│   ├── transformer.py   # Data Transformation
│   ├── time_series.py   # Time Series Logic
│   ├── visualizer.py    # Charting Engine
│   └── ...              # Other helper modules
├── requirements.txt     # Project Dependencies
└── README.md            # Documentation
