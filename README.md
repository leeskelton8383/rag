# NFL RAG Experiments

This folder contains experiments exploring Retrieval-Augmented Generation (RAG) techniques to answer narrative-style questions about NFL teams, with a focus on the Philadelphia Eagles.

The goal is to test lightweight pipelines for document chunking, embedding, vector retrieval, and summarization — using team season summaries and Wikipedia pages.

Each script isolates a piece of the RAG process:
- Chunking narratives with metadata
- Creating and saving FAISS vector indexes
- Retrieving top-k relevant chunks for a query
- Optional LLM summarization across retrieved context

This is part of a broader project combining RAG and Text-to-SQL for natural language queries over both stats and stories.
Let me know if you want a slightly longer version that links to your other modules or adds usage examples.











