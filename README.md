Hackathon IA - Isep - Sujet Environnement
==============================

Vous trouverrez ici un boilerplate (template) pour le sujet Environnement proposé par l'AFD et l'UNEP lors du Hackathon IA organisé à l'Isep de 13 au 15 mai 2022.

Ressources
------------

| Fichier | Description |
| --- | ----------- |
| data/raw/* | Données fournis par l'AFD et le PNUE |
| Note explicative Prospecteur ODD.pdf | Une note descriptive du Prospecteur ODD développé par l’AFD |
| data/external/* | Un corpus de descriptions de projets de la Banque Mondiale. Ces projets ont été sélectionnés pour leur pertinence au regard des ODD 12,15 et 16. Ils peuvent permettre aux équipes les plus avancées de tester leur modèle |

Liens utiles
------------
> Ce document recense un ensemble de sites internet relatifs aux ODD. Les participant.e.s sont susceptibles d’y trouver des informations utiles pour mieux comprendre l’Agenda 2030, constituer une base d’apprentissage, tester les performances de leur modèle etc.
### Exemples d’outils similaires au SDG Meter / ODD Prospecteur
- <p><small><a target="_blank" href="https://osdg.ai/">OSDG</a> (Programme des Nations Unies pour le Développement)</small></p>
- <p><small><a target="_blank" href="https://knowsdgs.jrc.ec.europa.eu/sdgmapper">SDG Mapper</a> (Commission Européenne)</small></p>
- <p><small><a target="_blank" href="https://linkedsdg.officialstatistics.org/#/">Linked SDGs</a> (UN DESA)</small></p>

### Ressources relatives aux ODD
- <p><small>UN DESA SDG description: <a target="_blank" href="https://sdgs.un.org/goals">THE 17 GOALS | Sustainable Development (un.org)</a></small></p>
- <p><small>UNBIS Thesaurus: <a target="_blank" href="http://metadata.un.org/thesaurus/categories?lang=en">Home | UNBIS Thesaurus </a></small></p>
- <p><small><a target="_blank" href="https://unstats.un.org/SDGAPI/swagger/">UN SDGs API</a></small></p>
- <p><small><a target="_blank" href="http://sdg.iisd.org/">SDG Knowledge Hub | Daily SDG News | IISD</a></small></p>

Comment utiliser ce template ?
------------
```shell
# Git
git clone https://github.com/Garage-ISEP/hackathon-ia-developpement-durable
# GitHub CLI
gh repo create votre-repo -p Garage-ISEP/hackathon-ia-developpement-durable
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
