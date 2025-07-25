# AI Product Analyzer with CrewAI and Ollama

This project is an AI-driven system that automates the process of product analysis by simulating a multi-agent team using [CrewAI](https://github.com/joaomdmoura/crewAI). It leverages the `deepseek-r1:1.5b` language model running locally via [Ollama](https://ollama.com/) and is designed to generate clear product descriptions, use case breakdowns, and expert evaluations—all formatted in Markdown.


##  Project Overview

This system emulates the workflow of a team of domain experts working together to analyze a product. It includes three specialized AI agents:

- **Product Describer:** Generates a clear, concise Markdown-formatted description of a given product.
- **Use Case Expert:** Lists common use cases, types, and target users of the product in structured Markdown format.
- **Reviewer & Evaluator:** Reviews and critiques the outputs of the previous agents, providing feedback and suggestions for improvement.

The agents are coordinated using CrewAI to sequentially perform their tasks and collaboratively generate a professional evaluation report.



## Features

-  Multi-agent architecture powered by CrewAI
-  Natural language product description and analysis
-  Markdown-formatted output for easy documentation and integration
-  Local inference using the DeepSeek-R1 model with Ollama (no OpenAI API needed)
-  Real-time input for flexible product evaluation

---

## Installation

```bash
pip install crewai crewai_tools langchain_community colab-xterm
curl -fsSL https://ollama.com/install.sh | sh
