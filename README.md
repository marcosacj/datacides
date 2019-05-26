# A Data Science Project

## Authorship

Marcos A. Cavalcanti Junior

marcos.acj@outlook.com

## Introduction

This project is an study about Homicides and Femicides in Brazil, involving data visualization in maps.

The data used in this project is from the [Brazilian Yearbook on Public Security 2018](http://www.forumseguranca.org.br/publicacoes/anuario-brasileiro-de-seguranca-publica-2018/).

## Project Structure

This is the folders hierarchy:

```text
root
├── csv
│   ├── estupro-por-capital.csv
│   ├── estupros-por-uf.csv
│   ├── homicidios-por-capital.csv
│   ├── homicidios-por-uf.csv
│   ├── homi-feminicidios-por-uf.csv
│   └── lesao-corporal-por-uf.csv
├── notebook
│   ├── 2019-05-20-macj-initial-exploration-cleaning.ipynb
│   └── 2019-05-20-macj-preparation.ipynb
├── src
│   ├── ANUARIO_12_vfinal_22fev19.xlsx
│   └── dados.ods
├── DEV.md
└── README.md

```

The `src` folder contains spreadsheets from the Brazilian Yearbook and other spreadsheets made to generate the datasets.

The `notebook` folder contains the notebooks created during the development of the project.

The `csv` folder contains the datasets in CSV format generated from the Brazilian Yearbook.

## Running

The notebooks are developed to run both on Jupyter and Google Colaboratory (Colab) without effort. Just open and run them.

A function is designed to read a local CSV file, by its name or its path, or a remote one, by its URL. This function returns a pandas DataFrame.

This way, a notebook can be runned on Jupyter, reading the local file, or on Colab, reading the uploaded or remote file.

To run on Jupyter, just type `jupyter-notebook` on terminal from root directory.

To run on Colab, just upload the project folder (or the notebook itself) to Google Drive. Optionally, upload the datasets.
