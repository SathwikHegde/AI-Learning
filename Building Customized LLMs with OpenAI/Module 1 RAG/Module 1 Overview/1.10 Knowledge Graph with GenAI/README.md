#  Module 1.10: Knowledge Graph with GenAI
### *Building Customized LLMs with OpenAI — Columbia Plus*

This unit introduces **Knowledge Graphs** as a sophisticated method for structuring entities and their relationships within text. Unlike standard vector databases that store data as isolated "points" in space, knowledge graphs map out how data points are interconnected, enabling more complex reasoning and efficient retrieval for domain-specific AI applications.

---

##  Learning Objectives
The primary goal of this session is to move from semantic search to relational reasoning. Key focus areas include:
* **Understanding Knowledge Graphs**: Defining what a graph-based data structure is and how it differs from traditional databases.
* **Entity-Relationship Modeling**: Learning how to identify "Nodes" (entities like People, Places, or Concepts) and "Edges" (the relationships between them).
* **Graph-RAG Integration**: Exploring how combining Knowledge Graphs with LLMs enhances retrieval-augmented generation.
* **Domain-Specific Applications**: Identifying use cases in complex fields like medical research, fraud detection, and organizational mapping where relational data is critical.

---

## Key Technical Concepts

### **1. What is a Knowledge Graph?**
A knowledge graph represents data in a network structure. It consists of:
* **Nodes/Entities**: The "nouns" of your data (e.g., *OpenAI*, *GPT-4o*, *Sam Altman*).
* **Edges/Predicates**: The "verbs" or relationships (e.g., *OpenAI* **developed** *GPT-4o*; *Sam Altman* **is the CEO of** *OpenAI*).
* **Triples**: The fundamental unit of a graph, following the structure: `Subject -> Predicate -> Object`.

### **2. Why Use Graphs with GenAI?**
While vector search is great at finding "similar" things, Knowledge Graphs excel at:
* **Multi-hop Reasoning**: Answering questions that require connecting multiple pieces of information (e.g., "Find the founder of the company that created the model we are using").
* **Hallucination Prevention**: Providing a verifiable, structured "truth" that the model can query directly.
* **Contextual Breadth**: Surrounding a query with related entities that a simple vector search might miss.

### **3. Building Graphs with LLMs**
Using models like GPT-4o to automatically extract structured triples from raw, unstructured text documents, significantly reducing the manual labor involved in graph construction.

---

## Skills & Knowledge Acquired
* **Structural Thinking**: Ability to visualize complex business information as a network of interconnected facts.
* **Advanced Retrieval**: Developing strategies for "Graph-RAG," where the AI navigates the knowledge graph to gather context for a response.
* **Data Synthesis**: Learning how to unify fragmented data sources into a single, coherent knowledge architecture.

---

##  Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1.  **Watch** the 1.10 Knowledge Graph with GenAI video in full.
2.  **Visual Review**: Examine the graph diagrams provided in the lecture to understand how nodes and edges connect.
3.  **Reflect**: How could a Knowledge Graph improve the "memory" or reasoning of the customer service chatbot you built earlier in this module?

---

