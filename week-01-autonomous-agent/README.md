# Week 1: The Autonomous IT Support Agent

## Overview
This notebook implements an AI-driven "first responder" agent designed to automate Level 1 IT incident management for server infrastructure.

## Key Capabilities
1. **Investigate:** Automatically checks server health metrics and system logs when an incident is reported.
2. **Act:** Evaluates conditions (e.g., if CPU utilization exceeds 90%, it triggers an automated service restart).
3. **Escalate:** Routes complex issues or critical anomalies to human support teams.

## Tech Stack
* Python
* Google Colab / Jupyter Notebooks
* OpenAI API (`openai` library)

## How to Run
1. Open the notebook in Google Colab (or run it locally in Jupyter).
2. Set your OpenAI API key as an environment variable or notebook secret (`OPENAI_API_KEY`).
3. Run the cells sequentially to test the agent's incident response workflow.