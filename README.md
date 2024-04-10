## LLaMA2 Q&A System with Sentence Embeddings

This project creates a question-and-answer (Q&A) system using the powerful LLaMA2 large language model and sentence embeddings for document search.

**Features:**

- Leverages LLaMA2 to answer your questions in an informative way.
- Utilizes sentence embeddings to efficiently search through a document collection.
- Provides a user-friendly interface for querying the system.

**Requirements:**

- Python 3.x
- `pip install transformers`
- `pip install einops accelerate langchain bitsandbytes` (for LLaMA2)
- `pip install sentence-transformers` (for sentence embeddings)
- `pip install llama_index` (for LLaMA2 integration)


**Example Usage:**

```
Query: What is Yolo?
```

The system will retrieve and process relevant documents using sentence embeddings and generate a response using LLaMA2 based on its understanding of the query and the documents.

**Disclaimer:**

- Running LLaMA2 locally requires significant computational resources (CPU, GPU, memory). Adjust configurations or use a machine with appropriate capabilities.
- The pre-trained models used are large and may take time to download.

**Further Development:**

- Explore integrating the system with a web interface for a more user-friendly experience.
- Experiment with different sentence embedding models for potentially improved search accuracy.
- Fine-tune LLaMA2 on a specific domain for more focused responses.

**Contribution:**

We welcome contributions to this project! Feel free to submit pull requests with improvements or bug fixes.
