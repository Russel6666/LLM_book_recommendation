# LLM_book_recommendation

This project explores a dataset of over 7,000 books, focusing on cleaning, analyzing, and preparing rich book metadata and descriptions for natural language processing (NLP) applications. The final result enables semantic search using LangChain, OpenAI embeddings, and ChromaDB.

## Overview of project

The goals of this project are to:

- Perform exploratory data analysis (EDA) on book metadata
- Engineer meaningful features to enhance interpretability
- Clean and filter the dataset for quality
- Prepare descriptions for semantic embedding
- Create a vector-based search system using LangChain

## Data Info:

- Source: [Kaggle - 7k Books with Metadata](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata)
- Format: CSV
- Key columns: `title`, `subtitle`, `description`, `published_year`, `num_pages`, `average_rating`, `isbn13`