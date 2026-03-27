# Module 2 Assignment: Data Analysis with LLM

This directory contains the final assessment for **Module 2**. This assignment transitions from individual API calls to a comprehensive, end-to-end data science project. You will use **Large Language Models (LLMs)** and **LangChain Agents** to perform complex data analysis on a real-world dataset, demonstrating your ability to automate technical workflows through natural language.

---

## Assignment Objectives
The goal of this project is to prove proficiency in the "Agentic" approach to data science. You will be evaluated on your ability to:
* **Interface with Data:** Programmatically load and explore datasets within a Google Colab environment.
* **Natural Language Querying:** Use LangChain agents to translate business questions into executable Python code.
* **Statistical Rigor:** Perform data cleaning, descriptive statistics, and correlation analysis.
* **Visualization & Synthesis:** Generate meaningful visual assets (charts/graphs) and summarize technical findings into actionable business insights.

---

## Project Structure & Components

### **1. The Dataset**
You will work with a provided CSV file containing multi-dimensional business data (e.g., sales, customer demographics, or operational metrics). Your first task is to ensure the LLM understands the schema and data types.

### **2. Technical Tasks**
The assignment is divided into three core phases:
* **Exploration:** Identifying missing values, outliers, and basic distributions.
* **Analysis:** Performing group-by operations, pivot tables, and identifying trends over time.
* **Prediction/Modeling:** (Advanced) Using the agent to run a simple regression or classification to predict a specific target variable.

### **3. Deliverables**
* **Colab Notebook (`.ipynb`):** A fully documented notebook containing your code, the agent's reasoning steps, and the final outputs.
* **API Security:** Evidence of using "Secrets" for your OpenAI API key (ensure keys are never hard-coded).
* **Summary Report:** A brief text cell at the end of the notebook summarizing your three most significant data findings.

---

## Tools & Libraries Used
To successfully complete this assignment, your environment must include:
* **OpenAI API:** Serving as the "Reasoning Engine."
* **LangChain:** Specifically the `create_pandas_dataframe_agent`.
* **Pandas:** For data manipulation.
* **Matplotlib/Seaborn:** For generating visual insights.

---

## Grading & Certification Criteria
This is a graded component of the **Columbia University Certificate**. To pass:
1. **Functional Code:** All cells must run sequentially without errors.
2. **Agent Autonomy:** The majority of the analysis should be performed by the LangChain agent rather than manual Pandas coding.
3. **Submission:** Upload your completed notebook to the course portal by the specified deadline.
4. **Passing Grade:** A minimum score of **60%** based on the technical rubric.

---