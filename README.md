# Project Family Economy Documentation

Профессиональный репозиторий документации проекта Family Economy.

Этот репозиторий содержит только инфраструктуру документации: структуру разделов, правила оформления, шаблоны и служебные файлы.

## Open Source Documentation

This repository contains open-source documentation for Project Family Economy.

The goal of open documentation is to:

- share product thinking openly;
- make the philosophy of the product transparent;
- collect feedback from parents, developers, educators, and investors;
- document why product decisions were made.

Important: this repository contains documentation only. Application source code may live in a separate private repository and may use a different license.

## Философия документации

Документация должна быть точной, проверяемой и минимальной.

Документы создаются только при наличии конкретной цели, аудитории и статуса. Репозиторий не используется для генерации идей, расширения продуктовой логики или хранения неутвержденных предположений вне предназначенных для этого разделов.

## Структура репозитория

```text
/docs
  00_Vision
  01_Product_Bible
  02_Economy_Bible
  03_Contracts_Bible
  04_Characters
  05_Parent_App
  06_Child_App
  07_AI
  08_Technical_Bible
  09_Codex_Bible
  10_Business_Bible
  11_Parent_Guide
  12_Investor_Pack
  13_Roadmap
  14_Research
  15_RFC
  16_ADR
  99_Frozen_Ideas
```

## Статусы документации

| Статус | Значение |
| --- | --- |
| Draft | Черновик. Документ находится в подготовке. |
| Review | Документ находится на проверке. |
| Approved | Документ утвержден и считается актуальным. |
| Deprecated | Документ устарел и не должен использоваться как источник актуальных решений. |

## Правила версионирования документов

Версия документа указывается в метаданных и изменяется при значимом обновлении содержания.

Используется формат:

```text
Version: t1
Version: t2
Version: t3
```

`t1` означает первую рабочую версию документа. Последующие версии получают следующий номер.

## Правила именования

Имена файлов должны быть последовательными, читаемыми и стабильными.

Формат:

```text
NNNN_Document_Name_tX.md
```

Примеры:

```text
0001_Project_Mission_t1.md
0002_Core_Principles_t1.md
```
