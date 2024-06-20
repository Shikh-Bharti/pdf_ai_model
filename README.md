# Fine-Tuning a Question Answering Model with SQuAD

## Project Overview

This project demonstrates how to fine-tune a pre-trained transformer model for question answering using text extracted from PDF documents. The project utilizes the SQuAD dataset to fine-tune the model and evaluates its performance on custom text data. The primary objectives of the project are:
- To extract text from PDF documents.
- To fine-tune a pre-trained transformer model on the SQuAD dataset.
- To evaluate the model's performance on custom text extracted from PDFs.

## Install Additional Dependencies

Make sure to install pymupdf and datasets libraries:

pip install pymupdf
pip install datasets
##Usage
Extract Text from PDF
Use the get_text_from_pdf function to extract text from a PDF file:
Load and Preprocess the SQuAD Dataset

Load the SQuAD dataset and preprocess it for training:
Train the Model

Fine-tune the pre-trained model on the SQuAD dataset:
Evaluate the Model

Use the fine-tuned model to answer questions based on extracted PDF text:
Dependencies
pymupdf: For extracting text from PDF files.
datasets: For loading and handling the SQuAD dataset.
transformers: For utilizing pre-trained models and fine-tuning them.
torch: For training the model.
tqdm: For displaying progress bars during training.
Install these dependencies using pip:
