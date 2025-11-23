# LLM-as-a-Judge Experiments

This repository contains experiments using Large Language Models (LLMs) as judges for evaluating RAG (Retrieval-Augmented Generation) systems.

## Experiments

- **Experiment 1**: Baseline evaluation using Azure OpenAI.
- **Experiment 2**: Enhanced evaluation with RAG, using `sentence-transformers` and `faiss` for retrieval.

## Setup

1.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Environment Configuration**:
    Create a `.env` file in the root directory with the following variables:
    ```env
    AZURE_OPENAI_API_KEY=your_api_key
    ENDPOINT_URL=your_endpoint_url
    DEPLOYMENT_NAME=gpt-4o
    DEPLOYMENT_NAME_EMBEDDING=text-embedding-3-large
    OPENAI_API_VERSION=2024-05-01-preview
    ```

## Usage

Run the notebooks using Jupyter:

```bash
jupyter notebook
```

Open `Experiment1.ipynb` or `Experiment2.ipynb` to run the experiments.
