CLUSTERING AND DIMENSION REDUCTION IN POKÉMON DATA

========
OVERVIEW
========

This repository is dedicated to using clustering and dimension reduction techniques to help new Pokémon players identify high-attack Pokémon types. The project applies methods like K-means, PAM, and CLARA, along with SVD and PCA, to explore key Pokémon attributes.

Team: Jin Huang. Georgii Bykov, Jakub Gazda
Objectives
Clustering: Use K-means, PAM, and CLARA to find Pokémon clusters with high attack values.
Dimension Reduction: Apply SVD and PCA to determine crucial Pokémon attributes.
Methodology
Data Preprocessing: Standardize attributes like type, attack, defense, etc.
Analysis: Evaluate clustering effectiveness; perform SVD and PCA on the dataset.
Expected Outcomes
Determine the best clustering method for identifying powerful Pokémon.
List of common Pokémon types in high-attack clusters.
Insights into important Pokémon attributes for player strategy optimization.

==============================
SETUP AND RUNNING INSTRUCTIONS
==============================

1/6 PREREQUISITES

Ensure you have Python and Git installed:
Download Python from python.org
Download Git from git-scm.com

2/6 CLONE THE REPOSITORY

Clone the project to your local machine: 
git clone https://github.com/<username>/<repository>.git
cd <repository>

3/6 ENVIRONMENT SETUP

Create and activate a virtual environment:
python -m venv venv
# On Windows
.\venv\Scripts\activate
# On Unix or MacOS
source venv/bin/activate

Install required packages:
pip install -r requirements.txt

4/6 RUN JUPYTER NOTEBOOK

Start Jupyter Notebook:
jupyter notebook
Access the notebook through the browser at http://localhost:8888.

5/6 USING THE NOTEBOOK

Open the .ipynb file in the notebook interface.
Run the notebook cells by selecting them and pressing Shift + Enter.

6/6 DEACTIVATE THE ENVIRONMENT

When done, deactivate the virtual environment:

deactivate
