# DCSurveyAnalysis
Welcome to the "DCSurveyAnalysis" repository! This repository contains a detailed analysis of the data collected from a preliminary survey conducted among the members of the Wroclaw Data Community. Our goal is to provide insights into the preferences, experiences, and expectations of the members of our growing data community.

## Setting Up the Conda Environment

Follow these steps to create a Conda environment based on the `environment.yml` file:

1. Install [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) if you haven't already.

2. Open a terminal.

3. Navigate to the directory that contains the `environment.yml` file.

    ```bash
    cd /path/to/directory
    ```

4. Create the Conda environment from the `environment.yml` file:

    ```bash
    conda env create -f environment.yml
    ```

5. Activate the new environment:

    ```bash
    conda activate myenv
    ```

Replace `myenv` with the name of the environment specified in the `environment.yml` file.

6. You're now ready to use the environment!

## Setting Up the Python Environment with venv

Follow these steps to create a Python environment based on the `requirements.txt` file:

1. Install [Python 3.8.18](https://www.python.org/downloads/release/python-3818/) if you haven't already.

2. Install [pip](https://pip.pypa.io/en/stable/installation/) if you haven't already.

3. Open a terminal.

4. Navigate to the directory that contains the `requirements.txt` file.

    ```bash
    cd /path/to/directory
    ```

5. Create a new virtual environment:

    ```bash
    python3.8 -m venv env
    ```

6. Activate the new environment:

    - On Unix or MacOS, run:

        ```bash
        source env/bin/activate
        ```

    - On Windows, run:

        ```bash
        .\env\Scripts\activate
        ```

7. Install the required packages from the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

8. You're now ready to use the environment!

