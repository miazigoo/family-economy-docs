# 0101 Product Overview

| Field | Value |
| --- | --- |
| Status | Draft |
| Version | t1 |
| Author | Pavel + OpenAI |
| Audience | Product, Developers, Parents, Investors |
| Related documents | 0001_Manifest_t1.md, 0002_Core_Principles_t1.md, 0003_Product_Vision_t1.md, 0102_Product_Storytelling_t1.md |
| Purpose | Defines the high-level product model of Family Economy, its main modules, user roles, product boundaries, and staged feature map. |
| Last update | 2026-06-27 |

## Table of Contents

- [1. Product in one paragraph](#1-product-in-one-paragraph)
- [2. What problem the product solves](#2-what-problem-the-product-solves)
- [3. What Family Economy is not](#3-what-family-economy-is-not)
- [4. Core product idea](#4-core-product-idea)
- [5. Main users and roles](#5-main-users-and-roles)
- [6. Two-app model](#6-two-app-model)
- [7. Core loop](#7-core-loop)
- [8. Product modules](#8-product-modules)
- [9. Module maturity map](#9-module-maturity-map)
- [10. Product boundaries](#10-product-boundaries)
- [11. Safety model at product level](#11-safety-model-at-product-level)
- [12. Reward model](#12-reward-model)
- [13. Economy model](#13-economy-model)
- [14. Contract model](#14-contract-model)
- [15. Character model](#15-character-model)
- [16. Marketplace model](#16-marketplace-model)
- [17. Treasury and family government](#17-treasury-and-family-government)
- [18. Photo reports and AI helper](#18-photo-reports-and-ai-helper)
- [19. Why this product can be sold](#19-why-this-product-can-be-sold)
- [20. Summary](#20-summary)
- [Open Questions](#open-questions)

## 1. Product in one paragraph

Family Economy — это безопасная семейная платформа, где взрослые и дети создают договоренности, выполняют задачи, заключают контракты, формируют привычки, получают награды, копят на цели и учатся ответственности и финансовой грамотности через игровые механики. Продукт не только про деньги: деньги являются одним из способов показать ценность труда и обещания, но рядом с ними существуют внутренние валюты, привилегии, подарки, семейные события, признание и прогресс к цели. Главный смысл продукта — сделать семейные обещания видимыми, честными и понятными для обеих сторон.

## 2. What problem the product solves

Во многих семьях договоренности живут устно. Родитель просит помочь, ребенок соглашается, награда обещается на словах, срок звучит примерно, а потом детали теряются. Иногда ребенок не понимает, что именно считается выполнением. Иногда взрослый забывает, что пообещал. Иногда правило меняется по дороге, и ребенок воспринимает это как несправедливость.

Family Economy решает проблему видимости. Он помогает превратить устную просьбу в понятную договоренность: что нужно сделать, кто попросил, какой результат ожидается, какая награда обещана и что происходит после выполнения. Это важно не для бюрократии, а для доверия.

Ребенок не всегда видит связь между усилием, обещанием, наградой и целью. Он может хотеть велосипед, игру или подарок, но не понимать, как маленькие действия складываются в большой результат. Продукт делает эту связь видимой: задача дает награду, награда попадает в ledger или копилку, копилка приближает цель.

Родителям нужен способ мотивировать без превращения семьи в систему давления. Обычный контроль быстро вызывает сопротивление. Полная свобода тоже не всегда работает. Family Economy предлагает средний путь: договоренности, выбор, игровые персонажи, понятный прогресс и ответственность обеих сторон.

Взрослые тоже забывают обязательства. Это особенно чувствительно, когда ребенок выполнил свою часть. Продукт должен напоминать взрослым об обязательствах по выплатам и помогать закрывать обещания. Семьям нужны гибкие инструменты, а не единая родительская доктрина: одни семьи используют деньги, другие — привилегии, третьи — внутренние валюты и семейные активности.

## 3. What Family Economy is not

Family Economy не является простым приложением домашних дел. Задачи есть в продукте, но они являются входной точкой, а не всей системой. Если продукт только показывает список домашних дел, он не объясняет доверие, обещание, цель и ответственность.

Это не банковское приложение. В MVP не должно быть bank API, автоматических банковских переводов или зависимости от финансовой инфраструктуры. Реальные деньги могут учитываться как ручные обязательства, которые взрослый выполняет вне приложения и отмечает внутри системы.

Это не punishment board. Продукт не должен строиться вокруг стыда, угроз и автоматических наказаний. Известные penalties могут быть частью контракта, но только если они видны до подписания и не меняются задним числом.

Это не public social network for children. У ребенка не должно быть публичного профиля, публичного поиска, публичного чата или входящих сообщений от неизвестных взрослых. Это также не замена родительству: приложение помогает говорить яснее, но не заменяет разговор, объяснение и живую ответственность взрослых.

Family Economy не является системой, где каждое семейное действие должно монетизироваться. Помощь, забота и привычки не должны автоматически становиться платными. Продукт поддерживает разные типы наград и не навязывает деньги как единственную мотивацию. Он также не должен становиться gambling-like economy: обменные курсы и события должны контролироваться родителями и объясняться, а не создавать случайную зависимость.

## 4. Core product idea

The product is built around visible promises.

По-русски это означает: Family Economy строится вокруг видимых обещаний. Семейная договоренность перестает быть размытым устным ожиданием и становится понятной записью, которую видят участники. Видимое обещание не делает семью формальной. Оно помогает семье меньше спорить о том, что было обещано, и больше говорить о смысле договоренности.

Tasks — это краткосрочные действия: убрать комнату, прочитать страницы, пройти шаги, помочь взрослому. Contracts — это более длинные соглашения: делать зарядку 30 дней, читать две недели, копить на велосипед. Habits помогают повторять важное действие, goals дают направление, rewards делают обещание конкретным, reputation поддерживает доверие, economy учит ценности, а characters делают взаимодействие эмоциональным.

Главная идея не в том, чтобы построить сложную игру. Главная идея в том, чтобы дать семье язык для договоренностей. Когда ребенок принимает задачу или предлагает контракт, он учится понимать условия. Когда взрослый обещает награду, он тоже становится участником системы. Когда цель видна, усилия получают смысл.

## 5. Main users and roles

Parent Owner — взрослый, который создает семью, управляет базовыми настройками, профилями детей, trusted adults, персонажами, правилами наград и безопасностью. Обычно это родитель или законный представитель, который отвечает за семейную систему.

Trusted Adult — одобренный взрослый внутри семьи. Это может быть второй родитель, бабушка, дедушка или другой близкий взрослый. Trusted adult может создавать задачи или контракты только в рамках разрешений семьи. Он не получает автоматического полного доступа ко всему.

Child — ребенок, который видит задачи, принимает или выполняет их, отправляет proof, видит rewards, goals, achievements, может request exchange и propose contracts в разрешенных сценариях. Child не может получать задачи от unknown adults.

Character/Persona — не отдельный реальный пользователь, а слой представления. Один взрослый может иметь несколько персонажей: Father, Santa Claus, Robot, Wizard. Ребенок может видеть персонажа, но система должна хранить реального взрослого для аудита и безопасности. Это различие важно: персонаж добавляет эмоцию, но ответственность остается у настоящего взрослого.

## 6. Two-app model

Family Economy должен использовать two-app model: Parent App и Child App. Эти приложения обслуживают разные роли, разные уровни сложности и разные границы безопасности.

Parent App создает семью, создает child profiles, связывает child device через QR или pairing code, создает tasks, approves submissions, manages rewards, manages trusted adults, manages characters, sees treasury and statistics. Взрослый интерфейс может быть сложнее, потому что взрослый управляет правилами, обязательствами и настройками.

Child App показывает tasks, allows accepting or completing tasks, submits proof, shows goals, rewards, achievements, exchange requests and proposed contracts. Детский интерфейс должен быть проще, спокойнее и защищеннее. Он не должен показывать лишнюю административную сложность.

Не стоит объединять два приложения в одно. У взрослого и ребенка разные UX-задачи. У них разные права и разные риски. Child App должен оставаться простым и protected: без лишних настроек, без доступа к взрослым инструментам, без внешних контактов и без небезопасных сценариев.

## 7. Core loop

```text
Adult creates task or contract
→ Child sees it in Child App
→ Child accepts or completes it
→ Child submits proof if required
→ Adult approves or returns for revision
→ Reward obligation appears
→ Adult pays, grants reward, or marks fulfilled
→ Child sees progress toward goal
→ Reputation and history are updated
```

Этот цикл доказывает MVP, потому что в нем есть вся суть продукта: взрослый формулирует обещание, ребенок понимает действие, выполнение подтверждается, reward obligation становится видимой, взрослый закрывает обязательство, а ребенок видит прогресс. Если этот цикл работает понятно и безопасно, Family Economy уже решает базовую проблему.

MVP не обязан включать всю будущую экономику. Он должен доказать, что семья хочет и может использовать видимые договоренности. Если core loop не работает, любые валюты, обмены, treasury и AI будут преждевременной сложностью.

## 8. Product modules

### Tasks

Tasks — короткие действия с понятным результатом. Они существуют, чтобы семья могла быстро договориться о помощи, привычке или разовом поручении. Tasks должны быть в MVP, потому что они являются самым простым входом в продукт.

### Contracts

Contracts — более длинные соглашения с условиями, сроками и последствиями. Они существуют, чтобы ребенок учился планировать и принимать условия. Contracts лучше вводить в v1 или как очень ограниченный эксперимент, если MVP уже доказал task loop.

### Habits

Habits поддерживают повторяющиеся действия: зарядка, чтение, шаги, помощь по расписанию. Они существуют, чтобы продукт работал не только с разовыми поручениями, но и с устойчивым поведением. Простые recurring tasks могут появиться в v1, более глубокие habits — позже.

### Goals and savings

Goals and savings показывают, зачем ребенок копит или выполняет договоренности. Они существуют, чтобы связать маленькие награды с большим смыслом. Базовые savings goals нужны уже в MVP.

### Rewards

Rewards делают обещание конкретным. Это могут быть money, internal currencies, privileges, gifts, family activities, screen/game time, goal progress or recognition. Базовый reward ledger нужен в MVP, расширенные типы наград могут расти постепенно.

### Characters

Characters добавляют эмоциональный слой. Они позволяют взрослому выступать как Father, Santa Claus, Robot or Wizard. Characters лучше вводить не раньше MVP/v1 в простом виде, а более сложные свойства персонажа — позже.

### Reputation

Reputation показывает историю надежности: ребенок выполняет обещания, взрослый закрывает rewards, персонаж держит слово. Она нужна для доверия, но должна быть осторожной и не карательной. Базовая reputation уместна в v1.

### Family economy

Family economy объединяет валюты, exchange, treasury, fund and optional taxes. Она нужна для финансовой грамотности и игры, но не должна перегружать ранний продукт. Основная family economy относится к v2.

### Exchange

Exchange позволяет ребенку запросить обмен внутренней валюты по parent-controlled rate. Он учит курсу, времени и запросу. Exchange не должен быть automatic bank transfer. Он относится к v2.

### Treasury

Treasury помогает взрослым видеть obligations, payouts and pending rewards. Она нужна для прозрачности и планирования. Базовая treasury может начаться с payment tracking, расширенная — v2.

### Family government

Family government — optional educational layer: family fund, optional taxes, charity fund. Он существует для обучения shared resources, но должен быть disabled by default for younger children. Это v2+.

### Marketplaces

Marketplaces бывают task marketplace and contract marketplace, only inside family. Они дают ребенку выбор из approved options. Публичного marketplace быть не должно. Task marketplace может появиться в v2 после базовых tasks, contract marketplace — вместе с contract maturity.

### Photo reports

Photo reports помогают подтвердить выполнение. Они полезны уже в MVP как optional proof. Фото должны храниться временно и удаляться автоматически.

### AI helper

AI helper может помогать с photo check, task suggestions, contract suggestions and character text style. AI не принимает финальное решение. Это v3+, за исключением очень осторожных экспериментов после проверки safety.

### Notifications

Notifications напоминают о задачах, проверках, rewards and payment obligations. Push notifications нужны в MVP, но язык уведомлений должен помогать, а не давить.

### Safety and access control

Safety and access control определяют family linking, trusted adults, permissions, audit trail and child protection. Это не отдельная поздняя функция, а фундамент MVP.

### Statistics

Statistics показывают progress, completion, unpaid obligations and basic trends. Базовая статистика уместна в v1, более глубокая analytics — v3+.

## 9. Module maturity map

| Module | MVP | v1 | v2 | v3+ | Notes |
| --- | --- | --- | --- | --- | --- |
| Two-app model | ✅ | ✅ | ✅ | ✅ | Parent App and Child App separated. |
| Family creation | ✅ | ✅ | ✅ | ✅ | Required for safe family scope. |
| Child profile | ✅ | ✅ | ✅ | ✅ | No public child profile. |
| Device linking | ✅ | ✅ | ✅ | ✅ | QR or pairing code. |
| Simple tasks | ✅ | ✅ | ✅ | ✅ | Core MVP entry point. |
| Task submissions | ✅ | ✅ | ✅ | ✅ | With optional proof. |
| Photo reports | 🟡 | ✅ | ✅ | ✅ | Optional, temporary storage. |
| Approval/rejection | ✅ | ✅ | ✅ | ✅ | Adult final decision. |
| Reward ledger | ✅ | ✅ | ✅ | ✅ | Internal accounting. |
| Manual payment tracking | ✅ | ✅ | ✅ | ✅ | No bank API in MVP. |
| Savings goals | ✅ | ✅ | ✅ | ✅ | Basic goal progress. |
| Push notifications | ✅ | ✅ | ✅ | ✅ | Helpful, not pressure-first. |
| Contracts | ⚪ | ✅ | ✅ | ✅ | Possibly very limited experiment later. |
| Child-proposed contracts | ⚪ | ✅ | ✅ | ✅ | Inside safe family boundaries. |
| Trusted adults | 🟡 | ✅ | ✅ | ✅ | Basic approval in MVP if needed. |
| Characters | 🟡 | ✅ | ✅ | ✅ | Simple personas first. |
| Reputation | ⚪ | ✅ | ✅ | ✅ | Must not become punishment board. |
| Recurring tasks | ⚪ | ✅ | ✅ | ✅ | Habit support. |
| Family economy | ⚪ | ⚪ | ✅ | ✅ | Advanced mode. |
| Currencies | 🟡 | 🟡 | ✅ | ✅ | Simple internal ledger first. |
| Exchange | ⚪ | ⚪ | ✅ | ✅ | Parent-approved requests. |
| Treasury | 🟡 | 🟡 | ✅ | ✅ | Starts as obligations tracking. |
| Family government | ⚪ | ⚪ | 🟡 | ✅ | Optional educational layer. |
| AI photo helper | ⚪ | ⚪ | ⚪ | ✅ | Helper only, not judge. |
| AI suggestions | ⚪ | ⚪ | ⚪ | ✅ | Suggestions for adults. |
| Bank integration | ⚪ | ⚪ | ⚪ | 🔒 | Future/frozen, not MVP. |
| Smart watches | ⚪ | ⚪ | ⚪ | 🔒 | Future integration. |

## 10. Product boundaries

Family Economy has hard boundaries. There is no public child discovery. There are no unknown adult messages. There is no public marketplace, no public chat and no external marketplace for children. Child-facing offers must come only from trusted adults or approved flows inside the family.

AI cannot make final decisions about children. It may suggest, summarize or help, but adult approval remains required. Contract penalties cannot be hidden. They cannot be changed after signing without transparent new agreement. No automatic bank dependence belongs in MVP.

Child photos cannot be stored forever. Photo reports must support temporary storage, retention settings and auto-deletion. Exchange rates must not behave like gambling by default. If rates change, they must be parent-controlled and explainable.

## 11. Safety model at product level

Safety starts at the product level before technical architecture. A child is linked to a family only through parent-approved pairing. Adults must be invited or approved. Trusted adult access must be explicit, limited and visible to the family.

Actions should be auditable. If a task is created by Santa Claus, the system still stores which adult created it. If a reward is promised, approved or marked paid, the system should keep a clear history. This supports trust without exposing children to external users.

Child-facing identity may be a character, but the real author is stored for audit and safety. Photos expire. Sensitive features should be off by default, especially for younger children. Safety is designed into the product, not added later as a patch.

## 12. Reward model

Rewards include real money, internal currencies, privileges, gifts, family activities, extra screen/game time, goal progress and recognition. This variety is essential because not every family wants to pay money for every action.

Reward obligation appears when the child completes agreed conditions and the adult approves. The reward can then become paid, fulfilled or still pending. If it is pending, the child may have a respectful reminder flow. This is not meant to pressure adults publicly; it is meant to preserve fairness.

Adult responsibility is part of the reward model. If an adult promised something, the adult should fulfill it. Paid/fulfilled status helps the family see what is still open. Not all rewards are money, but every promised reward should be clear.

## 13. Economy model

The family can define currencies. A currency may be general for the family or specific to a character. Santa Claus may use снежинки, Robot may use энергоядра, Wizard may use кристаллы. These currencies can support game feeling and financial literacy without requiring real money.

Exchange rate can be fixed, scheduled variable or event-based. In all cases it must be parent-controlled and understandable. A child may request exchange, and an adult approves it. Approval may lead to manual payment outside the app, but MVP should not depend on bank API.

The economy model must avoid random gambling-like defaults. The point is not to make the child chase unpredictable gains. The point is to teach value, exchange, timing, request flow and consequences inside safe family boundaries.

## 14. Contract model

A contract is longer than a task. It has visible conditions, a timeframe, a reward and possibly known penalties. A contract can be proposed by an adult or by a child. This is important because child-proposed contracts teach negotiation and initiative.

Conditions are visible before signing. Penalties are known before signing. Changes require transparency and, where needed, a new agreement. A contract can be linked to a goal, such as a bicycle or another savings target. Completion creates a reward obligation.

The contract model should not become a legalistic burden. It should remain understandable to families and children. The goal is not formal paperwork, but honest agreement.

Detailed contract rules are defined in [0301_Tasks_vs_Contracts_t1.md](../03_Contracts_Bible/0301_Tasks_vs_Contracts_t1.md).

## 15. Character model

A character or persona is a слой представления. It changes tone, emotion and style, but not real responsibility. One adult may have multiple characters: Father, Santa Claus, Robot, Wizard. A character can have tone, style, currency, generosity and rarity.

Characters improve emotion and engagement. A boring task can become a mission. A health habit can sound like a robot challenge. A non-money reward can feel magical. This matters because children respond to story and meaning.

The real adult must always be stored for audit and safety. If a character creates a task, the system knows which adult stands behind it. This prevents unsafe ambiguity and keeps family trust intact.

## 16. Marketplace model

Task marketplace is for short-term tasks inside the family. Contract marketplace is for longer agreements inside the family. Both exist only inside family boundaries. Only trusted adults or approved flows can create offers.

The child can choose from available options. Choice is important: it turns a command list into a set of opportunities. A child may prefer a reading task today and a movement task tomorrow. That choice supports participation.

There is no public marketplace. There are no external adult offers. There is no child-to-child marketplace outside the family. Marketplace means family catalog, not public economy.

## 17. Treasury and family government

Treasury helps adults track obligations, payouts and pending rewards. It shows what was promised, what was fulfilled and what still needs attention. It is not for shame. It is for planning and transparency.

Family government is an optional educational layer. It may include family fund, optional taxes and charity fund. For example, a small percentage of exchange can go to a shared goal or a charity fund. This can teach shared resources, budget and collective responsibility.

For younger children, family government should be disabled by default. It should be introduced only when the family wants that educational complexity and can explain it clearly.

## 18. Photo reports and AI helper

Photo report helps prove completion when visual proof is useful. The child submits a photo, the adult reviews it and decides whether to approve or return for revision. Photo reports must remain optional and age-appropriate.

AI can suggest but not judge. AI photo helper may say that a room appears clean with some confidence, but the parent decides. AI task suggestions and contract suggestions should help adults write better tasks, not create obligations automatically for children.

Photos are temporary. Product must support retention settings and auto-deletion. The product should collect less, store less and expose less, especially when child images are involved.

## 19. Why this product can be sold

Parents want less conflict and more self-motivation. They want children to understand responsibility without turning every evening into a negotiation or argument. Family Economy gives a concrete way to make expectations visible and rewards fair.

Children like game-like progress. They respond to characters, goals, achievements and visible movement toward something they want. The product can make ordinary family responsibilities feel more understandable and less arbitrary.

Families need flexible reward systems. Some use money, some use privileges, some use family events, some use recognition. Family Economy can start simple and grow with the child. Open documentation increases trust because parents, developers, educators and investors can see why decisions are made.

The product is differentiated from обычных приложений домашних дел because it is not only a task list. It combines agreements, roles, rewards, goals, trust, safety and education. Strong safety positioning is also commercial value: families need to know that children are not exposed to unknown adults or public systems.

## 20. Summary

Family Economy is a modular product about trust, responsibility, goals and value. Tasks are only the entry point. The deeper product is a safe family operating system for visible promises.

Tasks are the entry point. Trust is the product.

Это означает, что продукт не должен измеряться только количеством созданных задач. Настоящая ценность появляется тогда, когда ребенок понимает обещание, взрослый держит слово, семья видит прогресс, а деньги остаются только одним из языков ценности. Если Family Economy сохранит безопасность, модульность и уважение к семье, он сможет расти от простого MVP до полноценной платформы семейных договоренностей.

## Open Questions

- Which modules must be included in the first private alpha?
- Should MVP contain only tasks or also a very small version of contracts?
- Which reward types should be enabled by default?
- Should character/persona mode be enabled in MVP or introduced in v1?
- How should the app explain manual payment tracking without bank integration?
- Which product modules should be completely hidden for younger children?
- What should be the minimum viable version of family economy?
