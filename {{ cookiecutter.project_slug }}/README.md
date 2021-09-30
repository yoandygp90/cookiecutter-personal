# {{ cookiecutter.project_name }} 

By ✒️: {{ cookiecutter.project_author_name }}.

Version 📌: {{ cookiecutter.project_version }}

{{ cookiecutter.project_description }}

## Prerequisites 📋

- [Anaconda](https://www.anaconda.com/download/) >=4.x
- Optional [Mamba](https://mamba.readthedocs.io/en/latest/)

## Create environment 🔧

```bash
conda env create -f environment.yml
activate {{ cookiecutter.project_slug }}
```

or 

```bash
mamba env create -f environment.yml
activate {{ cookiecutter.project_slug }}
```

## Project organization 📖
```
    {{ cookiecutter.project_slug }}
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.
```
---
Project created for personal purposes to use a default project organization