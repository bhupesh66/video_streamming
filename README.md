# Video Streamming Pipeline

Seamless flow for video streaming data pipeline using a **Bronze–Silver–Gold architecture**.

This repository demonstrates how raw video streaming–related data can be ingested, transformed, and prepared for analytics using a layered data engineering approach implemented with **Jupyter Notebooks**.

---

## 🚀 Project Overview

The project showcases a typical modern data pipeline design:

* **Bronze Layer** – Raw data ingestion
* **Silver Layer** – Data cleaning and transformation
* **Gold Layer** – Aggregated, analytics-ready datasets
* **Utilities** – Logging, parameter handling, and testing

This structure is commonly used in data lakes and data warehouse architectures.

---

## 📁 Repository Structure

```
video_streamming/
├── bronze(data_ingestion).ipynb   # Raw data ingestion
├── silver_layer.ipynb             # Data cleaning and transformations
├── gold layear.ipynb              # Final aggregated datasets
├── log.ipynb                      # Logging and monitoring utilities
├── param.ipynb                    # Parameter and configuration management
├── test scripts.ipynb             # Data validation and tests
└── README.md                      # Project documentation
```

---

## 🧠 Pipeline Flow

1. **Bronze – Data Ingestion**

   * Reads raw video streaming or log data
   * Performs basic validation

2. **Silver – Data Transformation**

   * Cleans and normalizes data
   * Applies business logic

3. **Gold – Analytics Layer**

   * Aggregates metrics
   * Produces BI-ready datasets

4. **Logging & Parameters**

   * Centralized configuration via `param.ipynb`
   * Execution logging via `log.ipynb`

5. **Testing**

   * Data quality and transformation checks

---

## 🛠️ Prerequisites

* Python 3.x
* Jupyter Notebook / JupyterLab

Suggested Python libraries:


```



```bash
pip install pyspark
```

---

## ▶️ How to Run

Run the notebooks in the following order:

1. `param.ipynb`
2. `bronze(data_ingestion).ipynb`
3. `silver_layer.ipynb`
4. `gold layear.ipynb`
5. `log.ipynb`
6. `test scripts.ipynb`

Ensure data paths and parameters are correctly set before execution.

---

## 📊 Outputs

* Cleaned and transformed datasets
* Aggregated analytics tables
* Logs and validation results

These outputs can be used for dashboards, reports, or further ML processing.

---

## 🚧 Future Improvements

* Add real-time streaming support
* Integrate with cloud storage (AWS / Azure / GCP)
* Add automated tests and CI/CD
* Convert notebooks into reusable Python modules

---

## 📄 License

Add a license of your choice (e.g., MIT, Apache 2.0).

---

## 🙌 Contributions

Contributions are welcome. Feel free to fork the repository and submit a pull request.
