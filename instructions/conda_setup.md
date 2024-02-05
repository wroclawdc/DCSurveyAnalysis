
# Setting Up the Conda Environment

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