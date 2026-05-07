# HermesFlow AI

HermesFlow AI is a prototype multi-agent smartphone optimization assistant built for a Xiaomi/Android workflow.

## Core Problem
Smartphone users often waste time manually cleaning storage, checking battery settings, searching files, and summarizing notifications. HermesFlow AI automates those repetitive tasks through an agent-based workflow.

## Agent Workflow
1. Planner Agent - understands the user request and decomposes tasks.
2. Cleanup Agent - finds cache, temporary files, and duplicate media candidates.
3. Notification Agent - summarizes unread notifications.
4. Battery Agent - checks power usage and recommends optimizations.
5. Search Agent - finds photos/files with semantic-search style logic.
6. Validator Agent - reviews actions before execution.

## Demo
```bash
python run_hermesflow.py
```

## Demo Metrics
- Storage cleaned: 2.45 GB
- Notifications summarized: 34
- Photos found: 128
- Battery improvement: 22%
- Average response time: 1.8s
