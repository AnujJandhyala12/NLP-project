This project uses Natural Language Processing (NLP) to automatically detect Adverse Drug Reactions (ADR) from medical text. Both a baseline machine learning model and a transformer-based DistilBERT model are used and compared.

Project Overview:

Detect ADR-related sentences from medical text
Use ADE Corpus V2 dataset
Compare traditional ML vs. transformer models
Evaluate model accuracy, precision, recall, and F1-score
Perform error analysis for better understanding

Steps to run locally: 
Step1:

git clone https://github.com/AnujJandhyala12/NLP-Project
cd <NLP-PROJECT>


Step 2:
python -m venv venv
venv\Scripts\activate

Step 3:

pip install -r requirements.txt

Step 4:

if running in Jupyter notebook:
jupyter notebook
ADR_Transformer_Project.ipynb

Datasets used:

ADE Corpus V2
Binary classification: ADR vs Non-ADR
Contains labeled medical sentences
Split into Train / Validation / Test
https://huggingface.co/datasets/ade-benchmark-corpus/ade_corpus_v2
