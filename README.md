<h1>Programs with Diffirent LLM Workflows and Models </h1>

<h2>Description</h2>
This repository explores about how to built generative AI application with different workflows, models and Vector Database Integrations with RAG method.

- Vector database used: Chromadb
- Framework used: Langchain
- Embedding model: huggingface embedding model
- Models: llama 3.3, llama 3.1, llama 3.2, deepseek

Below are detailed description of code.

- demo_anthrophic_basic_workflow.ipynb: program has been writtern with "basic llm workflow", where an llm will generate the content for the given input

- Anthrophic_eval.ipynb: "Evaluator-optimizer workflow" has been implemented in this code, where one llm will generate content on given input and other llm will evaluate the content.

- Anthrophic_orches.ipynb: "Orchestrator-workers workflow" has been experimented in this code, where an orchestrator llm will divide the input task and feed into worker llms to generate output.

- Other programs: are experimentation for Test generation repository, which helped me to break the project into pieces and execute it.


<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
