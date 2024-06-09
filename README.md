# Module 7: Intro to Machine Learning Project

## Jackie Ganyo

## Purpose  

In this project, you will employ machine learning.  For our course, we will limit this to simple linear regression, which is supervised learning. We will use simple linear regression to train a model using all available data and us the resulting model (a "best-fit" straight line) to make predictions.

### 1. Environment Setup

Create new Github repository with appropriate README.md and .gitignore files
Clone to your machine
Create new project environment
Activate new project environment
Manage Project requirements
  Install dependencies, freeze requirements
  Git add and commit the changes for version control

### 2. Project Start

Make sure Jupyter is installed and working in your project virtual environment. Document the process and commands you used in your README.md.

Then create, open, and start a new notebook in your root project repository folder:

Create the Notebook: In the VS Code Explorer, create a new file i.e., yourname_eda.ipynb. Ensure it has a .ipynb extension.
Verify your new notebook is open for editing. If needed, view the project files in VS Code Explorer and double-click the notebook file to open it for editing.
Add a Markdown cell at the top of your notebook with the introduction (include the title, author, date and the purpose of the project).

### 3. Import Dependencies (At the Top, After the Introduction)

Add a Python cell next with the import statements for the libraries you will use in the project. Follow conventional package import organization and alias. Import each package just once near the top of the file. Be sure you have INSTALLED any external packages (outside the Python Standard Library) into your active project virtual environment first.

Jupyter Notebook / Python cell example:

import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns

Execute the cell to ensure everything works. If you get errors on one of the statements above, the most common issue is that package has not been installed into the active project virtual environment. When you find you need a new package, first install it into the active project virtual environment and then import it near the top of your Python or Notebook file.
