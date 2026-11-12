# Project guide

This repository is a learning demo for LangChain agent examples. The current root README documents Python 3.13, an Ollama server and local environment configuration.

## Setup

Follow the commands in the root README. Store the Ollama bearer token in a local `.env` file and never commit real credentials.

## Running an example

```bash
python -m examples.agent-lecture.simple_agent
```

## Before sharing a demo

- State which model and Ollama endpoint were used.
- Include a short example prompt and expected behavior.
- Document tool access and any side effects explicitly.
- Add tests for tool errors, empty responses and unavailable model servers.
