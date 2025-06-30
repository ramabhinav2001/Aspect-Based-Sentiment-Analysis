# Aspect-Based-Sentiment-Analysis

## Overview

**Introduction**  
In the previous group projects, we found that Transformer encoder blocks work very well for text classification problems (e.g., extracting span text from context). Therefore, in Project 3, our team aims to test models built on Transformer encoder architecture.

The problem we focus on is Aspect-Based Sentiment Analysis (ABSA), using datasets from the SemEval ABSA benchmark:  
- 2014 Restaurant & Laptop  
- 2015 Restaurant  
- 2016 Restaurant  

ABSA is commonly divided into three tasks:
- **Aspect Extraction**: Identify aspects/features referred to in a review.
- **Opinion Term Extraction**: Find words/phrases describing the aspect.
- **Sentiment Classification**: Classify the sentiment (positive/neutral/negative) of the aspect-opinion pair.

This project implements an **ABSA pipeline** using Python and common NLP libraries.

## Features

- Preprocessing of customer reviews  
- Aspect extraction and sentiment classification  
- Use of deep learning models (e.g., BERT, DeBERTa)  
- Visualization of sentiment results  

## Technologies Used

- `pandas`, `numpy`, `matplotlib`
- `torch`, `torch.nn`, `torch.optim`
- `transformers` (BERT, DeBERTaV2)
- `datasets` from Hugging Face
- `google.colab` for data loading
- `tqdm`, `json`, `os`, `ast`

## How to Run

1. Clone this repository.
2. Install dependencies (`pip install -r requirements.txt` or manually based on imports).
3. Open the notebook in Google Colab or Jupyter.
4. Run all cells sequentially.

## License

This project is intended for academic use only.
