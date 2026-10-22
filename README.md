# Real-Time Tracking of Misinformation Spread Waves Using Directed Graph Feature Extraction

## Project Overview
This Data Science project analyzes social-media conversation cascades using directed graph features. It explores how information propagates through reply networks and uses historical replay to visualize spread patterns over time.

## Objectives
- Construct directed graphs from conversation cascades.
- Extract graph features such as degree, PageRank, density, and cascade size.
- Analyze propagation waves and cumulative spread.
- Train and evaluate a Random Forest classifier using available dataset labels.
- Visualize graph structure and spread patterns.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- NetworkX
- Matplotlib, Seaborn, and Plotly
- Scikit-learn
- PHEME Misinformation Graphs dataset

## Project Workflow
1. Dataset loading and inspection
2. Graph feature extraction
3. Exploratory data analysis
4. Historical or simulated spread replay
5. Spread-wave visualization
6. Random Forest classification and evaluation
7. Exporting analysis results

## Dataset
PHEME Misinformation Graphs: https://huggingface.co/datasets/NunoBatista/PHEME-Misinformation-Graphs

The notebook downloads the dataset when required. Do not assume that all labels represent verified true or false claims.

## Execution
Open `Misinformation_Spread_Analysis.ipynb` in Google Colab and run the cells in order.

## Limitations
Historical replay is not live social-media monitoring. If timestamps are unavailable, synthetic timestamps may be used for demonstration and must not be interpreted as observed historical events. Classification performance depends on valid labels and the dataset's limitations.

## Outputs
The `outputs` folder contains generated graph features, replay events, spread-wave analysis, feature importance, and model predictions where available.

## Author
Add your name, department, and institution here.
