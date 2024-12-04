# Helpmate-AI
1.	Problem Statement:
This project is focused on the insurance industry, aiming to create a highly efficient generative search system that can precisely answer questions derived from a variety of insurance policy documents. We are utilizing LlamaIndex, a data integration framework that helps organize, structure, and access private or domain-specific datasets to achieve this. LlamaIndex facilitates the connection of large language models (LLMs), like GPT-3, with specialized data sources. The tool is a Python library designed to assist in the development of data-aware applications and question-answering systems.

2.	Why Llama Index:
LlamaIndex offers seamless integration of data from various file formats, such as text documents, websites, PDFs, and structured files like CSVs. After importing the data, it generates an index that optimizes data retrieval and querying. The platform also provides a query engine, enabling users to interact through natural language to obtain relevant answers from the indexed content. LlamaIndex is well-suited for this project because it supports multiple retrieval strategies, including vector-based searches and keyword-based queries, which can ensure the most pertinent results are retrieved based on the given input.

3.	Project Goals:
The main objectives of the project are:
•	To develop a highly functional generative search system that answers questions accurately based on insurance policy documents.
•	Leverage LangChain or LlamaIndex to create this generative search solution.

4.	System Design
<br><b>RAG System Architecture</b>

<img width="452" alt="image" src="https://github.com/user-attachments/assets/864927eb-a2e2-4ae1-8c9a-7fd9f1cb3dbc">
<br><img width="452" alt="image" src="https://github.com/user-attachments/assets/12550696-70fd-4c63-86c0-b1ecf741239b">

Components:
<br>•	Data Loading
<br>•	Building query engine
<br>•	Creating a Response Pipeline
<br>•	Build a Testing Pipeline
<br>•	Optimization and fine-tuning
