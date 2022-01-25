# seek_job_skill_prediction

## Description

This repo contains POC for predicting skills/responsibilities/requirements from job ads.

There are two attemps from this POC. Refer to these documents for more details about the methods.

1. [Using Bert-XMLC framework to train a multi-label classifier](bert-xmlc.ipynb)
  - demonstrates how to enrich the job ads using key-phrase extraction
  - demonstrates about how create a ground-true dataset is constructed using the enrichment info
  - propose to train an extreme multi-label classifier using Bert-XMLC
2. [Using FastText framework to train a multi-label classifier](fasttext_xmlc.ipynb)
  - demonstrate how to construct the train/dev/test dataset from the ground-true dataset above
  - propose to train extreme multi-label classifier using Fasttext

## Data files for re-producible
1. Job add dataset (enrichment)
2. Fine-tuned Bert model
  - [Checkpoint model](https://drive.google.com/drive/folders/10PaeeYkG99xmbV-FUSfeFuIwSX3zYP4L?usp=sharing)
  - [Job-ad datasets for Bert-XMLC and Fasttext-XMLC](https://drive.google.com/drive/folders/171NRFweLNltq_rmN9Mb7ETPkLzs_IV7R?usp=sharing)

## Reference:
1. https://www.aclweb.org/anthology/2020.coling-main.513
2. https://github.com/WING-NUS/JD2Skills-BERT-XMLC
3. https://github.com/facebookresearch/fastText/
