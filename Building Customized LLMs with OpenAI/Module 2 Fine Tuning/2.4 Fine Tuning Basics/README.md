# Module 2.4: Fine Tuning Basics
### *Building Customized LLMs with OpenAI — Columbia Plus*

In this hands-on coding unit, Xilin leads a technical walkthrough on the foundational workflow of model adaptation. You will transition from theory to practice by fine-tuning a **GPT-4o** model for a specialized classification task: **Sentiment Analysis** using the classic **IMDB Movie Reviews** dataset.

---

## Learning Objectives
The primary goal of this session is to master the standard OpenAI fine-tuning pipeline. Key focus areas include:
* **The Fine-Tuning Pipeline**: Understanding the sequence from data preparation to model deployment.
* **Instruction Formatting**: Learning how to structure your training data using the Chat Completion format.
* **Task Specialization**: Demonstrating how a base model's sentiment detection accuracy improves when trained on domain-specific examples (movie critiques).
* **OpenAI API Integration**: Using the `openai` Python library to manage files and fine-tuning jobs programmatically.

---

## Technical Workflow

### **1. Data Preparation (.JSONL)**
Fine-tuning requires a specific format. Each line in your training file must be a standalone JSON object containing:
* **System Message**: Defining the persona (e.g., "You are a sentiment analyst").
* **User Message**: The IMDB review text.
* **Assistant Message**: The "Gold Standard" label (Positive/Negative).

### **2. The Fine-Tuning Job**
The steps to execute the update in Google Colab:
1.  **File Upload**: Sending your prepared `.jsonl` files to OpenAI's servers.
2.  **Job Creation**: Initializing the training process on the GPT-4o base.
3.  **Monitoring**: Tracking progress via the OpenAI Dashboard or API status updates.

### **3. Evaluation and Inference**
Once the job is complete, you will receive a unique **Model ID**. You will learn how to:
* Compare the fine-tuned model's output against the base GPT-4o model.
* Verify that the model has adopted the specific tone and classification style required for the IMDB dataset.

---

## Skills & Knowledge Acquired
* **Data Engineering for AI**: Proficiency in converting raw CSV datasets into JSONL training formats.
* **API Management**: Handling asynchronous fine-tuning jobs and managing model versions.
* **Benchmarking**: Assessing whether the cost of fine-tuning is justified by the performance gains in sentiment accuracy.

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1.  **Watch** the 2.4 Fine Tuning Basics coding demo in full.
2.  **Execute the Notebook**: Follow along in Google Colab to upload your training file and start a test job.
3.  **Validate**: Ensure you understand how to call your new custom model using the `model` parameter in the Chat Completions API.

---
