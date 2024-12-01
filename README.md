# CS341NL01 Final Project

This project involves building a Question-Answering system using Hugging Face Transformers. The system processes medical text data and answers questions based on the content.

## Features
- Named Entity Recognition (NER) using BioClinicalBERT.
- Fine-tuned Question-Answering using RoBERTa-SQuAD2.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CS341NL01_Final-Project.git
2. Install dependencies:
    ```bash
    pip install -r requirements.txt

## How to Run 
1. Run the NER pipeline
   ```bash
   python scripts/ner_pipeline.py
4. rain the Question-Answering model:
   ```bash
    python notebooks/train_qa_model.ipynb

## Directory Structure
- notebooks/: Jupyter notebooks for model training and evaluation.
- scripts/: Python scripts for preprocessing and running pipelines.
- data/: Processed data and datasets.
