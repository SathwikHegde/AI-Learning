# Module 1.11 Module 1 Q&A: RAGs
### *Building Customized LLMs with OpenAI — Columbia Plus*

This concluding unit of **Module 1** features a deep-dive discussion between Xilin Wang and Professor Johar. This Q&A session is designed to synthesize the technical concepts covered in the previous ten units, focusing on the strategic decision-making involved in choosing between different data architectures.

---

## Learning Objectives
The primary goal of this session is to provide clarity on high-level system design. Key focus areas include:
* **Comparative Architecture**: Deeply analyzing the differences between **Vector-based RAG** and **Knowledge Graphs**.
* **Use-Case Mapping**: Using real-world examples to determine which approach works best for specific business problems.
* **Troubleshooting RAG**: Addressing common technical bottlenecks encountered during the build sequence in units 1.5–1.7.
* **Hybrid Approaches**: Discussing if and when to combine vector search with relational graphs for maximum accuracy.

---

## Key Topics Addressed

### **1. Knowledge Graphs vs. Standard RAG**
While both methods aim to ground the LLM in truth, they solve different problems:
* **Standard RAG (Vector Search)**: Best for finding similar content in large, unstructured text corpora (e.g., "Find the policy on vacation days").
* **Knowledge Graphs**: Best for complex reasoning and identifying relationships (e.g., "Which products are affected by the delay in the Shanghai factory?").

### **2. Real-World Decision Matrix**
The instructors walk through scenarios across various industries:
* **Customer Support**: When a flat vector store is sufficient for an FAQ bot.
* **Supply Chain/Healthcare**: When the interconnected nature of the data demands a graph-based structure to avoid reasoning errors.

### **3. Scaling Challenges**
* Managing API latency when performing "multi-hop" searches in a graph.
* Cost considerations of embedding large datasets versus maintaining a structured graph database.

---

## Skills & Knowledge Refinement
* **Architectural Literacy**: Developing the "intuition" to pick the right tool for the job before writing the first line of code.
* **Error Diagnosis**: Learning how to distinguish between a "retrieval failure" (the AI didn't find the data) and a "generation failure" (the AI found the data but hallucinated the answer).
* **Future-Proofing**: Understanding how the RAG landscape is evolving beyond simple similarity search.

---

## Module Completion
This Q&A serves as the final review before the Module 1 assessment. To successfully move forward:
1.  **Watch** the Q&A session to clear up any lingering technical confusion.
2.  **Review** your Google Colab notebooks from the earlier units.
3.  **Complete the Module 1 Quiz**: Ensure you have a firm grasp of RAG, NSW algorithms, and graph structures.

---