# LangGraph-with-multiAgents
MultiAgent - RAG (PDF loader) and Wikipedia search
In LangGraph, a "router with multiple agents" refers to a mechanism that directs information flow between different AI agents within a complex workflow, essentially deciding which agent should handle a task based on predefined conditions or the current state of the interaction, allowing for collaborative problem solving where each agent specializes in a specific area.

In this example I have added 2 Agents,  based on question Router will pass the question to one of the following agent:
  1. AstraDB:Vector Database  (PDF uploaded The_GALE_ENCYCLOPEDIA_of_MEDICINE_SECOND)
  2. Wikipedia

    
![alt text](https://github.com/yashu879/LangGraph-with-multiAgents/blob/main/MultiAgents.png)
