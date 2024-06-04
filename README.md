Overview
This repository provides a comprehensive guide for building a Retrieval-Augmented Generation (RAG) system using Gemma, MongoDB, and various open-source models from Hugging Face. The system leverages the latest advancements in NLP to enrich MongoDB with the ability to perform semantic search on large datasets.

Key Features
Data Sourcing and Preparation: Utilizes the AIatMongoDB/embedded_movies dataset.
Embedding Generation: Embeds movie plots using the gte-large model from Hugging Face.
Database Setup: Configuration and connection setup for MongoDB, including creation of vector search indexes.
Data Ingestion: Efficiently stores embeddings and metadata in MongoDB.
Query Processing: Implements vector searches to find relevant documents based on user queries.

Usage
Data Preparation: Clean and prepare data for embedding.
Embedding: Generate embeddings using SentenceTransformer.
Database Management: Set up MongoDB Atlas, connect, and configure collections.
Data Ingestion: Insert processed data into MongoDB.
Query Execution: Perform complex semantic searches using MongoDB's vector search capabilities.
Vector Search
Vector search is enabled in MongoDB to utilize cosine similarity for fetching documents similar to the query embedding, making the search process both efficient and relevant.

