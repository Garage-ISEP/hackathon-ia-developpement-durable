Hackathon IA - Isep - Sujet Environnement
==============================

Vous trouverrez ici un boilerplate (template) pour le sujet Environnement proposé par l'AFD et l'UNEP lors du Hackathon IA organisé à l'Isep de 13 au 15 mai 2022.

```diff
+ Les données fournies par les sponsors du sujet se trouvent dans data/raw.
```

Comment utiliser ce template ?
```shell
# Git
git clone https://github.com/Garage-ISEP/hackathon-ia-environnement
# GitHub CLI
gh repo create votre-repo -p Garage-ISEP/hackathon-ia-environnement
gh repo clone votre-repo
```

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
