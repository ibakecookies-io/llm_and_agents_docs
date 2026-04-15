# 01. Основы LLM

Раздел для материалов, которые объясняют, **как устроены большие языковые модели**, на чем основаны их возможности и откуда берутся их ограничения.

## Что хранить в этом разделе

- базовые понятия: tokens, context window, embeddings, inference;
- архитектура Transformer на прикладном уровне;
- pretraining, instruction tuning, RLHF / preference tuning;
- reasoning, hallucinations, uncertainty;
- latency, cost, throughput и другие системные ограничения.

## Полезные будущие заметки

- `how-llms-work.md`
- `context-window-and-tokenization.md`
- `instruction-tuning-vs-base-models.md`
- `why-llms-hallucinate.md`
- `trade-offs-latency-cost-quality.md`

## Вопросы, на которые должен отвечать раздел

- Почему LLM умеют решать широкий набор задач?
- Чем отличаются base model и instruct model?
- Почему качество ответа так зависит от контекста и формулировки?
- Какие ограничения нужно учитывать в инженерной системе?

## Связанные разделы

- [Prompting](../02-prompting/index.md)
- [RAG](../03-rag/index.md)
- [Безопасность](../08-safety/index.md)
