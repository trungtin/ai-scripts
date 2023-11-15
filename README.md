# OpenAI Assistant Scripts
This repository contains multiple scripts to interact with the OpenAI Assistant API for various purposes.

## Pre-requisites
```
poetry install
```

Copy the `.env.example` file to `.env` and fill in the values for your OpenAI API key.

## Scripts
### 1. Assistant from PDF Files
This script takes one or more PDF files as input and creates an OpenAI assistant that can answer questions based on the content of the PDFs.

**Usage**

Run the script with the paths to the PDF files as arguments:
```python
python assistant_pdf.py example.pdf (example2.pdf) (example3.pdf) ...
```
The script will upload the PDF files to the OpenAI Assistant API, create a new assistant named "pdf_assistant", and print the URL where you can interact with the assistant.