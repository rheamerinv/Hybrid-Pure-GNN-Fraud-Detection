# Demo User Guide: Hybrid GNN-Based Fraud Detection System

## 1. Overview

This demo showcases a hybrid fraud detection system combining:

* **Graph Neural Networks (GAT)** for relational fraud patterns.
* **Symbolic AI rules** for explainability and domain-driven checks.
* **Kafka streaming** to simulate real-time financial transactions.
* **Plotly/NetworkX/Streamlit dashboards** for visualization.

The demo allows users to:

1. Run baseline GNN models.
2. Apply hybrid GNN + Symbolic rules.
3. Stream transactions in real-time via Kafka.
4. Visualize fraud detection results.

## 2. Requirements

* Python 3.10+
* Libraries: `pytorch`, `torch-geometric`, `kafka-python`, `pandas`, `plotly`, `streamlit`
* Datasets:

  * **df_augmented_paysim_copy.csv** (whihc is the paysim data subset with synthetic fraud ring data which was created and downloaded from the datapreparation.ipynb )
  **(the dataset is already in the file)**

  ##3.Run the model 

  * Model.py creates artifacts and saves them in the artifacts directory -- the demo already contains the artifacts and model.pt in the directory 'artifacts'
  * Run Kafka streaming on Mac or Windows (using Kdraft or Zookeeper) -- /opt/homebrew/opt/kafka/bin/kafka-server-start /opt/homebrew/etc/kafka/server.properties
  * In seperate Pycharm terminal run-- python kalfka_consumer.py 
  * In another terminal run-- python kalfka_prodcuer.py 
  * And another terminal run-- streamlit run fraud_dashboard.py 


  


  *
