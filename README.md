This repo holds the code for the DH team participating in the TREC 2023 Product Ranking Challenge.

#### Team members:
Roman Grebennikov (@RomanGrebennikovDH)

Michel Oleynik ()

Gustavo Salazar (@gustavosalazartorres)

#### TREC Challenge website
https://trec-product-search.github.io/index.html


#### Resources
* Code to use:
  - SBERT https://www.sbert.net/docs/training/overview.html
  - Pythia https://github.com/EleutherAI/pythia

#### Dataset:
1. Sentence Transformers Embedding Data https://huggingface.co/datasets/sentence-transformers/embedding-training-data
2. Sentence Transfomers Reddit Data
https://huggingface.co/datasets/sentence-transformers/reddit-title-body
3. Amazon Product Search data 
https://github.com/amazon-science/esci-data
4. Extended Amazon data
https://github.com/shuttie/esci-s

#### Initial idea:
* Train the smallest Pythia model (Pythia-70M) with Datasets 1 and 2 using SBERT library (the Pythia model is available from HuggingFace)
* Evaluate that model on ESCI
