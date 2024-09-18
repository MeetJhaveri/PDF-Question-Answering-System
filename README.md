## RAG Application: PDF Question-Answering Using Llama2

This project demonstrates a Retrieval-Augmented Generation (RAG) application that utilizes open-source models to answer questions based on the content of PDF documents. The application leverages Llama2, an advanced language model, to provide accurate and context-aware answers to user queries.

## Introduction:

The PDF Question-Answering RAG application is designed to enhance the efficiency of information retrieval from PDF documents by combining the strengths of retrieval-based methods and generative models. This project focuses on building a system that can answer questions directly from the content of PDFs using the Llama2 model, which is known for its state-of-the-art performance in understanding and generating natural language.

## Features:

Question-Answering from PDFs: Extracts and processes text from PDF documents to answer user queries.

Llama2 Integration: Utilizes the Llama2 model for generating accurate and context-relevant responses.

Open-Source and Modular: Built using open-source tools and models, making it easily extensible and customizable.

## Architecture:

The system employs a Retrieval-Augmented Generation (RAG) architecture:

- **Retrieval:** Relevant text passages are extracted from the PDF document based on the user's query.

- **Generation:** The Llama2 model generates a response based on the retrieved text, ensuring the answer is contextually accurate.

## Technologies Used:

Python: Core programming language used for development.

Llama2: Language model for generating natural language answers.

PyPDF2: Python library for extracting text from PDFs.
