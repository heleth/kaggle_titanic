analysis for Kaggle titanic competition

# What is this
playground for Kaggle titanic competition


# Usage
* Change data to feather format
  ```
  python scripts/convert_to_feather.py
  ```

* Create features
  ```
  python features/create.py
  ```

* Run LightGBM
  ```
  python run.py
  ```

* flake8
  ```
  flake8 .
  ```


# Notes
* sample information (information of cloned repository)
  - SAMPLE_README.md

## Structures (copied from SAMPLE_README.md)
```
.
├── configs
│   └── default.json
├── data
│   ├── input
│   │   ├── sample_submission.csv
│   │   ├── train.csv
│   │   └── test.csv
│   └── output
├── features
│   ├── __init__.py
│   ├── base.py
│   └── create.py
├── logs
│   └── logger.py
├── models
│   └── lgbm.py
├── notebooks
│   └── eda.ipynb
├── scripts
│   └── convert_to_feather.py
├── utils
│   └── __init__.py
├── .gitignore
├── .pylintrc
├── LICENSE
├── README.md
├── run.py
└── tox.ini
```


# History
20190628
  git cloned sample repository
