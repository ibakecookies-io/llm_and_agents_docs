# 04. Агенты

Раздел посвящен агентам как системам, где модель не только отвечает, но и **планирует действия, вызывает инструменты, читает состояние среды и продолжает цикл выполнения**.

## Что хранить в этом разделе

- что такое агент и чем он отличается от обычного чат-интерфейса;
- tool calling, function calling, action selection;
- planning, reflection, memory, retry loops;
- управление состоянием и контекстом агента;
- human-in-the-loop и escalation patterns.

## Полезные будущие заметки

- `what-makes-a-system-an-agent.md`
- `tool-calling-patterns.md`
- `planning-vs-reactive-agents.md`
- `agent-memory-types.md`
- `human-in-the-loop-patterns.md`

## Вопросы раздела

- Когда действительно нужен агент, а когда достаточно workflow?
- Как проектировать цикл "наблюдение -> решение -> действие -> проверка"?
- Как ограничивать область действий агента?
- Какие ошибки чаще всего ломают агентные сценарии?

## Связанные разделы

- [RAG](../03-rag/index.md)
- [Агентские архитектуры](../05-agent-architectures/index.md)
- [Безопасность](../08-safety/index.md)
