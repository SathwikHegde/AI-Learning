## Module 2.5: Prepare Dataset for Fine Tuning
### *Building Customized LLMs with OpenAI — Columbia Plus*

This unit focuses on the most critical (and often most tedious) phase of model customization: **Data Preparation**. As the saying goes, "garbage in, garbage out." This session details the rigorous process of cleaning, structuring, and validating your data to meet OpenAI's specific requirements, ensuring your fine-tuning job actually delivers the results you're paying for.

---

## Learning Objectives
The primary goal of this session is to transform raw, messy information into a high-quality training asset. Key focus areas include:
* **JSONL Mastery**: Understanding the "JSON Lines" format and why it is the strict standard for OpenAI's training pipeline.
* **Data Cleaning & Sanitization**: Identifying and removing duplicates, outliers, and formatting errors that can confuse the model.
* **Validation Protocols**: Learning how to programmatically check your dataset for common pitfalls before uploading.
* **Token Budgeting**: Estimating the cost of your fine-tuning job based on the volume and length of your training examples.

---

## Key Technical Concepts

### **1. The JSONL Format**
Every training example must be a single, valid JSON object on its own line. This allows the training server to stream large datasets efficiently without loading the entire file into memory at once.
> **Format Check**: 
> `{"messages": [{"role": "system", "content": "..."}, {"role": "user", "content": "..."}, {"role": "assistant", "content": "..."}]}`
> *Crucial*: No trailing commas between lines and no "pretty-printing" (each example must stay on exactly one line).

### **2. Data Validation**
Before hitting the upload button, you must run validation scripts to check for:
* **Role Consistency**: Ensuring every example includes the mandatory system, user, and assistant roles.
* **Empty Strings**: Catching null values or whitespace-only messages that lead to training failures.
* **Length Constraints**: Ensuring no single example exceeds the model's maximum context limit.

### **3. Dataset Balancing**
* **Deduplication**: Removing identical prompts to prevent the model from becoming "stuck" on specific patterns.
* **Distribution**: Ensuring a representative mix of examples so the model doesn't develop a bias toward one type of response.

---

## Skills & Knowledge Acquired
* **Pythonic Pre-processing**: Proficiency in using libraries like `json` and `pandas` to automate the conversion of CSVs to JSONL.
* **Quality Assurance (QA)**: Developing a "pre-flight checklist" to catch errors that would otherwise lead to expensive, failed OpenAI jobs.
* **Cost Estimation**: Using the `tiktoken` library to calculate the exact number of tokens in your dataset for precise billing forecasts.

---

## Module Progress
To satisfy the requirements for this unit toward your **Columbia University Certificate**:
1. **Watch** the 2.5 Dataset Preparation video in full.
2. **Download** the sample validation script provided in the course platform.
3. **Execute** a validation check on your IMDB dataset (from Unit 2.4) and fix any errors identified by the script.

---