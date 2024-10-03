# Research Assistant 

## Overview

**Research Assistant** is an intelligent research and report-generation agent built using the `LLaMA-3.1-70B` versatile model and powered by `LangGraph`. This powerful tool can perform web searches, engage in discussions with AI analysts, and generate in-depth, well-structured reports based on the collected insights and data.

### Key Features:
- **Web Searching**: Research Assistant leverages web resources such as Wikipedia and Travily to gather relevant and trustworthy information on the specified topic.
- **AI Analyst Collaboration**: It creates its own AI analysts to discuss the topic, providing multiple perspectives and deep analysis before concluding.
- **In-depth Report Generation**: After web searches and AI analyst discussions, Research Assistant writes a properly structured, detailed, and well-reasoned report on the given topic.

### Use Case Example:
For example, when tasked with writing a report on **eco-friendly industrial practices**, Research Assistant will:
1. Perform web searches using **Wikipedia** and **Travily**.
2. Create and engage AI analysts to discuss various subtopics related to eco-friendly practices.
3. Deduce the final results by combining insights from both the web search and AI discussions.
4. Output a comprehensive and properly indented report.

---

## Architecture

1. **LLaMA-3.1-70B Model**:
    - A state-of-the-art large language model that drives the core reasoning, natural language understanding, and generation abilities of Research Assistant.
    - Provides the capability to generate accurate and coherent discussions among AI analysts.

2. **LangGraph**:
    - Facilitates the creation and management of interactive AI analysts.
    - Ensures smooth communication between different AI agents for a collaborative discussion on the given research topic.

3. **Web Search Integration**:
    - Wikipedia and Travily are used as external search engines to pull real-time, up-to-date information.
    - Research Assistant synthesizes findings from both sources and merges them with the analysis done by the AI agents.

---

## Workflow

### Step-by-step Process:

1. **Input Topic**: The user provides a topic or research question to Research Assistant.
2. **Web Search**:
    - The agent initiates web searches using Wikipedia and Travily to gather initial data.
    - Results are extracted and pre-processed for discussion.
3. **AI Analyst Creation**:
    - The system creates AI analysts to represent different viewpoints or subtopics.
    - Analysts engage in a discussion based on the web search data and their interpretations.
4. **Synthesis**:
    - The insights from both the AI analyst discussions and web search results are compiled.
    - Conflicting opinions are resolved, and key points are identified.
5. **Report Generation**:
    - A detailed, properly indented report is created.
    - The report combines insights, web findings, and conclusions in a structured manner.

---
