# Requirements Elicitation Pipeline

> 🇷🇺 Описание на русском доступно ниже / Russian description is available below

End-to-end pipeline for collecting and processing business requirements.

```
questions-for-client → answer-analyzer → task-formulator → business-analyst
         ↑________________ requirements-orchestrator ________________↑
```

## Skills

| Skill | Purpose |
|-------|---------|
| [`questions-for-client`](questions-for-client/) | Generate structured interview questions for stakeholders |
| [`answer-analyzer`](answer-analyzer/) | Analyze stakeholder answers, coverage, gaps and contradictions |
| [`task-formulator`](task-formulator/) | Formulate a short prompt for the business-analyst skill |
| [`business-analyst`](business-analyst/) | Produce a full business analysis document |
| [`requirements-orchestrator`](requirements-orchestrator/) | Orchestrate the full pipeline and keep context between steps |

---

## Описание на русском

Полный конвейер сбора и обработки бизнес-требований.

```
questions-for-client → answer-analyzer → task-formulator → business-analyst
         ↑________________ requirements-orchestrator ________________↑
```

## Навыки

| Навык | Назначение |
|-------|---------|
| [`questions-for-client`](questions-for-client/) | Генерация структурированных вопросов для интервью со стейкхолдерами |
| [`answer-analyzer`](answer-analyzer/) | Анализ ответов стейкхолдеров, покрытия, пробелов и противоречий |
| [`task-formulator`](task-formulator/) | Формулировка короткого промпта для навыка business-analyst |
| [`business-analyst`](business-analyst/) | Формирование полного документа бизнес-анализа |
| [`requirements-orchestrator`](requirements-orchestrator/) | Оркестрация полного конвейера и сохранение контекста между шагами |
