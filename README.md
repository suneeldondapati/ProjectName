# ProjectName
Project Structure

```
├── README.md          <- Project Description.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final data sets for modeling.
|   ├── raw            <- The original, immutable data dump from business.
│   └── README.md      <- Description of data recieved from business. 
│
├── docs               <- Project documents, eg: SOW.pdf etc
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's id, and a short `_` delimited description, e.g.
│                         `10-1322-initial_data_exploration.ipynb`.
│
├── references         <- Data dictionaries, research papers etc.
│
├── reports            <- Generated analysis as excel, PDF etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── environment.yml   <- The environment file for reproducing the analysis environment, e.g.
│                         generated with `conda environment_name export > environment.yml`
│
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
|   |   ├── __init__.py
│   │   └── makedataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
|   |   ├── __init__.py
│   │   └── featureengineering.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
|   |   ├── __init__.py
│   │   ├── predictmodel.py
│   │   └── trainmodel.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
|       ├── __init__.py
│       └── visualization.py
│
└── 
```
