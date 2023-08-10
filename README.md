# dtsa5510lo
final project for DTSA5510

<!-- ABOUT THE PROJECT -->
## About The Final Project
This project applies topic modeling, an unsupervised task, to biomedical abstracts.  Topic modeling helps us to extract the hidden topics present in these documents.

It was done for CU Boulder's DTSA5510 Introduction to Machine Learning: Unsupervised Learning.

The topic modeling methods covered include
- Latent Semantic Analysis (LSA)
- Non-negative Matrix Factorization (NMF)
- Latent Dirichlet Allocation (LDA)
- BERTopic


### Dependencies

The code was developed with Python 3.10.4 and the following libraries and versions:
- gensim==4.3.1
- numpy==1.24.4
- pandas==2.0.3
- sklearn==1.3.0
- torch==2.0.1
- transformers==4.31.0

The full environment setting can be installed through:
```
conda env create -f conda-environment.yaml
conda activate msds
```

### Data

The [data](https://www.kaggle.com/datasets/chaitanyakck/medical-text) used was downloaded from Kaggle.  The med_text_train.dat file is replicated here though technically you are supposed to log into Kaggle to download it.

### Usage

All code may be found and run in the notebook MedicalTextTopicModeling.ipynb.  The notebook assumes that the above datafile is found in the same directory in which the notebook is run.
