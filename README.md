# README to Setup Jupyter Notebook

## 1. Prerequisites

- Ensure that **Python** is already installed on your PC/Laptop.

## 2. Setup Instructions

Follow these steps to set up the Jupyter Notebook:

### a) Create a Virtual Environment

1. Open the **Command Prompt**.
2. Run the following command to create a virtual environment:
    ```bash
    python -m venv egc143
    ```
3. Navigate to the `egc143` folder:
    ```bash
    cd egc143
    ```
4. Activate the virtual environment by running:
    - On Windows:
      ```bash
      scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source bin/activate
      ```

### b) Clone the GitHub Repository

1. Run the following command to clone the required repository:
    ```bash
    git clone git@github.com:jhchng/pynb_userdefn1.git
    ```
2. Change to the project directory:
    ```bash
    cd pynb_userdefn1
    ```

### c) Install the Required Dependencies

1. Install the required dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```

### d) Launch the Jupyter Notebook

1. Run the following command to launch the notebook:
    ```bash
    jupyter notebook python_userdef_func.ipynb
    ```

That's it! Your Jupyter Notebook should now be up and running.


"# README to setup Jupyter Notebook"

1. To setup the jupyter notebook, ensure that Python is already installed on PC/Laptop.
2. Use the following steps to clone the required files as follows:
    a) Launch command prompt
    b) python -m venv egc143
    c) cd egc143
    d) run the command "scripts\activate" in command prompt
    e) git clone git@github.com:jhchng/pynb_userdefn1.git
    f) cd pynb_userdefn1
    g) pip install -r requirements.txt
    h) Launch the notebook using the command:
            jupyter notebook python_userdef_func.ipynb
