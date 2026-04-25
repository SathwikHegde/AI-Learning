# Module 2.3: Adapters
### *Building Customized LLMs with OpenAI — Columbia Plus*

In this unit, Professor Johar introduces the concept of **Adapters**, a revolutionary approach to model customization. This session explains how adapters allow technical practitioners to build highly specialized models with extreme efficiency, avoiding the massive computational costs of retraining large language models from scratch.

---

## Learning Objectives
The primary goal of this session is to understand the mechanics of "Modular AI." Key focus areas include:
* **The Concept of Adapters**: Understanding how small, trainable modules can be "plugged in" to a large, frozen base model.
* **Efficiency at Scale**: Analyzing how adapters significantly reduce the number of parameters that need to be trained.
* **Avoiding Full Retraining**: Learning why modifying an existing model is superior to starting from scratch for most business use cases.
* **Versatility and Adaptability**: Exploring how different adapters can be swapped in and out to allow one base model to perform dozens of specialized tasks.

---

## Key Technical Concepts

### **1. Lightweight Customization**
Instead of updating billions of weights in a model, adapters involve training only a tiny fraction (often <1%) of additional parameters. 
* **Frozen Base Model**: The original LLM remains untouched, preserving its general knowledge.
* **Task-Specific Modules**: Only the "adapter" layers are optimized for the new domain.

### **2. Storage and Compute Advantages**
* **Storage**: Because the base model is frozen, you only need to store the small adapter file for each custom task (kilobytes or megabytes instead of gigabytes).
* **Compute**: Training requires significantly less GPU memory, making it accessible for developers without massive server farms.

### **3. Rapid Swapping**
In a production environment, a single base model can be loaded into memory once. Depending on the user's request, the system can instantly "swap" the active adapter to change the model's expertise (e.g., from a legal expert to a creative writer).

---

## Skills & Knowledge Acquired
* **Modular Architecture**: Ability to explain how bottleneck layers or residual connections enable adapter integration.
* **Resource Optimization**: Determining when the cost-benefit ratio favors adapters over standard fine-tuning.
* **Scalable AI Deployment**: Designing systems where one model serves multiple distinct business functions via adapter-switching.

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1. **Watch** the 2.3 Adapters lecture video in full.
2. **Review** the visual diagrams showing where adapters are placed within the transformer layers.
3. **Compare** this method to the "Other Types of Fine Tuning" discussed in Unit 2.2.

---
