# Semantic Search with Sentence Transformers

##  Objective
Implement a mini semantic search engine using `sentence-transformers`.  
Given a user query, return the most relevant passage from a small corpus.

##  Setup
- Google Colab (preferred for easy setup)
- Python 3.10+
- Install required libraries:
  ```bash
  pip install sentence-transformers scikit-learn pandas
 Steps Implemented
Created a small dataset of text passages (Python + Big Data analytics).

Loaded the all-MiniLM-L6-v2 model from sentence-transformers.

Encoded all passages into dense embeddings.

Encoded a user query into the same embedding space.

Computed cosine similarity between query and passages.

Returned the passage with the highest similarity score.

 Example Query
Query: What tools does Python offer for big data?

Top Match:
Python has libraries like PySpark and Dask for large-scale data analysis.

 Learnings
Embeddings capture semantic meaning, not just keywords.

Cosine similarity is effective for comparing embeddings.

This approach is scalable (later can be extended to vector databases like Pinecone or FAISS).

 Files
semantic_search.ipynb: Colab notebook with implementation.

README.md: This file.
