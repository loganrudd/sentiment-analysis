Spanish Tweets Sentiment Analysis
==============================

An application of traditional and deep learning models to classify Spanish 
Tweets as positive or negative in sentiment. Explores two techniques of feature
extraction using Term frequency Inverse document frequency weighting and 
Word2Vec word embeddings. Presentation slides available on prezi: 
https://prezi.com/view/jh8H32IqSm707h33i3vz/

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    └── analysis_env.yml   <- The requirements file for reproducing the analysis environment


--------

## Installation

Creat a [Conda](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html) 
environment from respective env.yml file. For example, to
recreate the analysis environment to run jupyter notebooks run:

`conda create -n <name_of_env> -f analysis_env.yml`

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
