
---

# Llama3MultiAgent

## Project Description
Llama3MultiAgent leverages the LangGraph AI framework and the open-source Llama3 model from Groq for a multi-agent system. Inspired by CAMEL AI research, this project extends the concept of role-playing among multiple agents. The system consists of a main agent called `DataScientist` and other specialized agents: `InternetFinder`, `SQLWriter`, and `PythonProgrammer`. Tasks given by the user are managed by these agents collaboratively. By implementing role-playing among the LLMs, the project achieves better accuracy in producing results, with the `DataScientist` agent orchestrating the conversations among other agents to perform tasks in natural language.

## Features
- **Multi-Agent System:** Collaborates multiple agents with specialized roles.
- **Role-Playing Concept:** Implements CAMEL AI's role-playing among LLMs.
- **Improved Accuracy:** Achieves better results through specialized agent interactions.
- **Natural Language Processing:** Handles tasks and produces results in natural language.
- **Prompt Enhancer:** Enhances user queries for better output.

## Workflow
The project connects to a database, allowing users to query in natural language about their data. For example, users can ask about the top-selling product or why sales are declining. The system mimics a real data scientist's work by fetching data from the database, searching the internet for real-time information using the DuckDuckGo search engine, and executing Python codes to complete the task. A `PromptEnhancer` is also included to improve user queries for better results.

![MultiAgentArchitecture](https://github.com/user-attachments/assets/6b1572aa-9463-46b6-9226-eca97d751f3a)

Url link for the paper: 
[CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society](https://doi.org/10.48550/arXiv.2303.17760)


## Acknowledgments
I would like to express my gratitude to:
- **Groq** for providing open-source APIs for accessing LLMs with function-calling abilities.
- **Meta LLaMA 3** for their open-source LLMs.
- **LangSmith** For providing tools that facilitate easy debugging and testing of LLM Application using LangGraph.


---
