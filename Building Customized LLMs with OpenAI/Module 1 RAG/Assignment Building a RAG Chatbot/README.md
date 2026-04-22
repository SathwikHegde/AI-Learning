# 🛠️ Module 1 Assignment: Building a RAG Chatbot
### *Building Customized LLMs with OpenAI — Columbia Plus*

This directory contains the hands-on project for **Module 1**. In this assignment, you will transition from theoretical concepts to building a functional AI chatbot. You will implement a **Retrieval-Augmented Generation (RAG)** pipeline to query complex financial data, specifically using **Apple's 10-K report** as the primary knowledge base.

---

## Assignment Overview
The goal is to build a chatbot that can accurately answer questions about Apple's financial and operational status by retrieving relevant sections from its 10-K filing. This prevents the model from "hallucinating" and ensures its responses are grounded in official corporate data.

**Key Technical Skills:**
* **Data Retrieval**: Interfacing with large PDF/text documents.
* **Vector Storage**: Using similarity search to find relevant context.
* **LLM Integration**: Sending retrieved context to an LLM to generate a human-readable answer.

---

## Technical Stack
To complete this build, you will utilize the following industry-standard tools:
* **OpenAI API**: The "reasoning engine" used for generating responses and creating embeddings.
* **LangChain**: The orchestration framework used to link the data, the vector store, and the LLM.
* **FAISS (Facebook AI Similarity Search)**: The library used for efficient similarity search and clustering of dense vectors.

---

## Instructions for Google Colab

Follow these steps to complete and submit your project:

1.  **Open the Notebook**: Click the **"Open in Colab"** icon provided in the course portal to launch the assignment environment.
2.  **Make a Copy**: Go to `File` > `Save a copy in Drive`. This ensures you have a personal version to edit and save.
3.  **Implement & Test**: Complete the coding sections. You are encouraged to use LLMs to help generate code snippets or explain complex interactions within the context window.
4.  **Submission**:
    * Download your finished work via `File` > `Download` > `Download .ipynb` (or `.pdf`).
    * Click the **"Start Assignment"** button in the course portal and upload your file or submit the relevant URL.

---

## Important Notes
* **Optional but Encouraged**: While this assignment is optional for course completion, it is highly recommended to reinforce the technical content covered in the lectures.
* **API Access**: Ensure your OpenAI API key is stored securely in the Colab "Secrets" tab.
* **Alternative Environments**: If you do not have a Google account, you can download the `.ipynb` file and run it in any Colab-compatible environment (like VS Code or JupyterLab).

---
