# Module 1.8: Sentiment Analysis and Entity Recognition with GenAI
### *Building Customized LLMs with OpenAI — Columbia Plus*

In this unit, Professor Johar expands the scope of text analytics beyond simple retrieval. This session focuses on how Generative AI can be used to extract structured meaning from unstructured text through **Sentiment Analysis** and **Named Entity Recognition (NER)**, providing deeper insights into customer interactions and data patterns.

---

## Learning Objectives
The primary goal of this session is to master advanced text processing techniques. Key focus areas include:
* **Sentiment Classification**: Learning how to programmatically determine the emotional tone (positive, negative, neutral) of a text string.
* **Named Entity Recognition (NER)**: Identifying and categorizing key information such as names, organizations, locations, and dates within a body of text.
* **Text Analytics Workflow**: Integrating these analytical layers into a broader AI system to categorize and route customer inquiries.
* **Coding Implementation**: Walking through a practical Python example to perform sentiment analysis using the OpenAI API.

---

## Key Technical Concepts

### **1. Sentiment Analysis with GenAI**
Unlike traditional rule-based systems, GenAI understands nuance, sarcasm, and context.
* **Zero-Shot Classification**: Asking the model to identify sentiment without providing previous examples.
* **Structured Output**: Instructing the model to return results in a JSON format (e.g., `{"sentiment": "negative", "score": 0.9}`) for easy integration into business dashboards.

### **2. Named Entity Recognition (NER)**
Extracting the "Who, What, and Where" from data.
* **Entity Types**: Recognizing specific categories like **PERSON**, **ORG** (Organization), **GPE** (Geopolitical Entity), and **PRODUCT**.
* **Business Utility**: Automatically extracting account numbers or product names from a support ticket to trigger a RAG search.

### **3. The Analytical Pipeline**
1.  **Input**: Raw customer feedback or chat transcripts.
2.  **Analyze**: Use the LLM to tag entities and score sentiment.
3.  **Route**: If sentiment is "High Negative," escalate the ticket; if "Positive," route to a testimonial database.

---

## Skills & Knowledge Acquired
* **Insight Extraction**: Ability to transform thousands of customer reviews into a structured report on common complaints or praised features.
* **Advanced Prompting**: Crafting prompts that force the model to be objective and consistent in its labeling.
* **Data Enrichment**: Learning how to add analytical tags to your vector store metadata to allow for filtered searches (e.g., "Find all negative reviews regarding the mobile app").

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1.  **Watch** the 1.8 Sentiment Analysis and Entity Recognition video.
2.  **Review the Code**: Examine the sentiment analysis coding example provided in the lecture.
3.  **Experiment**: Try applying the sentiment analysis prompt to a different set of synthetic data in your Google Colab environment.

---

