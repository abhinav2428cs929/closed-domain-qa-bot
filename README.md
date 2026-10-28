
# Closed-Domain Technical Documentation QA Bot

## Project Overview
A question-answering system for technical documentation using TF-IDF passage retrieval and a pretrained RoBERTa extractive QA model.

## Technologies
- Python
- Hugging Face Transformers
- RoBERTa
- Scikit-learn
- Jupyter Notebook / Google Colab
- Gradio

## Workflow
1. Prepare technical text and split it into passages.
2. Retrieve a relevant passage using TF-IDF.
3. Extract an answer using RoBERTa.
4. Evaluate with Exact Match and token-level F1.
5. Visualize preliminary results.

## How to Run
1. Open `projectgeni.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Install any required packages if prompted.

## Preliminary Results
- Exact Match: 25%
- Mean token F1: approximately 60.9%
- Validation loss: approximately 0.7168

These are preliminary results from a small evaluation and fine-tuning experiment, not a robust benchmark.

## Limitations
- Evaluation used only four manually prepared examples.
- Fine-tuning used a small SQuAD 2.0 subset.
- End-to-end PDF ingestion is not yet implemented.

## Team Members
- Abhinav Verma — 20240110010010
- Anirudh Vashisth — 20240110010046
