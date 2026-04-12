# Module 1.3: Notebook Demo – Embedding Vectors and Cosine Similarity
### *Building Customized LLMs with OpenAI — Columbia Plus*

In this hands-on technical unit, Professor Johar transitions from RAG theory to implementation. This video walks you through the construction of a **Retrieval-Augmented Generation (RAG) chatbot** from scratch, using synthetic customer service data within the Google Colab environment.

---

## Learning Objectives
The primary goal of this demonstration is to understand the mathematical and logical operations that power AI search. Key focus areas include:
* **Vector Creation**: Learning how to transform text data into numerical **embedding vectors** using the OpenAI API.
* **Semantic Search**: Implementing **Cosine Similarity** to measure the "distance" between a user's question and the stored knowledge base.
* **Synthetic Data Workflows**: Utilizing generated customer service data to test the chatbot's accuracy in a controlled sandbox.
* **Context Retrieval**: Understanding how to select the most relevant "chunks" of data to pass into the LLM's prompt.

---

## Technical Concepts Covered

### **1. Embedding Vectors**
Text is converted into high-dimensional vectors. If two sentences have similar meanings (e.g., "How do I reset my password?" and "I forgot my login credentials"), their vectors will be positioned close to each other in mathematical space.

### **2. Cosine Similarity**
The core metric used to determine relevance:
* **Definition**: A measure of similarity between two non-zero vectors that measures the cosine of the angle between them.
* **Scale**: Ranges from **0 to 1** (in this context), where **1** represents identical semantic meaning and **0** represents no relation.

### **3. The Build Sequence**
1.  **Load Data**: Import the synthetic customer service CSV/JSON.
2.  **Embed**: Send the data to OpenAI to receive vector representations.
3.  **Query**: Embed the user's live question.
4.  **Calculate**: Run the Cosine Similarity math to find the top $N$ matches.
5.  **Generate**: Feed the matches + the question to the LLM for a grounded answer.

---

## Skills & Knowledge Acquired
* **Python for AI**: Proficiency in using `numpy` for vector math and `pandas` for data handling.
* **API Orchestration**: Managing the flow of data between your notebook and OpenAI's embedding and completion models.
* **Troubleshooting RAG**: Identifying why a model might retrieve the wrong information (e.g., poor chunking or low similarity thresholds).

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1.  **Watch** the 1.3 Notebook Demo in full.
2.  **Follow Along**: It is highly recommended to open the corresponding Google Colab notebook and execute the cells alongside the video.
3.  **Verify**: Ensure your script can successfully return a relevant data chunk for a sample user query.

---