---
tags:
  - Writing
  - Systems
date: 2026-10-09
title: Creating an Diet Tracker + Helper app with openCode!
description: You know, most diet tracker apps are paid, lets try vibecoding to try and fix that!
cover:
image: images/opencode.png
---

Hey guys! Hyp-n here! So, today, we are going to use openCode, an agentic harness, to make an Diet Tracker App! So, don't worry this is more of a hands-on tutorial, I'm not going to spoonfeed you, you're going to be doing most of the stuff.

# Requirements:
- Install openCode, connect it to openrouter

## Using an AI orchestrator along with subagents.

```mermaid
graph TD
    A[User Prompt: Change/Add Feature] --> B{Orchestrator Agent}
    B --> F[Provide Update to User]
    
    B -->|Prompt & Context| C[Coder Subagent]
    C -->|Output| B
    B -->|Review| D[Security Subagent]
    D -->|Feedback| B
    B -->|Test via MCPs| E[Tester Subagent]
    E -->|Results| B
```

