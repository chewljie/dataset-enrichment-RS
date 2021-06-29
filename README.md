# dataset-enrichment-RS

This is a Hybrid Recommender System that using the Ontology to enrich the data information of the model-based recommender system.
Item-based and user-based collaborative filtering techniques has been integrated to preprocess the data before passing into the model-based system, which is SVD in our testing model.

# Requirements
- Python 3.6 (Linux is prefered for the multiprocessing)
- Neo4j 3.12 or above (with Graph Data Science Library Plugin enabled)
- Surprise 1.1 https://github.com/NicolasHug/Surprise
- Py2neo 4.3 https://pypi.org/project/py2ne

# Dataset Used
- MovieLens 100K https://grouplens.org/datasets/movielens/100k/
- Extra movie details from OMDb API (access key required) https://www.omdbapi.com/

# License
Apache-2.0 License
