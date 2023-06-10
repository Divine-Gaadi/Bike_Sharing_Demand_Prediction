# Predict Bike Sharing Demand with AutoGluon

## Introduction to AWS Machine Learning Final Project
This project focuses on using AWS open-source AutoML library, AutoGluon to predict the bike sharing demand using the Kaggle Bike Sharing demand dataset. AutoGluon automates machine learning tasks by training tabular dataest with multiple machine learning models with just a few lines of code.
## Overview
This project focuses on predicting bike rental demand using machine learning algorithms. The dataset, sourced from Kaggle, consists of historical bike rental data including weather conditions, time, and other relevant factors. By leveraging this dataset, I aim to develop a model that accurately forecasts the number of bikes required in a given time period, allowing bike-sharing companies to optimize their inventory and meet customer demand effectively. The predictions were uploaded on kaggle to compete in the bike sharing demand competition.



To meet specifications, the project will require at least these files:
* Jupyter notebook with code run to completion
* HTML export of the jupyter notebbook
* Markdown or PDF file of the report

Images or additional files needed to make your notebook or report complete can be also added.

## Getting Started
* Clone this template repository `git clone git@github.com:udacity/nd009t-c1-intro-to-ml-project-starter.git` into AWS Sagemaker Studio (or local development).

<img src="img/sagemaker-studio-git1.png" alt="sagemaker-studio-git1.png" width="500"/>
<img src="img/sagemaker-studio-git2.png" alt="sagemaker-studio-git2.png" width="500"/>

* Proceed with the project within the [jupyter notebook](project-template.ipynb).
* Visit the [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand) page. There you will see the overall details about the competition including overview, data, code, discussion, leaderboard, and rules. You will primarily be focused on the data and ranking sections.

### Dependencies

```
Python 3.7
MXNet 1.8
Pandas >= 1.2.4
AutoGluon 0.2.0 
```

### Installation
For this project, it is highly recommended to use Sagemaker Studio from the course provided AWS workspace. This will simplify much of the installation needed to get started.

For local development, you will need to setup a jupyter lab instance.
* Follow the [jupyter install](https://jupyter.org/install.html) link for best practices to install and start a jupyter lab instance.
* If you have a python virtual environment already installed you can just `pip` install it.
```
pip install jupyterlab
```
* There are also docker containers containing jupyter lab from [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html).

## Information on files in this repository

1. project_notebook-bike_sharing_demand.ipynb: Jupyter notebook with code

2. project_notebook-bike_sharing_demand.ipynb: HTML export of the jupyter notebbook

3. project_report.md: (Markdown file of the report) A report was generated post-submission that meticulously examines the iterations that yielded the most significant improvement in model performance, along with a thorough explanation of the reasons for their effectiveness.

## License
[License](LICENSE.txt)
