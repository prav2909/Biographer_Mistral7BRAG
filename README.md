# Personal Biographer Chatbot with Mistral 7B

This repository contains an implementation of a Retrieval-Augmented Generation (RAG) chatbot using the Mistral 7B language model from Hugging Face. The chatbot is designed to answer questions about a specific individual, using data provided in the `data` folder.

## Repository Location

`git@github.com:prav2909/Biographer_Mistral7BRAG.git`

## Contents

* `RAG_on_Mistral_7B.ipynb`: A Jupyter Notebook that walks through the process of:
    * Loading and processing data from the `data` folder.
    * Creating a vector store corpus using LlamaIndex.
    * Setting up a RAG pipeline with Mistral 7B.
    * Interacting with the chatbot to ask questions.
* `data/`: A directory containing the data files used to build the chatbot's knowledge base.
* `requirements.txt`: A file listing all the Python dependencies required to run the notebook.

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone git@github.com:prav2909/Biographer_Mistral7BRAG.git
    cd Biographer_Mistral7BRAG
    ```

2.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Jupyter Notebook:**

    * Open `RAG_on_Mistral_7B.ipynb` using Jupyter Notebook or JupyterLab.
    * Follow the instructions within the notebook to load your data, build the index, and interact with the chatbot.

4.  **Data Preparation:**

    * Place your personal data (e.g., text files, PDFs) into the `data` folder.
    * Ensure that the data is structured in a way that allows the chatbot to understand and answer questions about you.

## Key Technologies

* **Mistral 7B:** A powerful language model from Hugging Face.
* **LlamaIndex:** A library for building LLM data frameworks.
* **RAG (Retrieval-Augmented Generation):** A technique for improving LLM responses by retrieving relevant information from external data sources.

## Usage

Modify the data in the `data` folder to personalize the chatbot with your own information. Follow the steps in the notebook to interact with the chatbot and explore its capabilities.