# Data Analysis

## JupyterLab

- JupyterLab is a next-generation web-based user interface for Project Jupyter.
- Code Consoles provide transient scratchpads for running code interactively, with full support for rich output.
- Kernel-backed documents enable code in any text file (Markdown, Python, R, LaTeX, etc.) to be run interactively in any Jupyter kernel.
- Notebook cell outputs can be mirrored into their own tab, side by side with the notebook, enabling simple dashboards with interactive controls backed by a kernel.
- JupyterLab can be installed using `conda`, `mamba`, `pip`, `pipenv` or `docker`.

## Data Analysis with Python

- `NumPy` is a commonly used Python data analysis package.
- We can create a NumPy array using the `numpy.array` function. If we pass in a list of lists, it will automatically create a `NumPy` array with the same number of rows and columns. 
- header rows contain strings
- the shape property will tell us how many rows and columns are in our data structure
- You can create an array where each element is a random number using `numpy.random.rand.`
- It’s possible to use `NumPy` to directly read csv or other files into arrays.
-  We can use `numpy.vstack` to vertically stack multiple arrays.

### Resources

- https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html 
- https://www.dataquest.io/blog/numpy-tutorial-python/ 
