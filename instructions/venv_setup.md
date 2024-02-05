
# Setting Up the Python Environment with venv

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