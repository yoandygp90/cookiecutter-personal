# cookiecutter-personal
Custom template for personal purposes.

### Requirements 📋
- anaconda >= 4.x
- git >= 2.x
- cookiecutter python package >= 1.4.0: this can be installed using _pip_ o _conda_

```
pip install cookiecutter
```
o
```
conda install -c conda-forge cookiecutter
```
### Create a new project 🔧
_In the directory where you want to save your generated project:_

```
cookiecutter https://github.com/yoandygp90/cookiecutter-personal --checkout branch_name
```
### Directories structure and resulting files:
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
