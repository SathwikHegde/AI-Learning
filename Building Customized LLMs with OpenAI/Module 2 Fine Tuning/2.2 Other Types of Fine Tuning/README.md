# Module 2.2: Other Types of Fine Tuning
### *Building Customized LLMs with OpenAI — Columbia Plus*

In this unit, Professor Johar introduces advanced approaches to fine-tuning that go beyond traditional full-parameter updates. This session focuses on the technical nuances and the critical trade-offs involved in selecting alternative techniques, ensuring you can choose the most efficient path for your specific business constraints.

---

## Learning Objectives
The primary goal of this session is to expand your toolkit for model customization. Key focus areas include:
* **Beyond Traditional Methods**: Moving away from "Full Fine-Tuning" to understand more resource-efficient alternatives.
* **Trade-off Analysis**: Evaluating the relationship between computational cost, training time, and model performance.
* **Parameter-Efficient Fine-Tuning (PEFT)**: Introducing techniques that allow you to adapt large models by only training a small fraction of their parameters.
* **Nuance in Application**: Identifying which specific business use cases (e.g., low-latency requirements vs. high-accuracy tasks) demand different tuning strategies.

---

## Key Concepts Covered

### **1. Efficiency vs. Performance**
Traditional fine-tuning requires significant GPU memory and time. We explore:
* **Full Parameter Tuning**: Updating all weights (high cost, high accuracy).
* **Freezing Layers**: Keeping the base model's "core knowledge" intact while only training the final layers.

### **2. Alternative Techniques**
A preview of the modern methods used in the industry today:
* **Adapter-Based Tuning**: Inserting small, trainable modules into the existing architecture.
* **Prompt Tuning / Prefix Tuning**: Learning a specific "soft prompt" that guides the model without changing its underlying weights.

### **3. Decision Nuances**
Understanding that "more tuning" isn't always better. We discuss:
* **Catastrophic Forgetting**: The risk of a model losing its general abilities while becoming too specialized.
* **Data Scarcity**: How alternative methods can actually perform *better* when you have a very small dataset.

---

##  Skills & Knowledge Acquired
* **Strategic Selection**: Ability to defend a choice between different tuning methods based on budget and hardware availability.
* **Architectural Awareness**: Understanding how modern AI frameworks (like Hugging Face) implement these alternative tuning paths.
* **Optimization Mindset**: Learning how to achieve "90% of the results with 10% of the compute."

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1. **Watch** the 2.2 lecture on alternative fine-tuning methods.
2. **Review** the trade-off matrix provided by Professor Johar in the video.
3. **Continue** to the next unit to see these alternative techniques applied in a hands-on environment.

---