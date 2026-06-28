# 0902 Правила документации на русском языке

| Field | Value |
| --- | --- |
| Status | Draft |
| Version | t1 |
| Author | Pavel + OpenAI |
| Audience | Codex, Developers, Product |
| Related documents | 0901_Codex_Rules_t1.md, STYLE_GUIDE.md, 1401_Terminology_Glossary_t1.md |
| Purpose | Defines Russian-first writing rules for all future documentation and explains how translations and documentation website should be handled later. |
| Last update | 2026-06-27 |

## Оглавление

- [1. Основное правило](#1-основное-правило)
- [2. Почему сначала русский](#2-почему-сначала-русский)
- [3. Что может оставаться на английском](#3-что-может-оставаться-на-английском)
- [4. Что нужно переводить на русский](#4-что-нужно-переводить-на-русский)
- [5. Заголовки](#5-заголовки)
- [6. Метаданные](#6-метаданные)
- [7. Примеры и UI-текст](#7-примеры-и-ui-текст)
- [8. Продуктовые термины](#8-продуктовые-термины)
- [9. Технические термины](#9-технические-термины)
- [10. Будущие переводы](#10-будущие-переводы)
- [11. Будущий сайт документации](#11-будущий-сайт-документации)
- [12. Правила для Codex](#12-правила-для-codex)
- [Открытые вопросы](#открытые-вопросы)

## 1. Основное правило

Основной язык документации — русский.

Документация должна читаться без знания английского языка, кроме устойчивых технических названий и продуктовых labels, которые понятнее оставить как есть.

## 2. Почему сначала русский

Павел работает и продумывает продукт на русском языке. Документация используется для продуктовых решений, задач Codex, архитектуры и будущей разработки. Поэтому ясность на русском важнее, чем внешний стиль, похожий на англоязычный startup-документ.

Чем яснее исходный русский текст, тем проще будет переводить его позже. Перевод должен идти от понятного источника, а не от смеси английских и русских формулировок.

## 3. Что может оставаться на английском

Можно оставлять на английском устойчивые технические или проектные labels:

- `README`;
- `CHANGELOG`;
- `MVP`;
- `API`;
- `RFC`;
- `ADR`;
- `Git`;
- `GitHub`;
- `FastAPI`;
- `Kotlin`;
- `Parent App`;
- `Child App`;
- `Codex`;
- `Open Source`;
- имена файлов;
- commit messages.

## 4. Что нужно переводить на русский

| Avoid | Prefer |
| --- | --- |
| task | задача |
| contract | контракт |
| habit | привычка |
| goal | цель |
| reward | награда |
| reward obligation | обязательство по награде |
| proof | подтверждение |
| submission | отправка результата |
| approval | подтверждение взрослым |
| rejection | отклонение |
| returned for revision | возвращено на доработку |
| marketplace | рынок / семейный рынок |
| treasury | Казначейство |
| family fund | Семейный фонд |
| charity fund | Благотворительный фонд |
| exchange | обмен / Биржа |
| exchange rate | курс обмена |
| ledger | журнал операций |
| balance | баланс |
| parent-controlled | контролируется родителями |
| gambling-like | похожий на азартную механику |
| public market | публичный рынок |
| trusted adult | доверенный взрослый |
| unknown adult | неизвестный взрослый |
| presentation layer | слой представления |
| audit | аудит |
| payer | плательщик |
| fulfilled | исполнено |

## 5. Заголовки

Новые документы должны предпочитать русские заголовки разделов.

Допустимо сохранять английские заголовки в уже созданных документах ради стабильности anchors и cross-links. Новые документы должны использовать русские заголовки, если задача явно не требует английский текст заголовков.

Предпочтительно:

```md
## 1. Что такое персонаж
```

Избегать:

```md
## 1. Character in one paragraph
```

## 6. Метаданные

Ключи метаданных могут оставаться на английском для единообразия:

```md
Status
Version
Author
Audience
Related documents
Purpose
Last update
```

Значения metadata должны быть понятными. `Purpose` в новых документах может быть на русском.

## 7. Примеры и UI-текст

Все пользовательские примеры должны быть на русском.

Хорошо:

```text
🎅 Дед Мороз

Хо-хо-хо!

Сегодня у меня есть особое задание.
```

Не нужно смешивать языки в UI-примерах, кроме технических labels.

## 8. Продуктовые термины

- `Family Economy` — рабочее название проекта.
- `Parent App` — приложение для родителей.
- `Child App` — приложение для ребенка.
- `задача` — короткое действие.
- `контракт` — долгосрочная договоренность.
- `привычка` — повторяемое поведение.
- `цель` — то, ради чего ребенок копит или выполняет условия.
- `персонаж / роль` — образ, через который взрослый обращается к ребенку.
- `Казначейство` — родительский учет обязательств и выплат.
- `Биржа` — семейный механизм запроса обмена.
- `Семейный фонд` — общий фонд семьи.
- `Государство семьи` — опциональный обучающий слой правил.

## 9. Технические термины

Технические термины могут оставаться английскими, если они общеприняты и так понятнее:

- API;
- backend;
- frontend;
- commit;
- branch;
- pull request;
- deploy;
- FastAPI;
- Kotlin;
- PostgreSQL;
- Redis.

В product-facing документах не нужно злоупотреблять английским, если есть понятный русский термин.

## 10. Будущие переводы

Текущий source of truth — русская документация. Английский перевод может быть добавлен позже. Перевод не должен управлять продуктовыми решениями.

Перевод должен сохранять философию и смысл, а не буквально копировать структуру каждого предложения.

Возможная будущая структура:

```text
docs/ru/...
docs/en/...
```

Эту структуру сейчас создавать не нужно.

## 11. Будущий сайт документации

Документационный сайт планируется после MVP-приложений. Сайт может поддерживать выбор языка и разные представления для родителей, инвесторов, разработчиков и product-команды.

Сайт должен строиться на основе approved docs. Он не является частью текущей фазы документации. Код сайта сейчас создавать нельзя.

Потенциальное будущее направление:

```text
docs source
→ documentation website
→ language switcher
→ parent/investor/developer views
```

## 12. Правила для Codex

- Write new documentation in Russian by default.
- Do not use English headings unless explicitly instructed.
- Do not mix English and Russian in product explanations if a Russian term exists.
- Keep stable product labels like `Parent App`, `Child App`, `MVP`, `API`.
- Use the glossary before inventing terms.
- If unsure, add a TODO or Open Question.
- Do not create multilingual site structure unless explicitly instructed.
- Do not translate docs automatically unless asked.

## Открытые вопросы

- Should future file names remain English for GitHub readability?
- Should headings in existing documents be translated to Russian in a separate cleanup pass?
- Should the future website use `docs/ru` and `docs/en` structure or separate translation files?
- Which product terms should remain as brand-like English labels?
