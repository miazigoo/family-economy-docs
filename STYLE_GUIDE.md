# STYLE_GUIDE

## Заголовки

Используйте один заголовок первого уровня для названия документа.

Структура заголовков должна быть последовательной:

```markdown
# Название
## Раздел
### Подраздел
```

## Таблицы

Таблицы применяются для сравнения, статусов, атрибутов и перечней с несколькими полями.

```markdown
| Поле | Значение |
| --- | --- |
| Status | Draft |
```

## Списки

Используйте маркированные списки для равнозначных пунктов.

Используйте нумерованные списки только для последовательных шагов.

## Примеры

Примеры должны быть короткими и относиться только к описываемому правилу.

```markdown
Version: t1
```

## Цитаты

Цитаты используются только для внешних или зафиксированных формулировок.

```markdown
> Текст цитаты.
```

## Блок метаданных

Каждый документ должен начинаться с блока метаданных из шаблона.

```markdown
# Title

| Field | Value |
| --- | --- |
| Status | Draft |
| Version | t1 |
```

## Использование иконок

Иконки не используются в обязательной структуре документации.

Если иконки необходимы, они должны быть функциональными и единообразными.

## Форматирование

- Используйте пустую строку между разделами.
- Используйте кодовые блоки для шаблонов, команд и примеров именования.
- Используйте относительные ссылки внутри репозитория.
- Не используйте оформление, которое не добавляет смысла.

## Product Story Examples

Product stories should make abstract mechanics easy to understand.

Use this structure:

### Context

What is happening in the family.

### Child App

A short `text` block that imitates what the child may see.

### Parent App

A short `text` block that imitates what the parent may see.

### Why it matters

Explain the value:

- emotional value;
- educational value;
- safety value;
- product value.

Rules:

- examples must be concrete;
- examples must not introduce unsafe mechanics;
- examples must not show unknown adults contacting children;
- examples must not show public child discovery;
- examples must not make AI the final judge;
- examples must not make exchange rates feel like gambling;
- examples should be reusable for marketing, onboarding, and product specs.

## Языковая политика

Исходный язык документации — русский.

Правила:

- Писать продуктовую документацию на русском.
- Использовать понятные русские термины из глоссария.
- Избегать смешанных русско-английских предложений.
- Оставлять устойчивые технические labels там, где они понятнее как есть.
- Пользовательские примеры должны быть на русском.
- Будущие переводы должны основываться на утвержденных русских документах.
- Не создавать многоязычную структуру документации или сайт документации без отдельной задачи.

Связанные документы:

- [0902_Russian_First_Documentation_Rules_t1.md](docs/09_Codex_Bible/0902_Russian_First_Documentation_Rules_t1.md)
- [1401_Terminology_Glossary_t1.md](docs/14_Research/1401_Terminology_Glossary_t1.md)
