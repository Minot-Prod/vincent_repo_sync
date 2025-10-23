---
title: "Télémétrie — Schémas YAML"
owner: "Max"
last_review: "2025-10-22"
tags: ["telemetry","credit_log","learn_log"]
---
## CREDIT_LOG
```yaml
task_id: "auto-uuid-or-date"
agent: "vincent_prospection|vincent_reporting|manager"
complexity: "XS|S|M|L|XL"
time_spent_est: "minutes"
quality_self_score: 1-5
checkpoint70: "GO|NOGO|ADJUST"
notes: "points clés (non sensibles)"
```

## LEARN_LOG
```yaml
task_id: "auto-uuid-or-date"
agent: "..."
goal: "..."
context_snippet: "..."
what_worked: ["..."]
what_failed: ["..."]
user_feedback: "..."
next_idea: "..."
timestamp: "YYYY-MM-DDThh:mm"
```
