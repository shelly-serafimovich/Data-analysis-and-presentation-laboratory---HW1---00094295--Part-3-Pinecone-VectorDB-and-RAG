# Data analysis and presentation laboratory 00094295 - HW1 -Part 3 Pinecone-VectorDB-and-RAG
<div align="center">
    <img src="https://miro.medium.com/v2/resize:fit:1400/1*J7vyY3EjY46AlduMvr9FbQ.png" alt="Example Diagram" width="500">
</div>
 ## Overview
This repository contains a Jupyter Notebook titled "Lab_HW1_O3" which demonstrates the implementation and usage of a RAG (Retrieval-Augmented Generation) pipeline. The notebook covers the integration of various components such as an embedding model, a vector database, and a large language model (LLM) to effectively retrieve and generate answers to user queries.

## Table of Contents
- **Introduction**
- **Notebook Structure**
- **Results**
- **Contributing** 

## Introduction
In this notebook, we explore the RAG (Retrieval-Augmented Generation) pipeline, which combines the strengths of retrieval-based and generation-based models. The pipeline consists of three main components:

- *An embedding model for generating vector representations of text.*
- *A vector database to store and retrieve these embeddings.*
- *A large language model (LLM) to generate responses based on the retrieved information*.
- *We utilize the sentence-transformer model for embeddings, Pinecone for the vector database, and Cohere's chat API for the LLM.*

## Notebook Structure
The notebook is organized into the following sections:

1. Imports: Importing the necessary libraries and dependencies.
2. RAG Pipeline Introduction: Explanation of the RAG pipeline and its components.
3. Embedding Model: Loading the dataset and generating embeddings using a sentence-transformer model.
4. Vector Database: Using Pinecone's vector database to store and manage embeddings.
5. Large Language Model (LLM): Utilizing Cohere's chat API to generate responses based on the retrieved vectors.
6. Example Queries: Running example queries to demonstrate the pipeline in action.

## Results
The notebook provides a comprehensive demonstration of the RAG pipeline, showcasing its ability to efficiently retrieve and generate accurate responses to user queries. Below are some example queries:

- Query: "Who are the Greek 200 meter sprinters who retired from the Olympic Games in Athens?"
- Query: "In a friendly soccer match between Germany and Cameroon, what was the result of the match?"
- Query: "In the 2005-2006 season, the Cleveland Cavaliers rejected the contract of the player Dajuan Wagner, who became a free agent, what was the amount of the contract?"


## Contributing
We welcome contributions to enhance this project. 
