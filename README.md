# Photovoltaic Deployment Analysis – Campania

This project analyzes the spatial distribution of photovoltaic installations across municipalities in the Campania region (Italy).

The objective is to identify territorial patterns and municipalities with potential for photovoltaic development using statistical and machine learning models.

## Methods

The analysis includes several statistical and machine learning approaches:

- Logistic Regression
- Ridge and Lasso Regression
- Random Forest Classification
- Cluster Analysis (K-Means)

## Data

The dataset was constructed by integrating multiple public datasets related to Italian municipalities and renewable energy infrastructure.

Data sources include:

- ISTAT
- CORINE Land Cover
- Altaimpianti
- Other public territorial datasets

Raw datasets were merged in Excel to build a municipal-level dataset for the Campania region.

The final dataset used in the analysis is available in the `data` folder.

## Repository structure

photovoltaic-campania-analysis
│
├── notebook
│   └── photovoltaic_analysis.ipynb
│
├── data
│
├── docs
│   └── data_sources.md
│
└── README.md