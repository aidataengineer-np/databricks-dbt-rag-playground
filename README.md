# Databricks + dbt RAG Playground

End-to-end demo of an Azure Databricks lakehouse using **dbt** for transformations and **Retrieval-Augmented Generation (RAG)** for AI-powered analytics.

## Architecture

This project showcases:

- **Azure Databricks** – compute, Delta Lake, and Unity Catalog
- **dbt** – modular data transformations and semantic layer
- **Vector storage / embeddings** – indexing business documents for RAG
- **LLM / Azure OpenAI** – question answering over your data
- **Orchestration** – notebooks / jobs to run the pipeline end-to-end

## Use Cases

- Ask natural-language questions over curated lakehouse tables
- RAG over documents (e.g. PDFs, wiki pages, knowledge base)
- Show how dbt models feed both BI and AI workloads

## Project Structure

- `dbt/` – dbt project (models, seeds, tests)
- `notebooks/` – Databricks notebooks for ingestion, embeddings, and RAG
- `configs/` – connection and environment configuration
- `app/` – (optional) simple UI or API for the RAG demo

## Getting Started

1. **Clone this repo** to your local machine or Databricks Repo.
2. **Configure dbt** to connect to your Azure Databricks workspace.
3. **Run dbt models** to build the curated Delta tables.
4. **Run the notebooks** to generate embeddings and create the vector index.
5. **Execute the RAG notebook / app** and start querying your data with AI.

## Demo Flow (for clients)

1. Walk through the lakehouse tables built with dbt.
2. Show how documents are ingested and embedded.
3. Ask real business questions and show grounded RAG answers.
4. Highlight governance (Unity Catalog), lineage (dbt), and scalability.

---

This is a sandbox project for demos and experiments – feel free to fork and extend.
