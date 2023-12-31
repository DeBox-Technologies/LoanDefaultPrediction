# LoanDefaultPrediction
This repository offers machine learning solutions for predicting loan defaults using XGBoost and Random Forest models. It focuses on enhancing model transparency and interpretability through Explainable AI techniques, addressing the needs of data scientists, stakeholders, and regulators in the financial industry.

## Acknowledgments
This project is based on the work provided by ProjectPro. I have adapted and extended their code from their tutorial "Loan Default Prediction Project using Explainable AI ML Models" for the specific purposes of this project. My modifications and extensions build upon the foundational code and concepts learned from ProjectPro's excellent resources.

# Execution Instructions

# Python version 3.10.4

To create a virtual environment and install requirements in Python 3.10.4 on different operating systems, follow the instructions below:

### For Windows:

Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.

Change the directory to the desired location for your project:

`cd C:\path\to\project`

Create a new virtual environment using the venv module:

`python -m venv myenv`

Activate the virtual environment:

`myenv\Scripts\activate`

Install the project requirements using pip:

`pip install -r requirements.txt`


### For Linux/Mac:

Open a terminal.

Change the directory to the desired location for your project:

`cd /path/to/project`

Create a new virtual environment using the venv module:

`python3 -m venv myenv`

Activate the virtual environment:

`source myenv/bin/activate`

Install the project requirements using pip:

`pip install -r requirements.txt`

These instructions assume you have Python 3.10.4 installed and added to your system's PATH variable.


## Execution Instructions if Multiple Python Versions Installed


If you have multiple Python versions installed on your system , you can use the Python Launcher to create a virtual environment with Python 3.10.4, you can specify the version using the -p or --python flag. Follow the instructions below:

### For Windows:

Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.

Change the directory to the desired location for your project:

`cd C:\path\to\project`

Create a new virtual environment using the Python Launcher:

`py -3.10 -m venv myenv`

Note: Replace myenv with your desired virtual environment name.

Activate the virtual environment:

`myenv\Scripts\activate`

Install the project requirements using pip:

`pip install -r requirements.txt`


For Linux/Mac:

Open a terminal.

Change the directory to the desired location for your project:

`cd /path/to/project`

Create a new virtual environment using the Python Launcher:

`python3.10 -m venv myenv`
Note: Replace myenv with your desired virtual environment name.

Activate the virtual environment:

`source myenv/bin/activate`
Install the project requirements using pip:

`pip install -r requirements.txt`


By specifying the version using py -3.10 or python3.10, you can ensure that the virtual environment is created using Python 3.10.4 specifically, even if you have other Python versions installed.





```
├─ engine.py
├─ Input
│  ├─ CleanedData.xlsx
│  ├─ Cleaned_SampledData.xlsx
│  ├─ Credit_Risk_Dataset.xlsx
├─ Notebooks
│  ├─ 1. Data prep and ML.ipynb
│  ├─ 2. Explainable AI.ipynb
│  └─ Source
|
├─ Output
├─ readme.md
├─ requirements.txt
└─ Source
   ├─ eda.py
   ├─ machine_learning.py
   ├─ setup.py
```


