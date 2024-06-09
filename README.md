# Module 7: Intro to Machine Learning Project

## Jackie Ganyo

## Purpose  

In this project, you will employ machine learning.  For our course, we will limit this to simple linear regression, which is supervised learning. We will use simple linear regression to train a model using all available data and us the resulting model (a "best-fit" straight line) to make predictions.

### 1. Environment Setup

Create new Github repository with appropriate README.md and .gitignore files
Clone to your machine

``` shell
git clone site_url
```

Create new project environment

``` shell
py -m venv .venv
```

Activate new project environment

``` shell
.\.venv\Scripts\Activate
```

Manage Project requirements
  Install dependencies, freeze requirements
  Git add and commit the changes for version control

``` shell
py -m pip install "dependencies"

py -m pip freeze > requirements.txt 
```

### 2. Project Start

Make sure Jupyter is installed and working in your project virtual environment. Document the process and commands you used in your README.md.

Then create, open, and start a new notebook in your root project repository folder:

Create the Notebook: In the VS Code Explorer, create a new file i.e., yourname_eda.ipynb. Ensure it has a .ipynb extension.

Verify your new notebook is open for editing. If needed, view the project files in VS Code Explorer and double-click the notebook file to open it for editing.

Add a Markdown cell at the top of your notebook with the introduction (include the title, author, date and the purpose of the project).

### 3. Import Dependencies (At the Top, After the Introduction)

Add a Python cell next with the import statements for the libraries you will use in the project. Follow conventional package import organization and alias. Import each package just once near the top of the file. Be sure you have INSTALLED any external packages (outside the Python Standard Library) into your active project virtual environment first.

Jupyter Notebook / Python cell example:

``` shell
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
```

Execute the cell to ensure everything works. If you get errors on one of the statements above, the most common issue is that package has not been installed into the active project virtual environment. When you find you need a new package, first install it into the active project virtual environment and then import it near the top of your Python or Notebook file.

### CC 7.5:  Chart a Straight Line (Part 1)

Always

1. Open your project repository folder in VS Code.
2. Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub.

Chart a Straight Line

1. Add a Markdown heading for Part 1 - Chart a Straight Line
2. Follow the instructions from 10.16 (starting page 414).
3. Use Markdown cells to create section headings as you work.
4. Use pandas DataFrames to plot Celsius vs Fahrenheit
5. Refresh your understanding of the equation for a line (y = mx + b) and be familiar with the use of:
  a. m = the slope of the line (rise over run or delta y over delta x)
  b. b = the y-intercept of the line (where the straight line crosses the y axis).
  
Always

1. Run the whole notebook to verify. Fix any issues or warnings.
2. Git add / commit / push your changes to GitHub.
3. Optional - if you have any issues, ask your favorite AI or your team members in the associated discussion. Use screenshots and paste error messages so we can help.

### CC 7.6:  Predict Avg High Temp in NYC in January (Part 2)

Always

1. Open your project repository folder in VS Code.
2. Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub.
3. Use Linear Regression on Average High Temperatures in NYC in January.

Read these notes before you start:

1. Continue following the instructions from 10.16 (starting page 416).
2. The data is for the average high temperature in January over many years.
3. For example, in 1895, the average high temperature in January was 34.2.
4. We only care about this one series of data: the "average high temp in Jan".
5. There's a lot of stats in the title, and it has confused students. Just think of each value as "the temperature" for that year.
6. We'll use all of the data available to build a best-fit line (supervised learning).
7. We'll use the slope and intercept of the best-fit line to estimate a point out in the future.
8. Refresh your understanding of the equation for a line (y=mx +b)

Add to your notebook as you work through the process. Add a second-level Markdown for Part 2. Use third-level Markdown headings for each section listed below. Copy and paste the section heading if you like, and add a ### space before each.

#### Section 1 - Data Acquisition
1. Follow the instructions to load NY City January high temperature from a csv file into a DataFrame.
2. Recommended: Rather than nyc, name the dataframe nyc_df to reinforce the DataFrame operations.
3. Recommended: Add all imports to the top of your file, just under the Markdown Introduction. Follow conventions.

#### Section 2 - Data Inspection
1. Follow the instructions to view head and tail of the file.

#### Section 3 - Data Cleaning
1. Follow the instructions to clean the data. Improve the column names and clean up the date series. 

#### Section 4 - Descriptive Statistics
1. Set the display precision to 2 decimal places. Use 'display.precision' instead of 'precision' as shown in the text.
2. Use describe() to calculate basic descriptive statistics for the dataset. 

#### Section 5 - Build the Model
1. Use the SciPy stats module linregress function to calculate slope and intercept for the best fit line through the data.
2. Recommended: Add all imports to the top of your file, just under the Markdown Introduction. Follow conventions. 

#### Section 6 - Predict
1. Use your model to predict the "average high temp in Jan" for the year 2024 (just like they did for 2019).

#### Section 7 - Visualizations
1. Follow the instructions and use Seaborn to generate a scatter plot with a best fit line.
2. Set the axes and the y scale as directed
3. Customize your chart and notebook as you like to make your work clear and compelling. 
Always

1. Run the whole notebook to verify. Fix any issues or warnings.
2. Git add / commit / push your changes to GitHub. 
3. Optional - if you have any issues, ask your favorite AI or your team members in the associated discussion. Use screenshots and paste error messages so we can help. 