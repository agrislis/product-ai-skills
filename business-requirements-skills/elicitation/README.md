# Requirements Elicitation Pipeline

End-to-end pipeline for collecting and processing business requirements.

```
questions-for-client → answer-analyzer → task-formulator → business-analyst
         ↑________________ requirements-orchestrator ________________↑
```

## Skills

| Skill | Purpose |
|-------|---------|
| `questions-for-client` | Generate structured interview questions for stakeholders |
| `answer-analyzer` | Analyze stakeholder answers, coverage, gaps and contradictions |
| `task-formulator` | Formulate a short prompt for the business-analyst skill |
| `business-analyst` | Produce a full business analysis document |
| `requirements-orchestrator` | Orchestrate the full pipeline and keep context between steps |
