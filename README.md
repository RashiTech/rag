# Retrieval-Augmented Generation

## Data pipeline for RAG system

### Key-points

Ecommerce review data in csv format with both structured and unstructured data.

Data uploaded to postgresql with proper indexing.

![image](https://github.com/user-attachments/assets/3e2df134-b718-40c5-a13c-0e9ed7e82289)


Review text vectorized using hugging face SentenceTransformers (balance of speed and accuracy).

The embeddings upserted and index created in Vector database -Pinecone  (fully managed, cloud based and highly scalable).

![image](https://github.com/user-attachments/assets/81f4aef4-5896-4d1e-b104-4cabebc585c9)

Finally matching data with the query retrieved from index and final response generated using google/flan-t5 model (Retrieval Augmented Generation).
