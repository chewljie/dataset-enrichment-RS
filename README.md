# dataset-enrichment-RS

This is a Hybrid Recommender System that using the Ontology to enrich the data information of the model-based recommender system.
Item-based and user-based collaborative filtering techniques has been integrated to preprocess the data before passing into the model-based system, which is SVD in our testing model.

# Requirements
- Python 3.6 (Linux is prefered for the multiprocessing)
- Jupyter Notebook
- Neo4j 3.12 or above (with Graph Data Science Library Plugin enabled)
- Surprise 1.1 https://github.com/NicolasHug/Surprise
- Py2neo 4.3 https://pypi.org/project/py2ne

# Dataset Used
- MovieLens 100K https://grouplens.org/datasets/movielens/100k/
- Extra movie details from OMDb API (access key required) https://www.omdbapi.com/

# License
Attribution 4.0 International (CC BY 4.0)

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
