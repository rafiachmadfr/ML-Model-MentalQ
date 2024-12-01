# ML-Model-MentalQ
 
# Project README

## Description
This project involves the preprocessing, analysis, and training of a model on text data. The data consists of statements in different statuses, and we perform multiple stages of data cleaning, transformation, and analysis before training a machine learning model.

## Requirements
To run this project, you will need to install the following Python libraries:

- pandas
- matplotlib
- numpy
- random
- stanza
- re
- nltk
- h5py
- pickle
- tensorflow
- gensim
- scikit-learn
- tqdm
- Sastrawi
- wordcloud

You can install them using pip:

```bash
pip install pandas matplotlib numpy stanza nltk h5py pickle tensorflow gensim scikit-learn tqdm Sastrawi wordcloud

Project Structure

.
├── data/
│   ├── data_raw.csv                 # Raw dataset
│   ├── data_hasil_translate_30k.csv # Translated dataset
│   ├── data_hasil_EDA.csv           # Dataset after exploratory data analysis
│   └── data_hasil_prepos.csv        # Preprocessed dataset
├── model_word2vec/
│   ├── word2vec_model_MentalQ.model # Word2Vec model file
│   └── word2vec_model_MentalQ.h5    # Word2Vec model saved in HDF5 format
├── data/
│   └── word_index.pkl              # Pickle file with word index
└── script.py                        # Main script
