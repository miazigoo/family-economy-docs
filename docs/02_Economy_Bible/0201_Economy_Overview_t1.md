# 0201 Economy Overview

| Field | Value |
| --- | --- |
| Status | Draft |
| Version | t1 |
| Author | Pavel + OpenAI |
| Audience | Product, Developers, Parents, Investors |
| Related documents | 0001_Manifest_t1.md, 0002_Core_Principles_t1.md, 0003_Product_Vision_t1.md, 0101_Product_Overview_t1.md, 0102_Product_Storytelling_t1.md, 0301_Tasks_vs_Contracts_t1.md |
| Purpose | Defines the family economy model, currencies, exchange, treasury, family government, optional taxes, charity, and safe financial literacy mechanics. |
| Last update | 2026-06-27 |

## Table of Contents

- [1. Economy in one paragraph](#1-economy-in-one-paragraph)
- [2. Why the economy exists](#2-why-the-economy-exists)
- [3. What the economy is not](#3-what-the-economy-is-not)
- [4. Core concepts](#4-core-concepts)
- [5. Real money vs internal value](#5-real-money-vs-internal-value)
- [6. Internal currencies](#6-internal-currencies)
- [7. Character-specific economies](#7-character-specific-economies)
- [8. Exchange model](#8-exchange-model)
- [9. Exchange rate types](#9-exchange-rate-types)
- [10. Child exchange request flow](#10-child-exchange-request-flow)
- [11. Parent approval and manual fulfillment](#11-parent-approval-and-manual-fulfillment)
- [12. Ledger and balances](#12-ledger-and-balances)
- [13. Savings goals](#13-savings-goals)
- [14. Non-money rewards](#14-non-money-rewards)
- [15. Treasury](#15-treasury)
- [16. Family government](#16-family-government)
- [17. Family fund](#17-family-fund)
- [18. Optional taxes](#18-optional-taxes)
- [19. Charity fund](#19-charity-fund)
- [20. Graphs and financial literacy](#20-graphs-and-financial-literacy)
- [21. Age-appropriate complexity](#21-age-appropriate-complexity)
- [22. MVP vs future scope](#22-mvp-vs-future-scope)
- [23. Product examples](#23-product-examples)
- [24. Product rules](#24-product-rules)
- [Open Questions](#open-questions)

## 1. Economy in one paragraph

Family Economy использует контролируемый семейный экономический слой, чтобы дети могли понимать ценность, накопление, обмен, обязательства, цели, общие ресурсы и разные типы наград на реальных семейных ситуациях. Деньги являются только одним типом награды. Рядом с ними могут существовать внутренние валюты, привилегии, подарки, семейные события, признание и прогресс к целям. Обмен должен подтверждаться взрослыми, правила должны контролироваться родителями, а вся экономика должна оставаться безопасной, семейной, объяснимой и соответствующей возрасту ребенка.

## 2. Why the economy exists

Экономика в Family Economy существует не для того, чтобы превратить семью в рынок. Она существует как образовательная система. Детям трудно понять ценность через абстрактные лекции. Слова о деньгах, труде, накоплении и бюджете остаются слишком общими, пока ребенок не видит связь между своим действием, обещанием взрослого, наградой и целью.

Реальные семейные задачи делают финансовую грамотность конкретной. Если ребенок помог, выполнил задачу, завершил контракт или накопил внутреннюю валюту, он видит, что ценность появляется не из воздуха. Она связана с усилием, временем, договоренностью и доверием. Это более естественный способ обучения, чем объяснение экономики отдельно от жизни.

Валюты и обмен помогают понять ценность. Когда ребенок видит, что 80 снежинок можно обменять на 10 ₽ при курсе 8 снежинок за 1 ₽, он учится считать, сравнивать и выбирать. Если курс меняется по расписанию или из-за понятного события, ребенок может увидеть, что ценность зависит от правил и контекста. Но это должно быть безопасно и объяснимо, без случайных азартных циклов.

Цели учат накоплению. Накопительная цель превращает маленькую награду в путь: велосипед, книга, игра, семейная поездка или благотворительная цель. Ребенок видит прогресс, учится ждать и понимает, что не каждое желание закрывается мгновенно.

Казначейство учит видеть обязательства. Если взрослые обещают награды, эти обязательства должны быть видимыми. Казначейство помогает родителям видеть, что уже выдано, что ожидает выплаты, какие обмены нужно закрыть и кто является плательщиком. Это поддерживает доверие, потому что экономика работает в обе стороны.

Семейный фонд учит видеть общие ресурсы. Он помогает объяснить, что ресурсы могут быть не только личными, но и общими. Благотворительность помогает понять социальную ценность: часть ресурсов может идти на благотворительную цель, если семья решила это осознанно. Экономика должна поддерживать разговор, а не заменять его. Взрослые все равно объясняют правила, смысл и границы.

## 3. What the economy is not

Экономика Family Economy не является банком. В MVP не должно быть банковского API, автоматических банковских переводов, реальных банковских счетов или зависимости от финансовой инфраструктуры. Реальные переводы происходят вручную вне приложения, а приложение отслеживает обязательства и их исполнение.

Это не азартная система. Нельзя строить мотивацию ребенка на случайных шансах, непредсказуемых наградах, скрытых вероятностях или постоянном ожидании удачного курса. Курсы обмена могут меняться, но изменения должны контролироваться родителями, быть запланированными или связанными с понятным событием.

Это не cryptocurrency. Внутренние валюты не должны выглядеть как публичные токены, инвестиции или спекулятивные активы. Они существуют только внутри семьи как образовательный и игровой инструмент.

Это не публичный рынок. У ребенка не должно быть доступа к публичным рынкам, неизвестным взрослым, внешним предложениям или публичной торговле. Все экономические действия происходят внутри семьи и под контролем trusted adults.

Это не способ монетизировать каждое семейное действие. Помощь, забота, привычки и участие не должны автоматически превращаться в оплату. Экономика должна поддерживать ценность, а не уничтожать благодарность и семейное чувство.

Это не способ давить на детей. Графики, балансы, курсы, фонды и налоги не должны превращаться в тревожный интерфейс. Для младших детей сложные элементы должны быть выключены или скрыты. В MVP нет автоматической системы реальных денежных переводов: приложение отслеживает обязательства и их исполнение, а взрослые вручную выполняют реальные переводы при необходимости.

## 4. Core concepts

Currency — единица ценности внутри семьи. Это могут быть рубли как реальная награда, снежинки как внутренняя валюта, энергоядра для активности или кристаллы для привилегий.

Balance — текущий видимый остаток ценности у ребенка или в семейном фонде. Баланс должен объясняться через ledger, а не меняться молча.

Ledger — история событий экономики. Он показывает, что было earned, spent, exchanged, adjusted, expired or moved to goal. Ledger is product-level concept here, not database schema.

Reward — обещанный результат за задачу, контракт, привычку или другое семейное действие. Reward can be money, internal currency, privilege, gift, family activity, recognition or goal progress.

Reward obligation — обязательство плательщика после approved completion. Если ребенок выполнил условия, взрослый или назначенный payer должен выполнить обещанную награду или отметить fulfillment.

Exchange rate — правило обмена одной ценности на другую. Например, 10 снежинок = 1 ₽.

Exchange request — запрос ребенка на обмен. Он не должен автоматически запускать банковский перевод. Взрослый получает запрос, approves, rejects or discusses.

Treasury — parent-facing overview of obligations, payouts, pending exchanges and currency totals. Казначейство помогает взрослым видеть экономику семьи.

Family fund — общий семейный фонд для shared goals. Он может получать manual contributions or optional parts of exchanges.

Optional tax — образовательное семейное правило, где небольшой видимый процент идет в family fund or charity fund. It must be optional, visible and parent-controlled.

Charity fund — optional goal for social value. It can represent a family-controlled charitable intention; no external donation processing in MVP.

Goal — цель, к которой направляются награды или накопления: bicycle, book, game, family trip, animal shelter food.

## 5. Real money vs internal value

Real money can be tracked as obligation. Если взрослый обещает 100 ₽ за задачу, приложение фиксирует reward obligation. После выполнения взрослый переводит деньги вручную вне приложения или выдает наличными, затем marks fulfilled in Parent App.

Internal currencies are educational and game currencies. Они помогают ребенку видеть прогресс, копить, выбирать и обменивать без необходимости каждый раз использовать реальные деньги. Внутренняя валюта может быть полностью игровой или иметь правило обмена на рубли, если родители это включили.

Privileges and family events are also value. 30 минут игры, семейный кино-вечер, любимая пицца, поход в парк или признание результата могут быть более подходящими наградами, чем деньги. Для некоторых семей это основной режим.

Not every internal currency must convert to money. Some currencies can be exchangeable. Some can be spend-only. Some can be symbolic. Снежинки могут convert to rubles. Кристаллы могут buy privileges but not rubles. Энергоядра могут reward activity and support health habits without becoming money.

This distinction protects the product from reducing everything to cash. A family can choose that rubles are rare, снежинки are exchangeable, кристаллы are only for privileges, and recognition is used for habits. The product should support this variety without implying that every point is money.

## 6. Internal currencies

A family can define currencies. Each currency should have name, icon, meaning and rules. Name helps child understand the story. Icon makes the currency visible. Meaning explains why it exists. Rules define how it is earned, spent, exchanged or disabled.

Currency can be connected to character. Santa Claus may give снежинки. Robot may give энергоядра. Wizard may give кристаллы. Father may pay directly in rubles. Character-specific currencies help the economy feel like part of a family story, not an accounting table.

Currency can be connected to reward type. A family may define a currency for reading, another for activity, another for kindness or shared goals. This should be used carefully. Too many currencies can overwhelm children and parents. The default should be simple.

Currency can be disabled. If the family does not want exchange or internal points, the product should still work with tasks, rewards and goals. Parent controls currency rules. Child should not be able to create new currencies or change exchange settings.

Examples:

```text
🎅 Снежинки
10 снежинок = 1 ₽

🤖 Энергоядра
Used for activity missions

🧙 Кристаллы
Can be spent on privileges, not exchanged for rubles
```

## 7. Character-specific economies

Each character may have its own economy. This does not mean each character is a real independent payer. Character is presentation layer. The real adult remains responsible and must be stored for audit and safety.

Santa may be generous but rare. He can give larger seasonal rewards, special снежинки or holiday missions. Robot may give small frequent rewards for activity missions, steps or habits. Wizard may give non-money currency that can buy privileges, family events or playful rewards. Father may pay in rubles directly when directness is better than fantasy.

Character economy should support story and engagement. A child may feel that Robot missions are about movement, Wizard tasks are about imagination, and Santa contracts are about long-term goals. This makes abstract mechanics easier to understand.

Economy must not hide payer in unsafe ways. If child sees 🎅 Дед Мороз, the system still knows which adult created the task, promised reward and owes fulfillment. The character can change tone and currency, but not accountability.

The product should avoid making characters manipulate children. A character should inspire, explain and make progress visible. It should not pressure, shame or create dependence.

Detailed character rules are defined in [0401_Characters_Overview_t1.md](../04_Characters/0401_Characters_Overview_t1.md).

Character-specific economy should also remain understandable to parents. If Santa gives снежинки, Robot gives энергоядра and Wizard gives кристаллы, the parent must still see the whole picture in one place. A playful layer is useful only while it makes motivation clearer. If the family cannot understand which rewards are real money, which are internal value and which are non-money privileges, the economy has become too complex and should be simplified.

## 8. Exchange model

Exchange converts one value into another. It can convert internal currency to rubles, internal currency to privilege, internal currency to goal contribution or internal currency to family activity. Exchange should teach rate, timing and choice.

Child may request exchange. Adult approves. This distinction matters. A child should not directly trigger bank transfer or irreversible real-money action. The request flow protects adults and children and teaches that exchange is a decision, not magic.

Exchange can be simple. Example: 80 снежинок → 10 ₽. It can also be non-money: 15 кристаллов → 30 minutes of game time, or 50 энергоядер → family bike ride reward. Exchange can contribute to goal: 240 снежинок → 30 ₽ into bicycle savings.

Exchange is not automatic bank transfer in MVP. The app can show expected result, create request, notify adult, record approval and track fulfillment. If real money is involved, adult transfers manually outside the app and marks fulfilled.

A good exchange model gives the child a sense of agency while preserving family control. The child chooses amount, sees result and sends request. The adult confirms whether this exchange fits current family rules and obligations.

## 9. Exchange rate types

### Fixed rate

Fixed rate is the simplest model. It is stable and easy to explain.

```text
10 снежинок = 1 ₽
```

This works well for younger children and early versions. The child can calculate expected result without anxiety. Fixed rate should be the default if exchange is enabled early.

### Scheduled variable rate

Scheduled variable rate changes by a parent-configured interval and within parent-defined limits.

```text
Снежинки меняются от 8 до 12 за 1 ₽
Обновление: раз в неделю
```

Important: this must use parent-controlled deterministic or scheduled model, not casino-like randomness. The child should understand when and why rate changes. Scheduled changes can teach that value changes over time, but they must not push the child to compulsively check the app.

### Event-based rate

Event-based rate changes because the family defines a clear reason.

```text
Новый год:
снежинки +20%

День рождения:
кристаллы можно обменять на семейный кино-вечер

Каникулы:
энергоядра дают бонус к спортивным заданиям
```

Event-based changes are easier to understand because they have story and context. Parent creates reason. Child learns why value changes. This is safer than unexplained randomness.

## 10. Child exchange request flow

```text
Child opens exchange
→ sees currency balance
→ sees current rate
→ chooses amount
→ sees expected result
→ sends request
→ adult receives notification
→ adult approves, rejects, or discusses
→ fulfillment is recorded
```

This flow prevents accidental real-money movement. The child does not directly trigger bank transfer. The adult receives notification and decides whether to approve, reject or discuss. This is especially important when the exchange affects real money, family fund or a goal.

The request flow teaches asking and waiting. It shows that value exchange has process. The child sees balance, current rate and expected result before sending. This reduces surprises.

If adult rejects, the product should support respectful explanation. Rejection should not feel arbitrary. If adult discusses, the product can keep the request pending or cancelled with reason. The system should preserve clarity without turning the exchange into conflict.

## 11. Parent approval and manual fulfillment

Adult approves exchange. Approval means the family accepts the exchange under current rules. If the result is real money, the adult may transfer money manually in bank app or give cash. Then adult marks fulfilled in Parent App.

For non-money rewards, adult grants or schedules reward. For example, crystals may be spent on pizza, game time or family movie night. The app records status but does not need external integration.

Suggested statuses:

```text
draft
requested
approved
rejected
fulfilled
cancelled
expired
```

`draft` means the exchange is being prepared. `requested` means child sent it. `approved` means adult accepted it. `rejected` means adult declined. `fulfilled` means reward or transfer is done. `cancelled` means request was cancelled. `expired` means the request is no longer valid.

App tracks status. This protects trust. If child sent request and adult approved, the result should not disappear. If adult has not fulfilled yet, it remains pending until closed.

## 12. Ledger and balances

Ledger is event history. Balances are calculated from ledger. This is a product-level rule, not a database schema. The reason is trust: if balance changes, family should know why.

Ledger should track earned, spent, exchanged, adjusted, expired and transferred to goal. It should be possible to explain every visible balance. Do not allow silent balance changes. Adjustments should have reason and adult author.

Example ledger events:

```text
earned
spent
exchange_requested
exchange_approved
exchange_fulfilled
goal_contribution
manual_adjustment
expired
```

`earned` means value was received from task, contract or habit. `spent` means value was used for privilege or reward. `exchange_requested`, `exchange_approved` and `exchange_fulfilled` show exchange flow. `goal_contribution` moves value toward goal. `manual_adjustment` corrects balance with reason. `expired` handles values that are no longer valid if family rules allow expiration.

Silent changes are dangerous. If a parent adjusts 100 снежинок down to 50, the child should not simply see a lower balance without reason. The product should show transparent history appropriate to age.

## 13. Savings goals

Goals connect rewards to meaning. A child may have a goal like bicycle, book, game, family trip or animal shelter food. Currency or money can go to goal. The child sees progress and understands that repeated effort can accumulate.

Adult can contribute after task or contract completion. Example: a contract promises 500 ₽ into bicycle savings. When approved, reward obligation appears and then contribution is marked fulfilled. This is more meaningful than handing the child an abstract number.

Family goals are possible. A family can save toward a trip, event or shared purchase. Charity goals are possible as optional family-controlled goals. These should not require external donation processing in MVP.

Goals help delayed gratification. Instead of spending everything immediately, the child can decide to save. The product should show progress simply: amount collected, amount needed and what actions contributed.

Goals should remain understandable. Younger children need visual progress. Older children can see more details: contributions, dates, exchange rates and pending obligations.

## 14. Non-money rewards

Non-money rewards include privilege, gift, extra screen/game time, family event, recognition, collectibles or achievements. They are essential because many families do not want money for chores or habits.

Privilege can be 30 minutes of game time. Gift can be small toy or book. Family event can be movie night, pizza or trip to park. Recognition can be a message from parent or character. Collectibles and achievements can support progress without monetary value.

Non-money rewards make the product usable for families with different values. One family may use rubles for some tasks. Another may use only internal currencies. Another may avoid exchange entirely and use recognition and goals.

Not all rewards need exchange. Some are directly granted after approval. Some are bought with internal currency. Some are connected to goals. Product should not force every reward into a money conversion.

## 15. Treasury

Treasury is parent-facing financial and obligation overview. It shows pending obligations, fulfilled rewards, who owes what, monthly totals and currency totals. It helps adults see promises, not shame anyone.

Example:

```text
🏛 Казначейство

Ожидает выплаты:
350 ₽

Выдано за месяц:
2 400 ₽

Ожидает обмена:
240 снежинок → 30 ₽
```

Treasury can show that father paid 2400 ₽ this month, grandmother has 100 ₽ pending, and 240 снежинок await exchange. This helps with planning and prevents forgotten promises.

Treasury should not become a public scoreboard. It is primarily for adults. Child-facing economy should focus on personal goals, pending rewards and understandable progress. Adult totals and family budgeting can stay in Parent App.

## 16. Family government

Family government is optional educational layer. It can include family rules, shared resources, family fund, taxes, charity and collective goals. It exists to teach that resources can be personal and shared.

Family government is not in MVP. It should be disabled by default for younger children. It must be explained clearly when enabled. If a child sees a deduction, fund or rule, they should understand what happened and why.

This layer can be powerful for older children and teens. It can teach shared budgets, responsibility and social value. But it can also become too complex or feel unfair if introduced too early. Product should treat it as advanced mode.

Family government should remain family-controlled. It is not public governance, not external marketplace and not social network.

## 17. Family fund

Family fund is shared fund for family goals. It can receive contributions from exchanges or manual adult contributions. It can fund family activities and help child learn common budget.

Example:

```text
Семейный фонд

Цель:
поездка в парк

Собрано:
850 ₽ из 2000 ₽
```

Family fund can make shared resources visible. If the family decides that part of exchanges goes to a park trip, the child can see how individual actions contribute to collective outcome. This should feel educational, not confiscatory.

Adults can contribute manually. Children may contribute voluntarily if family settings allow it. Optional rules can send small visible percentages to the fund, but never hidden deductions.

## 18. Optional taxes

Optional taxes are educational, parent-controlled and never hidden. The word "tax" may be too heavy for younger children, so future UX may choose softer wording, but the product rule remains: visible percent, visible purpose, visible destination.

Example:

```text
Правило:
2% каждого обмена идет в Семейный фонд.
```

Optional taxes can go to family fund or charity fund. They should be disabled by default for younger children. They should be introduced only when parents can explain why shared contributions exist.

Taxes should not feel like surprise punishment. No hidden deductions. No sudden loss after exchange. Before a child sends exchange request, they should see expected result and any contribution to fund.

If the family uses optional taxes, the product should frame them as shared resource learning, not as penalty for earning.

## 19. Charity fund

Charity fund is optional charity goal. It teaches social value and shared care beyond personal rewards. It can be family-controlled and connected to family decisions.

Example:

```text
❤️ Фонд помощи животным

Цель:
купить корм для приюта

Источник:
1% обменов или добровольные взносы
```

No external donation processing in MVP. If real donation happens, parent handles it manually outside the app. The app can track intention, goal and fulfillment inside family context.

Charity should not be forced. Voluntary contributions may be more educational than automatic ones for some families. If an automatic percentage exists, it must be visible and parent-controlled.

## 20. Graphs and financial literacy

Graphs can help children understand history and progress. Child can see currency history, exchange rate graph, goal progress, earned vs spent, pending rewards and simple visual explanations.

Graphs should teach, not create compulsive checking. If rate graph updates too often or looks like trading screen, it can push unhealthy behavior. For younger children, graphs should be simple: progress bar, collected amount, goal remaining. Older children can see more detail.

Exchange rate graph can show scheduled or event-based changes. It should avoid casino-like excitement. The goal is learning: "value changed because family event happened" or "rate updates weekly".

Earned vs spent can teach budgeting. Pending rewards can teach obligations. Goal progress can teach saving. The product should explain graphs in plain language, not financial jargon.

## 21. Age-appropriate complexity

### Simple mode

For younger children:

- tasks;
- visual rewards;
- goals;
- no complex exchange;
- no taxes;
- no variable rates.

Simple mode should feel complete, not limited. A younger child can understand task, reward and goal without seeing treasury, rates or taxes.

The main product responsibility in Simple mode is restraint. The app should not tease younger children with locked exchanges, hidden rates or advanced graphs they cannot understand. If a module is disabled, the child experience should still feel coherent: do a task, receive a visible reward, move toward a goal, and hear a clear explanation from the adult.

### Learning mode

For middle age:

- currencies;
- simple exchange;
- fixed rates;
- goals;
- basic graphs.

Learning mode introduces financial literacy carefully. The child can request exchange, see fixed rate and understand progress. Parent approval remains required.

### Advanced mode

For older children and teens:

- scheduled rates;
- event rates;
- family fund;
- optional taxes;
- deeper graphs;
- contract-linked economy.

Advanced mode is where family economy becomes a richer educational system. It should be opt-in and explainable. If it creates pressure or confusion, it should be simplified or disabled.

Age-appropriate complexity is not only a UX setting. It is a safety rule. A mechanic that is educational for a teenager can be confusing or unfair for a younger child. The same family may need different settings for different children, and the product should allow adults to keep the economy simple until the child is ready for more detail.

## 22. MVP vs future scope

| Feature | MVP | v1 | v2 | v3+ | Notes |
| --- | --- | --- | --- | --- | --- |
| Internal reward ledger | ✅ | ✅ | ✅ | ✅ | Core tracking of rewards. |
| Real money manual tracking | ✅ | ✅ | ✅ | ✅ | No bank API in MVP. |
| Simple savings goals | ✅ | ✅ | ✅ | ✅ | Connect rewards to meaning. |
| Internal currencies | ⚪ | 🟡 | ✅ | ✅ | Basic version may appear after MVP. |
| Exchange requests | ⚪ | ⚪ | ✅ | ✅ | Requires adult approval. |
| Fixed exchange rate | ⚪ | 🟡 | ✅ | ✅ | Safest exchange model. |
| Scheduled variable rates | ⚪ | ⚪ | 🟡 | ✅ | Advanced mode, parent-controlled. |
| Event-based rates | ⚪ | ⚪ | 🟡 | ✅ | Clear reason required. |
| Treasury | 🟡 | ✅ | ✅ | ✅ | Starts as obligations overview. |
| Family fund | ⚪ | ⚪ | ✅ | ✅ | Optional educational layer. |
| Optional taxes | ⚪ | ⚪ | 🟡 | ✅ | Disabled by default for younger children. |
| Charity fund | ⚪ | ⚪ | 🟡 | ✅ | No external donation processing in MVP. |
| Exchange graphs | ⚪ | ⚪ | 🟡 | ✅ | Teach, not compulsive checking. |
| Bank API | ⚪ | ⚪ | ⚪ | 🔒 | Future/frozen unless separately approved. |
| Real bank savings integration | ⚪ | ⚪ | ⚪ | 🔒 | Future/frozen. |
| Smart watch health economy | ⚪ | ⚪ | ⚪ | 🔒 | Future integration. |

MVP should focus on ledger, manual tracking and simple goals. v1 may add basic internal currencies if they do not overload the product. v2 is the natural place for exchange, treasury, family fund and controlled rate models. v3+ can include advanced graphs and integrations only after safety and value are proven.

## 23. Product examples

### Snowflake exchange

```text
📈 Биржа

Текущий курс:
8 снежинок = 1 ₽

У тебя:
240 снежинок

Можно обменять:
240 снежинок → 30 ₽

Отправить запрос?
```

### Crystal privilege

```text
🧙 Кристаллы

Кристаллы нельзя обменять на рубли.

Можно потратить на:
🎮 30 минут игры
🍕 любимую пиццу
🎬 семейный кино-вечер
```

### Event rate

```text
🎄 Новогоднее событие

Снежинки сегодня ценнее:
8 снежинок = 1 ₽

Обычный курс:
10 снежинок = 1 ₽
```

### Treasury

```text
🏛 Казначейство

Папа:
2 400 ₽ выплачено

Бабушка:
100 ₽ ожидает выплаты

Биржа:
240 снежинок ожидают обмена
```

### Family fund

```text
🏛 Семейный фонд

Цель:
поездка в парк

Источник:
2% обменов

Собрано:
850 ₽
```

### Charity

```text
❤️ Фонд помощи животным

Цель:
купить корм для приюта

Собрано:
320 ₽
```

### Manual fulfillment

```text
Обмен одобрен

Петя получит:
30 ₽

Действие взрослого:
перевести вручную и отметить как выполнено.
```

## 24. Product rules

- Economy is family-only.
- No public market.
- No automatic bank transfers in MVP.
- Exchange requires adult approval.
- Rates are parent-controlled.
- No random gambling-like default.
- Event-based changes must be explained.
- Deductions must be visible.
- Taxes are optional and never hidden.
- Child photos are not part of economy.
- Internal currencies do not imply real money unless configured.
- Some currencies may be non-exchangeable.
- Balance changes must be ledger-based.
- Manual adjustments require reason.
- Economy modules can be disabled.

## Open Questions

- Should MVP include any internal currency or only money/manual rewards?
- Should fixed exchange be available before v2?
- Should scheduled variable exchange rates be hidden behind an advanced mode?
- What is the safest default for younger children?
- Should taxes be renamed to a softer child-facing term?
- Should family fund be visible to children by default?
- Should charity goals be part of v2 or later?
- Should exchange graphs have limits to avoid compulsive checking?
- What terminology should be used in Russian: "Казначейство", "Семейный фонд", "Биржа", "Государство семьи"?
