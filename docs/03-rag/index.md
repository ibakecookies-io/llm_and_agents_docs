# 03. RAG и работа с контекстом

Раздел для материалов про retrieval-augmented generation и в целом про подключение внешних знаний к LLM.

## Что хранить в этом разделе

- когда нужен RAG, а когда достаточно промпта;
- indexing, chunking, embeddings, reranking;
- retrieval pipelines и query transformation;
- контекстное сжатие, memory stores, knowledge bases;
- оценка качества retrieval и grounded generation.

## Полезные будущие заметки

- `when-to-use-rag.md`
- `chunking-strategies.md`
- `retrieval-pipeline-design.md`
- `reranking-and-context-selection.md`
- `common-rag-failure-modes.md`

## Ключевые вопросы

- Какой источник знаний должен использовать агент или LLM-система?
- Как выбирать chunk size, overlap и способ индексации?
- Почему retrieval может ухудшить ответ, а не улучшить его?
- Как проверять, что ответ действительно grounded в источниках?

## Связанные разделы

- [Prompting](../02-prompting/index.md)
- [Агенты](../04-agents/index.md)
- [Оценка качества](../06-evaluation/index.md)
