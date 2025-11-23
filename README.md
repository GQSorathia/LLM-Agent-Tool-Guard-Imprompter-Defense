# LLM-Agent-Tool-Guard-Imprompter-Defense
Post-Generation Defense against Imprompter Adversarial Tool Misuse in LLM Agents.

## Project Summary

This repository contains the code and documentation for the conference paper: "A Lightweight Post-Generation Guard Against Improper Tool Use in LLM Agents."

This work addresses the security vulnerability demonstrated by the Imprompter attack ($\text{arXiv:2410.14923}$), which uses adversarial prompts to force LLM agents to misuse their tools (e.g., to leak sensitive data via malicious markdown image tags). Our solution is a simple, highly performant Post-Generation Tool-Call Guard implemented as a regular expression filter on the agent's output.

