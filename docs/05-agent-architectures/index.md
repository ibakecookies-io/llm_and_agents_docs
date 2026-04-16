# 05. Агентские архитектуры

Раздел про проектирование систем, в которых один или несколько агентов решают задачу совместно с инструментами, данными и управляющей логикой.

## Материалы

- [Multi-agent coordination patterns](https://claude.com/blog/multi-agent-coordination-patterns), Claude Blog.

## Что хранить в этом разделе

- single-agent, supervisor, planner-executor, router и multi-agent схемы;
- orchestration vs autonomy;
- state machines, DAG / graph-based execution;
- delegation, coordination, shared memory, message passing;
- критерии выбора архитектуры под тип задачи.

## Полезные будущие заметки

- `single-agent-vs-multi-agent.md`
- `planner-executor-pattern.md`
- `supervisor-architecture.md`
- `graph-based-agent-orchestration.md`
- `architecture-selection-guide.md`

## Вопросы раздела

- Когда один агент лучше нескольких?
- Как не превратить multi-agent систему в неоправданную сложность?
- Где проводить границу между workflow-движком и агентной автономией?
- Как проектировать деградацию и fallback-механизмы?

## Связанные разделы

- [Агенты](../04-agents/index.md)
- [Оценка качества](../06-evaluation/index.md)
- [Наблюдаемость](../07-observability/index.md)
