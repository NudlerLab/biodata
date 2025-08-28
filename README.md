# Biodata Workshop

A short workshop for my labmates on working with genomic data.

## Topics Covered

This workshop provides a hands-on introduction to bioinformatics and data analysis. The topics are structured as a series of Jupyter notebooks, covering the following areas:

*   **Foundations:**
    *   `00 - Intro.ipynb`: Workshop introduction.
    *   `01 - BASH basics.ipynb`: Essential command-line skills for data manipulation.
    *   `03 - Environments.ipynb`: Managing software dependencies and environments.
    *   `04 - Formats and tools.ipynb`: Overview of common bioinformatics file formats and tools.
    *   `06 - Git (version control).ipynb`: Introduction to version control with Git.

*   **Python for Bioinformatics:**
    *   `05 - Python.ipynb`: Fundamentals of Python programming for bioinformatics.

*   **Data Visualization:**
    *   `07.1 - Plotting (Altair).ipynb`: Creating interactive plots with Altair.
    *   `07.2 - Plotting (plotnine aka ggplot for python).ipynb`: Data visualization using plotnine, a Python implementation of ggplot2.
    *   `Visualization.ipynb`: Additional examples of data visualization.

*   **Advanced Topics:**
    *   `Stats.ipynb`: Statistical analysis in Python.
    *   `grad.ipynb`: Notebook on gradient descent.
    *   `sessions/examples/`: A directory with more advanced examples, including machine learning applications such as dimensionality reduction and clustering.

## Setup

### Environment Setup

This project uses `uv` for environment and dependency management.

1.  **Create a virtual environment:**
    ```bash
    uv venv
    ```

2.  **Activate the virtual environment:**
    ```bash
    source .venv/bin/activate
    ```

### Dependencies

1.  **Install the required dependencies:**
    ```bash
    uv pip install pandas numpy ggplot jupyterlab altair
    ```

## Usage

After setting up the environment and installing the dependencies, you can start the workshop by running JupyterLab:

```bash
jupyter lab
```

This will open a new tab in your web browser with the JupyterLab interface. From there, you can navigate to the `sessions` directory and open the notebooks to begin the workshop.