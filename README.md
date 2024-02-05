# DCSurveyAnalysis
Welcome to the "DCSurveyAnalysis" repository! This repository contains a detailed analysis of the data collected from a preliminary survey conducted among the members of the Wroclaw Data Community. Our goal is to provide insights into the preferences, experiences, and expectations of the members of our growing data community.

# Setting Up Projet's Environment

- [Set up the environment with Conda](./instructions/conda_setup.md)
- [Set up the environment with pip](./instructions/venv_setup.md)

# Environment and Dependency Management


## Important Notice: Update `requirements.txt` and `environment.yml` Before Committing Data

Consistency in development and production environments is crucial for the seamless operation and collaboration in any project. To maintain this consistency, it is essential to update the `requirements.txt` and `environment.yml` files before pushing any changes to the repository.

### Updating `environment.yml`

Before committing your code, ensure that the `environment.yml` file is updated to reflect the latest state of Python packages used in your project. This can be achieved by executing the following command in your terminal:

1. Activate your Conda environment: `conda activate wro-dc-survey`
2. Export the current environment: `conda env export --no-builds > environment.yml`

### Updating `requirements.txt`

1. Activate your Conda environment: `conda activate wro-dc-survey`
2. Export the current environment: `pip list --format=freeze > requirements.txt`
