# Google Analytics 360 EDA

A CRISP-DM process for analyzing data

---

## Table of Contents

- [Instalation](#installation)
- [Project Motivation](#project_motivation)
- [File Description](#file_description)
- [Results](#results)
- [Licensing, Authors, Acknowledgements](#licensing_authors_acknowledgements)


## Instalation<a name="installation"></a>

1. Install necessary libraries using Anaconda
    - `conda env create -f environment.yml`

2. Activate the Envirnoment
    - `conda activate EDA`

2. Create a Google Cloud Project
    - Great instructions can be found [here](https://cloud.google.com/getting-started/) 

3. Create BigQuery Service-account Credentials (key file) and save the file this directory. 
    - https://cloud.google.com/bigquery/docs/authentication/service-account-file
    - For more information about authorization with Service Credentials, check out the documentation [here](https://google-auth.readthedocs.io/en/latest/user-guide.html)

4. Replace `PROJECT_ID` and `CREDENTIALS` variables in the first code block with the name of your project and the path to your key file. 

For further information about the dataset and how to access it, please visit Google [BigQuery Sample Dataset](https://support.google.com/analytics/answer/7586738?hl=en)


## Project Motivation<a name="project_motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

How other developers suggested breaking into the field (what education to pursue)?
What factors about an individual contributed to salary?
How bias played a role in the suggestions of developers for how to break into the field?
What was the state of bootcamps for assisting individuals with breaking into developer roles?
How were bootcamps assisting with increasing diversity in tech careers?
The full set of files related to this course are owned by Udacity, so they are not publicly available here. However, you can see pieces of the analysis here. This README also serves as a template for students to follow in creating their own project README files.

## File Description<a name="file_description"></a>

There file in this repository, `google_analytics_ecommerce_data.ipynb`, is a Jupyter Notebook which performs the basic Exploratory Data Analysis and creates visualizations with Plotly in the notebook. These visuals do not render in the Github viewer, but can be recreated locally inside a browser or iPykernel capable editor, such as vscode. 

## Results<a name="results"></a>

The main findings of the code can be found in the Medium post available [here](https://derrickjameslewis.medium.com/are-targeted-ads-less-effective-for-apple-users-c40bb445364d).

## Licensing, Authors, Acknowledgements<a name="licensing_authors_acknowledgements"></a>

Data for this project is publicly available from Google Cloud. You can find the Licensing for the data and other descriptive information at the link available [here](https://support.google.com/analytics/answer/7586738?hl=en). Otherwise, feel free to use the code here as you would like!

