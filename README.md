# Finding-Donors
In this project, I will employ several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. 
I will then choose the best candidate algorithm from preliminary results and further optimize this algorithm to best model the data. 
My goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. 
This sort of task can arise in a non-profit setting, where organizations survive on donations. 
Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. 
While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will see) infer this value from other publically available features.
# Open the Notebook
First of all you need to have jupyter notebook installed.
You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).
The documentation for advanced usage of Jupyter notebook can be found
[here](https://jupyter-notebook.readthedocs.io/en/latest/).

For a local installation, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    $ pip install notebook

Then you can open the notebook with the following command:

    $ jupyter notebook
Finally you have to choose 'finding_donors.ipynb'.

Alternatively you can open up 'report.html' with your favourite browser. 
# Dataset
The dataset for this project originates from the UCI Machine Learning Repository. 
The datset was donated by Ron Kohavi and Barry Becker, after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid". 
You can find the article by Ron Kohavi online. 
The data we investigate here consists of small changes to the original dataset, such as removing the 'fnlwgt' feature and records with missing or ill-formatted entries.
# Authors
This is the first project of the Udacity Machine Learning Nanodegree. 
The template of the notebook was given, but most of the code and the answers were written by myself. 
