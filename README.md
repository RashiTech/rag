# Retrieval-Augmented Generation

## Data pipeline for RAG system

### Key-points

Ecommerce review data in csv format with both structured and unstructured data.

Data uploaded to postgresql with proper indexing.

Review text vectorized using hugging face SentenceTransformers (balance of speed and accuracy).

The embeddings upserted and index created in Vector database -Pinecone  (fully managed, cloud based and highly scalable).

Finally matching data with the query retrieved from index and final response generated using google/flan-t5 model (Retrieval Augmented Generation).
