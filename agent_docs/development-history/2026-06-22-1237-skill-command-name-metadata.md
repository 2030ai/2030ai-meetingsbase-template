# [2026-06-22 12:37] Skill command-name metadata

Файл: `agent_docs/development-history/2026-06-22-1237-skill-command-name-metadata.md`

## Что сделано

- Skills `/meeting-agenda`, `/meeting-followup`, `/meeting-notes` приведены к единой metadata-схеме.
- Первый H1 в каждом `SKILL.md` приведён к `# /command`.
- Добавлены `agents/openai.yaml` с `display_name: "/command"`.

## Зачем

Чтобы названия skills в UI совпадали с командами meeting-шаблона.

## Обновлено

- [ ] agent_docs/architecture.md (не применимо)
- [ ] agent_docs/adr/YYYY-MM-DD-HHMM-title.md (не применимо)
- [ ] Тесты (не применимо, metadata-only)
- [x] Документация

## Связанные решения

- Не применимо.

## Следующие шаги

- При добавлении новых meeting skills сразу задавать `agents/openai.yaml display_name` в формате `/command`.
