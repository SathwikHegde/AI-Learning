# Module 2.5: LangChain for Data Analysis


This directory explores the power of **LangChain**, the industry-standard framework for developing applications powered by language models. In this unit, we specifically focus on how LangChain can be used to augment Large Language Models (LLMs) with the ability to perform complex **Data Analysis** by connecting them to external data sources and computation engines.

---
##  Learning Objectives
The primary goal of this unit is to move from "Prompting" to "Chaining." Key focus areas include:
* **The LangChain Framework:** Understanding the core components—Models, Prompts, Chains, and Agents.
* **Data Connectivity:** Learning how to "ground" an LLM in your own data (CSVs, SQL databases, or PDFs).
* **Automated Analysis:** Utilizing **Agents** that can write and execute Python code on the fly to answer data-driven questions.
* **Memory & State:** Implementing conversation memory so the AI can remember previous analysis steps in a multi-turn dialogue.

---

## Key Concepts Covered

### **The Architecture of a LangChain App**
LangChain allows us to build a pipeline where the LLM is just one part of the system:
1.  **Components:** Modular building blocks for LLM applications.
2.  **Chains:** Sequences of components combined to accomplish a specific task.
3.  **Agents:** LLMs that use a reasoning loop to decide *which* tools to use (e.g., "Use the Calculator tool for this math," or "Use the Pandas tool for this dataset").



### **LangChain for Tabular Data**
We focus on the `create_pandas_dataframe_agent`, which allows business users to interact with data using natural language:
* **Natural Language to Code:** The agent translates a user's question (e.g., "Which region had the highest sales growth?") into Python/Pandas code.
* **Self-Correction:** If the code fails, the agent reads the error message and tries a different approach until it succeeds.
* **Visualization:** Instructing the agent to generate charts and graphs directly from a dataset using libraries like Matplotlib or Seaborn.

---

## Skills & Knowledge Acquired
* **Agentic Workflows:** Understanding how an LLM can act as a "reasoning engine" to control other software tools.
* **Data Interfacing:** Proficiency in loading external datasets into an LLM context without exceeding token limits.
* **Scalable AI Design:** Ability to build reusable "chains" that can be applied to different business datasets with minimal reconfiguration.

---

## Module Completion Requirements
To fulfill the requirements for this unit toward your **Columbia University Certificate**:
1.  **Watch** the technical lecture on LangChain Fundamentals.
2.  **Review** the documentation for LangChain Agents and Tools.
3.  **Complete the Lab:** Build a "Data Assistant" in Google Colab that can analyze a sample sales CSV using LangChain.
4.  **Submit** your notebook demonstrating at least three complex queries performed by the agent.
