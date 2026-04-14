# Module 1.5: Basic Chatbot Setup
### *Building Customized LLMs with OpenAI — Columbia Plus*

In this technical lab session, Xilin Wang leads a hands-on walkthrough for constructing a **Retrieval-Augmented Generation (RAG) chatbot** from the ground up. Utilizing synthetic customer service data within **Google Colab**, this unit demonstrates the practical integration of data retrieval and language generation to create a functional AI assistant.

---

## Learning Objectives
The primary goal of this setup is to move from theory to a working prototype. Key focus areas include:
* **Workflow Orchestration**: Integrating the individual components of a RAG system into a single, cohesive Python script.
* **Data Ingestion**: Loading and preparing synthetic customer support datasets for AI consumption.
* **Query Transformation**: Processing user input to ensure it can effectively trigger the retrieval mechanism.
* **Prompt Construction**: Designing the system and user prompts that instruct the LLM to use the retrieved data as its "source of truth."

---

## Key Technical Components

### **1. The RAG Pipeline**
The chatbot follows a strict operational sequence to ensure accuracy:
1.  **Input**: The user submits a customer service inquiry.
2.  **Retrieve**: The system identifies and pulls the most relevant text chunks from the knowledge base.
3.  **Augment**: The system combines the user's query with the retrieved facts.
4.  **Generate**: The OpenAI API processes the combined prompt and generates a grounded response.

### **2. System Prompt Engineering**
A critical part of the setup is defining the **System Role**. This ensures the chatbot:
* Maintains a helpful, professional tone.
* Admits when it does not know an answer (avoiding hallucinations).
* Only references information found in the provided snippets.

### **3. Interaction Loop**
Implementing a continuous loop that allows for a conversational experience, enabling the user to ask follow-up questions within the Colab environment.

---

## Skills & Knowledge Acquired
* **End-to-End Development**: Proficiency in building a complete AI application within a Jupyter Notebook.
* **Contextual Grounding**: Understanding how to programmatically limit an LLM's knowledge base to specific organizational data.
* **Synthetic Data Testing**: Learning how to use "fake" data to stress-test your chatbot's logic before deploying it with real customer records.

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1.  **Watch** the 1.5 Basic Chatbot Setup demonstration in full.
2.  **Execute the Code**: Follow along in Google Colab, ensuring you have your **OpenAI API Key** properly configured in the "Secrets" tab.
3.  **Test**: Submit a query to your chatbot and verify that it retrieves the correct synthetic data point to formulate its response.

---
