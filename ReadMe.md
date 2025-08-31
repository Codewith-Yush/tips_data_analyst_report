# Tips for Data Analyst Report

This repository contains a collection of tips and best practices for creating effective data analyst reports. Whether you're a beginner or an experienced analyst, these tips will help you communicate your findings clearly and effectively.

## 1. Installation by create a python virtual environment
To set up a Python virtual environment for working with data analysis reports, follow these steps:

```bash
# Create a new virtual environment
python -m venv .venv
# Activate the virtual environment in windows using gitbash
source .venv/Scripts/activate

# create a requirements.txt file and add libraries inside
# Install required packages
pip install -r requirements.txt
```
or you can install the packages individually using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly
pip install ipykernel openpyxl
```

## 2. Create a Jupyter Notebook

```bash
# create a ipynb file
mkdir scripts
cd scripts
touch 01_data_analysis.ipynb
```

### 2.1. Use of github copilot for data anlytics report

Here is the prompt no. 1:

> 1. I have df in this notebook, which is tips data.
Act as a data analyst, and write the code using python libaries pandas, numpy, seabron, matplotlib and plot, to do the basic data analytics tasks such as:
1. Data composition report
2. Data distribution report
3. Data comparison report
4. Data relationship report

> If you need to do the statistics please install stats models and scipy libraries using code cells in jupyter notebook.

> If you want to create a plot and whenever you do that, please intepret the results as I would like to submit that in a report form
Lets see what you have got, i am really looking forward to your code without bugs and best possible plots.
