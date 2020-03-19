## Course Content
### Introduction
### Machine Learning
1. Supervised Learning, 
2. Unsupervised Learning
### Natural Language Processing
1. Regular Expressions, 
2. Tokenization, 
3. Character Encoding, 
4. Part-of-Speech Tagging, 
5. Chunking, 
6. Stemming and Lemmatization, 
7. Parsing, 
8. Named Entity Recognition, 
9. Topic Segmentation
### Introduction to Deep Learning for NLP
1. Sequence models, 
2. Embeddings, 
3. BERT models

## Practical Lab setup

You need a google account for using Colab for the first labs. Later, you have to use a virtual environment like conda to run the jupyter notebooks locally.

### On local: Install Miniconda

#### Download

Miniconda from https://conda.io/miniconda.html

#### install

\$bash Miniconda3-latest-Linux-x86_64.sh

### Create environment

#### Create env

\$conda create --name nlplab python=3.6

#### activate env

\$source activate nlplab

### Install packages

(nlplab)$pip3 install --upgrade pip

(nlplab)$pip3 install numpy scipy pandas matplotlib

(nlplab)$pip3 install scikit-learn

(nlplab)$pip3 install jupyter

(nlplab)\$pip install --ignore-installed --upgrade tensorflow

#### list packages

(nlplab)\$ conda list

### Jupyter notebook

#### run jupyter

(nlplab)\$ jupyter notebook

#### install package inside a jupyter notebook cell

!pip install numpy

