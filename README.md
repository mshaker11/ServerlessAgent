# ServerlessAgent


# Serverless AI Agent

A serverless multi-agent AI system built in Python that uses multiple specialized LLM agents to analyze and generate content. The project demonstrates how AI agents can work together in a pipeline, with each agent handling a different part of the task.

## Overview

The system uses multiple AI agents with different responsibilities:

- **Sentiment Agent** – analyzes the sentiment and tone of content
- **Content Agent** – generates or improves written content
- **Context Agent** – evaluates the broader context of the input
- **Agent Pipeline** – combines the outputs from the individual agents to produce a final result

The goal of the project was to explore multi-agent AI systems and how specialized agents can collaborate to complete a larger task.

## Tech Stack

- Python
- OpenAI API
- SwarmNode SDK
- Large Language Models (LLMs)
- Serverless Architecture
- REST APIs

## How It Works

1. User input is received by the system.
2. The input is passed through multiple specialized AI agents.
3. Each agent analyzes the input based on its assigned role.
4. The agents' outputs are combined and processed.
5. The system generates a final response or piece of content.

```text
User Input
    |
    v
Sentiment Agent
    |
    v
Context Agent
    |
    v
Content Agent
    |
    v
Final Output
