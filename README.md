# cmp6232-ag-news-text-classification
Traditional NLP and transformer-based text classification on AG News using Bag of Words, TF-IDF, Word2Vec, DistilBERT, BERT, and FLAN-T5.

# AG News Text Classification with Traditional NLP and Transformer Models

## Project overview
This project compares traditional NLP models and transformer-based models for four-class news classification using the AG News dataset. The classes are World, Sports, Business, and Sci/Tech.

## Models included
- Bag of Words + Logistic Regression
- TF-IDF + Logistic Regression
- TF-IDF + Linear SVC
- Word2Vec + Logistic Regression
- DistilBERT
- BERT subset comparison
- FLAN-T5 zero-shot experiment

## Main result
The best classical model was TF-IDF + Linear SVC with 92.68% test accuracy.  
The best overall model was fine-tuned DistilBERT with 95.00% test accuracy and 0.95 macro F1.

## Repository structure
- `notebooks/` contains the main notebook
- `figures/` contains plots and confusion matrices
- `references/` contains source acknowledgements
- `requirements.txt` lists the dependencies needed to run the notebook

## Code provenance and acknowledgements
This project began from the CMP6232 text classification template and was extended for AG News.  
The Word2Vec section was informed by the vector semantics lab.  
The AG News preprocessing, exploratory analysis, tuning experiments, classifier comparisons, subset-based transformer comparisons, and ablation studies were added for this project.

## Dataset
This project uses the AG News dataset.

## How to run
1. Install dependencies from `requirements.txt`
2. Open the notebook in Google Colab or Jupyter
3. Mount Google Drive or update file paths
4. Run the notebook cells in order

## References
See `references/sources.md`
