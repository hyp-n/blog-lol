---
tags:
  - Writing
  - Systems
  - AI
  - Opencode
  - Tutorial
  - GUide
  - SEO
  - recipes
  - dosa
  - Performance
  - Coding
date: 2026-10-10
title: Creating stuff with opencode and oh-my-opencode
description: Creating interesting artifacts and apps, just to have fun :)
cover:
image: images/opencode.png
---
**I AM NOT RESPONSIBLE FOR YOU BREAKING YOUR PC :) ANY INCONVINIENCES ARE ENTIRELY YOUR FAULT >:)**


Hello, everybody. Today I will be making an app with OpenCode, paired with oh-my-openCode. Let us continue.

## How I set this up:
So, setting this up was nothing hard. 

- First, install openCode. I used Bun:
```
bun install -g --trust @opencode/cli
```

- Then, install oh-my openCode using:
```
Install and configure oh-my-opencode by following the instructions here:
https://raw.githubusercontent.com/code-yeongyu/oh-my-opencode/refs/heads/master/docs/guide/installation.md
```

And well, after that, it is smooth sailing.

## How it works 

{{<mermaid>}}
flowchart TB
    User["👤 You"] -->|"1. Describe what you want"| Planner["🧠 Planner (Prometheus)\nInterviews you, makes a plan"]
    
    Planner -->|"2. Creates work plan"| PlanFile[("📝 Plan File\n.sisyphus/plans/")]
    
    PlanFile -->|"3. You run /start-work"| Orchestrator["⚡ Orchestrator (Atlas)\nReads plan, manages the work"]
    
    Orchestrator -->|"Delegates tasks"| Workers["🛠️ Specialized Workers"]
    
    Workers -->|"• Sisyphus-Junior: writes code\n• Oracle: architecture advice\n• Explore: finds code patterns\n• Librarian: checks docs\n• Frontend: UI/design\n• Hephaestus: deep logic"| Orchestrator
    
    Orchestrator -->|"Verifies each task\n• Runs tests\n• Checks for errors"| Done["✅ Done!\nCode works, tests pass"]
    
    style User fill:#e1f5fe
    style Planner fill:#fff3e0
    style PlanFile fill:#f3e5f5
    style Orchestrator fill:#e8f5e9
    style Workers fill:#fce4ec
    style Done fill:#e8f5e9
{{</mermaid>}}

. This setup is powerful, because the agent does not trust itself, instead, it does the opposite. It uses *MULTIPLE* agents, in order to cross check and verify. This is... marvelous. And, in order to make my projects with a total budget of 0$, I've used open Router, though you can use anything you want.
	


