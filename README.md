# 🌍 GHCN-D Spark Assignment (DATA420)

[![Spark](https://img.shields.io/badge/Spark-3.3.5-orange.svg)](https://spark.apache.org/)
[![Python](https://img.shields.io/badge/PySpark-API-blue)](https://spark.apache.org/docs/latest/api/python/)

This repository contains a Spark-based Jupyter notebook for analyzing the **Global Historical Climatology Network daily (GHCNd)** dataset. The work forms part of **Assignment 1** for the University of Canterbury’s *DATA420: Scalable Data Science* course.

## 📁 Dataset Overview

The GHCNd dataset is hosted on **Azure Blob Storage** and includes:

- `daily/` - Gzipped CSVs of daily weather observations (one per year)
- `stations.csv` - Station metadata
- `states.csv`, `countries.csv`, `inventory.csv` - Supporting reference files

All files are accessed using the `wasbs://` protocol.

## ⚙️ Technologies Used

- Apache Spark 3.3.5
- PySpark
- Azure Blob Storage
- HDFS commands (`hdfs dfs`)
- Jupyter Notebook
- Python 3.10+

## 🚀 Getting Started

To run this notebook:

1. Log into the **Windows server** environment provided by the course.
2. Use the **Kubernetes Dashboard** to start your Spark cluster.
3. Launch **Jupyter Lab** on the master node.
4. Open and run:
   - `process.ipynb`
   - `analysis_visualisation.ipynb`


## ⚠️ Disclaimer
This repository contains code originally provided by James Williams for educational purposes only.

**All rights reserved.**
Unauthorized use, reproduction, distribution, or modification of this code is strictly prohibited without explicit permission from the original author.
If you are a student or collaborator in **DATA420** at **University of Canterbury**, you may use this code solely for coursework as instructed.
