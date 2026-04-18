# 🔍 Module 1.4: Vector Search – Retrieve Similar Vectors
### *Building Customized LLMs with OpenAI — Columbia Plus*

In this unit, Professor Johar explores the algorithmic efficiency of **Vector Search**. As datasets scale from hundreds to millions of documents, simple math isn't enough—you need specialized algorithms to find relevant information instantly. This session focuses on the **Navigable Small Worlds (NSW)** algorithm, a core technique for high-performance vector retrieval.

---

## 🎯 Learning Objectives
The primary goal of this session is to understand how vector databases navigate massive amounts of high-dimensional data. Key focus areas include:
* **The Search Challenge**: Understanding why "Brute Force" search (comparing a query to every single vector) is too slow for production apps.
* **Navigable Small Worlds (NSW)**: Learning how nodes (vectors) are linked in a graph to allow for "greedy" searching through the data.
* **Proximity Graphs**: Understanding how mathematical relationships are used to create "short-cuts" across the data landscape.
* **Efficiency vs. Accuracy**: Managing the trade-offs between search speed and the quality of the retrieved results.

---

## 📂 Key Technical Concepts

### **1. The "Small World" Phenomenon**
Inspired by social network theory, this concept suggests that most nodes in a network can be reached from every other node by a small number of steps. In vector search, we build a graph where:
* Vectors that are semantically similar are physically linked.
* Long-distance links are added to allow the search "jump" quickly across the database.

### **2. Greedy Search Algorithm**
When a user asks a question, the search doesn't look everywhere. Instead:
1. It starts at a random entry point in the graph.
2. It looks at the neighbors and moves to the one closest to the query vector.
3. It repeats this until it can no longer find a neighbor that is closer.

### **3. HNSW (Hierarchical Navigable Small Worlds)**
A preview of the industry-standard evolution of NSW, which adds multiple layers (like a skip-list or a multi-level map) to make searches even faster.

---

## 🛠️ Skills & Knowledge Acquired
* **Algorithmic Literacy**: Understanding how modern vector databases (like Pinecone, Weaviate, or Milvus) actually work under the hood.
* **Graph-Based Retrieval**: Moving beyond linear math to graph-based navigation strategies.
* **System Scalability**: Identifying when a project requires an Approximate Nearest Neighbor (ANN) approach versus a simple exact search.

---

## ⭐ Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1. **Watch** the 1.4 lecture on Vector Search algorithms.
2. **Review** the visual representations of NSW graphs to understand the pathing logic.
3. **Continue** to the next unit to see how these search techniques are applied to text analytics.

---

**Would you like me to explain the difference between "Exact Search" and "Approximate Nearest Neighbor" search in the context of business costs and latency?**