# Thesis Project: Exploring the Colombian Constitutional Jurisprudence through Bibliometric Analysis and Large Language Models: An Application in Legal Research

***Authors:*** Ana Maria Giraldo Vargas @[amgiraldov](https://github.com/amgiraldov), Sonia Rocio Socadagui Casas @[soniasocadagui](https://github.com/soniasocadagui).

***Supervisor:*** Prof. Dr. Seppe vanden Broucke ([profile](http://www.seppe.net/)), assistant professor at the Department of Business Informatics at UGent (Belgium), and lecturer at KU Leuven (Belgium).

## Description
This research aims to provide an innovative tool to the Colombian judiciary that supports semantic searches of jurisprudence using machine learning techniques to increase, on the one hand, the efficiency of solving legal issues and, on the other hand, to produce effective and fair rule decisions. In addition, this project would supply a measure of similarity between court documents taking into account the meaning of the topics, allowing the identification of texts that deal with the same subject matter to facilitate the construction of jurisprudential lines.

In the Colombian Judicial branch, this field, known as Legal Tech, has been approached recently, meaning there is much room for research. In addition, the solution we propose is not only attractive to the Constitutional Court, citizens, or jurisprudence’s users, but it has the potential of applicability in different legal organizations to present efficient and effective actions for protecting rights using the appropriate jurisprudential line

## Link
The document can be consulted at the following link: [Thesis Project](https://es.overleaf.com/1326268636wfdddrsxnmhs).

## Directory explanation

```
Thesis Project
├── code: Contains the Jupyter notebooks used
│   ├── 00_PreparingData.ipynb
│   ├── 01_EDA.ipynb
│   └── 02_ExtractJurisprudence.ipynb
│   ├── 03_PreprocessingText.ipynb
│   └── 04_Citation_standard.ipynb
├── data: Contains the datasets downloaded to develop the project
│   ├── ...
│   ├── ...
│   ├── ...
│   ├── ...
│   ├── ...
│   └── ...
├── img: Contains the KU Leuven logo
├── models: Contains the models created to do the ontological search
│   ├── ...
│   ├── ...
│   ├── ...
│   ├── ...
│   └── ...
└── output: Contains the processed data, and the results obtained from the NLP analysis 
└── requirements.txt: Contains all the packages used in the project

```

## Instructions to run this repository's code

1. Install [MongoDB](https://www.mongodb.com/docs/manual/installation/).
2. Clone the repository.
```
git clone -b main https://github.com/amgiraldov/thesisKULeuven.git
```
3. Create a new virtual environment with Python 3.8.15 version.
```
pyenv virtualenv 3.8.15 <name>
```
4. Activate the environment.
```
pyenv activate <name>
```
5. Install the `requirements.txt` file into the virtual environment.
```
pip install -r requirements.txt
```
