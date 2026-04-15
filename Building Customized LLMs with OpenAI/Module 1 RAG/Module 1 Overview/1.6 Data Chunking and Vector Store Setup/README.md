# Module 1.6: Data Chunking and Vector Store Setup
### *Building Customized LLMs with OpenAI — Columbia Plus*

This technical unit focuses on the infrastructure of a **Retrieval-Augmented Generation (RAG)** system. In this walkthrough, Xilin Wang demonstrates how to prepare raw data for AI consumption by implementing strategic **chunking** and configuring a **vector store**. This is a critical step in ensuring your chatbot can retrieve accurate information quickly and at scale.

---

## Learning Objectives
The primary goal of this session is to master the "ETL" (Extract, Transform, Load) process for vector databases. Key focus areas include:
* **Chunking Optimization**: Understanding how to split long documents into smaller, semantically coherent pieces.
* **Vector Store Configuration**: Setting up a local or cloud-based database to store and index embedding vectors.
* **Metadata Integration**: Learning how to attach extra information (like source links or categories) to your chunks for more precise filtering.
* **Indexing for Speed**: Exploring how vector stores organize data to allow for near-instantaneous similarity searches.

---

## Key Technical Concepts

### **1. The Art of Chunking**
If a chunk is too small, it loses meaning; if it is too large, it can dilute the relevance of a search. This unit covers:
* **Character vs. Token Chunking**: Choosing the right unit of measurement for your splits.
* **Chunk Overlap**: Why keeping a small "buffer" between chunks (e.g., 10-20%) is necessary to prevent splitting a critical sentence in half.

### **2. Embedding Pipelines**
Converting the chunks into math.
* **Batch Processing**: Sending multiple chunks to the OpenAI `text-embedding-3-small` or `large` models simultaneously to save time and reduce API overhead.

### **3. Vector Store Setup**
Initializing the "brain" of the RAG system.
* **FAISS/Chroma/LanceDB**: Utilizing lightweight, efficient vector stores that can run directly within your Google Colab environment.
* **Persistence**: Understanding how to save your vector store so you don't have to re-embed your data every time you restart the notebook.

---

## Skills & Knowledge Acquired
* **Data Architecture**: Ability to design a robust pipeline that transforms raw text into a searchable vector index.
* **Computational Efficiency**: Learning how to balance chunk size with the model's context window limits.
* **Scalable Retrieval**: Developing the skills to manage datasets that are too large to fit into a standard prompt without RAG.

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1.  **Watch** the 1.6 Data Chunking and Vector Store Setup video in full.
2.  **Verify Setup**: Ensure your Google Colab script can successfully ingest a CSV and generate a corresponding vector index.
3.  **Check Indices**: Use a simple search command to confirm that the vector store returns the expected top-k results for a sample prompt.

---