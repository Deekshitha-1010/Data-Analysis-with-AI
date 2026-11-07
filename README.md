# Latvia IMF Financial Analysis Using Local LLMs

## Project Overview

This project analyses Latvia's 2024 IMF Country Report (No. 24/284) using Python and local Large Language Models. The aim is to extract financial indicators, summarise economic information, identify financial risks and create a four-panel dashboard.


## Models Used

- **Qwen2.5-3B-Instruct:** Financial data extraction, summarisation and question answering.
- **Phi-3.5-mini-instruct:** Evaluation of generated summaries, financial indicators and RAG answers.
- **BAAI/bge-small-en-v1.5:** Sentence embeddings for document retrieval.
- **FAISS:** Vector indexing and retrieval of relevant IMF report passages.

## Project Tasks

1. PDF text extraction, cleaning and token-aware chunking.
2. Executive summary and section summarisation.
3. Financial indicator extraction into JSON.
4. Analysis of seven financial stability themes.
5. Identification of economic strengths and vulnerabilities.
6. FAISS-based Retrieval-Augmented Generation (RAG).
7. LLM evaluation and financial data verification.
8. Four-panel financial dashboard at 300 DPI.

## Tools

Python, Google Colab, PyPDF, Transformers, Sentence Transformers, FAISS, Pandas, NumPy and Matplotlib.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Select a T4 GPU runtime.
3. Run all cells in order.
4. Upload the Latvia IMF PDF when prompted.
5. Review the generated results, dashboard and validation outputs.


