# Fake News Detection

## Introduction
The goal of this project is to build a model that can detect fake news. 
The datasets used in this project is the [LIAR dataset](https://paperswithcode.com/dataset/liar) and the [ISOT dataset](https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/).

## Data
The LIAR dataset contains 3 TSV files: train, test, and validation.
The ISOT dataset contains 2 CSV files: true and fake.

Both datasets have been preprocessed in the `preprocess_isot.ipynb` and `preprocess_liar.ipynb` files.

## Model
The model used in this project is ALBERT (A Lite BERT) which is a lightweight version of BERT. 
The version used is `ALBERT-base-v2` from HuggingFace.
