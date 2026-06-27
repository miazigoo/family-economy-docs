# 0401 Characters Overview

| Field | Value |
| --- | --- |
| Status | Draft |
| Version | t1 |
| Author | Pavel + OpenAI |
| Audience | Product, Developers, Parents, Investors, Marketing |
| Related documents | 0001_Manifest_t1.md, 0002_Core_Principles_t1.md, 0003_Product_Vision_t1.md, 0101_Product_Overview_t1.md, 0102_Product_Storytelling_t1.md, 0201_Economy_Overview_t1.md, 0301_Tasks_vs_Contracts_t1.md |
| Purpose | Defines the character/persona model, including emotional role, safety boundaries, adult accountability, character economy, tone, reputation, and product usage rules. |
| Last update | 2026-06-27 |

## Table of Contents

- [1. Character in one paragraph](#1-character-in-one-paragraph)
- [2. Why characters exist](#2-why-characters-exist)
- [3. What characters are not](#3-what-characters-are-not)
- [4. Adult user vs character](#4-adult-user-vs-character)
- [5. Multiple characters per adult](#5-multiple-characters-per-adult)
- [6. Child-facing identity and internal accountability](#6-child-facing-identity-and-internal-accountability)
- [7. Character permissions](#7-character-permissions)
- [8. Character tone and style](#8-character-tone-and-style)
- [9. Character economy](#9-character-economy)
- [10. Character currencies](#10-character-currencies)
- [11. Character generosity and rarity](#11-character-generosity-and-rarity)
- [12. Character reputation](#12-character-reputation)
- [13. Character templates](#13-character-templates)
- [14. Default character examples](#14-default-character-examples)
- [15. Custom characters](#15-custom-characters)
- [16. Characters in tasks](#16-characters-in-tasks)
- [17. Characters in contracts](#17-characters-in-contracts)
- [18. Characters and trusted adults](#18-characters-and-trusted-adults)
- [19. Characters and AI helper](#19-characters-and-ai-helper)
- [20. Safety and ethics](#20-safety-and-ethics)
- [21. Age-appropriate character modes](#21-age-appropriate-character-modes)
- [22. MVP vs future scope](#22-mvp-vs-future-scope)
- [23. Product examples](#23-product-examples)
- [24. Product rules](#24-product-rules)
- [Open Questions](#open-questions)

## 1. Character in one paragraph

Character is a family-controlled presentation layer that lets an approved adult present a task, contract, reward, or message in a specific tone and style while the system still stores the real adult behind the action. Characters add emotion, story, warmth and play to family agreements, but they do not remove adult responsibility. They are family-only, not public identities, not separate real users and not a way for unknown adults to reach children. A child may see Santa Claus, Robot or Wizard, but the product must still know which adult created the task, who promised the reward, who pays, and who is accountable.

## 2. Why characters exist

Children respond to stories. A simple request can feel very different depending on how it is framed. "Clean your room" can sound like a command. A mission from a character can make the same action warmer, clearer and more memorable. The product should not hide the real condition, but it can make the experience feel less dry.

Characters make repeated habits less boring. Walking 5000 steps can be a health task. From Robot X-17 it can become a short mission. Reading 10 pages can be a line in a checklist. From Wizard it can become part of a learning journey. This matters because motivation is not only about reward amount. It is also about meaning, tone and emotional context.

Characters let parents choose tone. Sometimes a direct adult request is best. Sometimes a playful persona helps the child engage. Sometimes a rare character creates a special moment. Sometimes a structured character makes a habit feel clear and calm.

Example:

```text
Папа может попросить напрямую:
"Помоги мне помыть машину."

А вечером тот же взрослый может отправить миссию:
"🎅 Дед Мороз заметил, что ты хорошо себя вел. Есть особое задание!"
```

Characters support play without making the product unsafe. They help the product become emotionally memorable for children and easier to explain to parents, investors and developers. But the story must never erase accountability. If the product becomes warmer but less honest, the character model is wrong.

The strongest product value of characters is not decoration. It is translation. A parent already has an intention: ask for help, support a habit, offer a contract, recognize effort, or remind about a goal. A character translates that intention into a tone the child can receive more easily. This is why characters belong in the product model, not only in marketing copy. They shape how agreements feel.

At the same time, character usage should be measured. If every ordinary request becomes dramatic fantasy, the child may stop trusting the tone. A character works best when it makes the situation clearer, warmer or more motivating. If it makes the situation less clear, the adult should use direct identity instead.

## 3. What characters are not

Characters are not separate real users. They are not public accounts. They are not a way for unknown adults to contact children. They are not a way to hide responsibility from the system. They are not a manipulative tool. They are not AI agents acting independently. They are not a public marketplace of identities.

The family may enable child-facing fantasy mode. A younger child may see a message from Santa Claus or Wizard and enjoy the story. But the system must still keep audit and real author. Parent-facing views must show enough accountability: real adult, character used, payer, reward obligation, and history of actions.

Characters must not create unsafe ambiguity. If a task arrives from a character, it must still be created by an approved adult or allowed family flow. If a contract is proposed by a character, the real adult or approved payer is still responsible. If a reward is delayed, the character cannot be used as a mask to avoid responsibility.

Characters are also not a replacement for parenting. They can help adults phrase a request, but the adult remains responsible for the request, the tone, the reward and the conversation around it.

A character also should not be used to say something an adult would not be willing to say directly. If the message contains pressure, threat, shame or unclear consequences, putting a friendly avatar on it does not make it acceptable. The character layer should raise the quality of communication, not soften unsafe communication enough to pass through.

## 4. Adult user vs character

An adult user is an authenticated real person in the family system. This can be Parent Owner or Trusted Adult. The adult has permissions, settings, responsibility and audit history. A character is a presentation layer. It changes how a message appears to the child, not who is responsible.

One adult can act as Father, Santa Claus, Robot or Wizard. The child may see the character. The system must store real adult id internally. Parent Owner can review character use and understand which adult sent which task, contract, reward or message.

This document does not define database schema. It defines the product rule: character identity and real adult identity must be separate concepts. The product can show a playful layer to the child while keeping accountability in parent-facing and internal records.

This distinction is essential for safety. If the product only stores character name, then accountability is lost. If it only shows real adult name and never supports character tone, the product loses emotional differentiation. The correct model supports both: child-facing story and internal truth.

## 5. Multiple characters per adult

One adult may have multiple personas. Different family moments need different tone. A direct father tone works for real help: "Помоги мне помыть машину". Santa can be rare and magical. Robot can be structured and useful for health or activity. Wizard can be educational and focused on non-money rewards.

Character choice should be intentional. The adult should choose a character because it helps the child understand or enjoy the task, not because it hides pressure. If the task is serious, sensitive or emotionally difficult, direct adult tone may be better.

Example:

```text
Adult:
Pavel

Characters:
👨 Папа
🎅 Дед Мороз
🤖 Робот X-17
🧙 Волшебник
```

Multiple characters per adult also support different currencies and reward styles. The same adult can pay rubles directly as Father, give снежинки as Santa, give энергоядра as Robot, or give кристаллы as Wizard. The product must still make the payer explicit.

Multiple characters should not overload the child. If too many characters exist, the story becomes noisy. The product should help families start with a small set and add more only when useful.

## 6. Child-facing identity and internal accountability

Child-facing identity can be character. Internal accountability is always real adult. Every task, contract, reward obligation and reminder must know who created it. Every paid reward must know who pays. If a character promises reward, real adult or approved payer is responsible.

Child-facing mode can be simplified. A younger child may only need to see "🎅 Дед Мороз" and the mission. Parent-facing mode must show enough accountability: real author, payer, created time, approval status and reward fulfillment status.

This separation protects trust. The child gets story and warmth. The parent gets audit and responsibility. The system gets clear ownership. If a dispute happens, the family can see what was promised and who promised it.

A character cannot create a task by itself. A character cannot pay by itself. A character cannot approve completion by itself. These actions belong to adults or approved family flows. The character is how the action is presented.

The audit trail should be understandable at product level even before any technical model is designed. A parent should be able to answer simple questions: which adult used this character, what did they send, what reward did they promise, was the reward fulfilled, and did the child see a clear version of the terms? If the product cannot answer these questions, character mode becomes unsafe.

For the child, accountability can be shown with different levels of detail. A younger child may only need a simple statement that the family knows who sent the mission. An older child may need a more explicit display: \"Sent by Dad as Robot X-17.\" This is an age and family preference, but the system must support the underlying truth.

## 7. Character permissions

Not every adult can use every character. Parent Owner controls permissions. Trusted Adult may use only approved characters. Some characters may be family-wide. Some may be private to one adult. Some may require approval before sending tasks or contracts.

Examples:

- Grandmother can use "Бабушка".
- Grandmother cannot use "Папа".
- Trusted adult may be allowed to create tasks but not contracts.
- Trusted adult may be allowed to send rewards only up to a limit.

Character permission is a safety boundary. If a trusted adult can use any character, the child may misunderstand who is speaking. If the adult can promise unlimited rewards through a character, payment obligations can become unclear. The product must make permissions explicit.

Some characters may be family-wide, such as Robot or Wizard. Even then, the real adult behind each action must be stored. If both parents can use Robot, a parent-facing audit view must show which parent used Robot for a specific task.

Permissions should be simple by default. Advanced permission rules can come later. The first principle is clear: no adult uses a character unless the family owner allows it.

Permissions should also protect the adult. A trusted adult should not accidentally create obligations they did not understand. If a character has a currency, reward style or generosity setting, the adult using that character needs to know what they are promising. This is especially important for paid tasks and contracts. A playful character can still create a real obligation.

## 8. Character tone and style

Tone affects wording. Style affects emotional feel. Character should not change factual conditions. Tone must not hide penalties or obligations. Child should understand actual task or contract terms even when the message is playful.

### Santa tone

Warm, rare, magical. Santa is useful for special missions, seasonal events and generous rewards. Santa should not appear so often that the character loses meaning or starts to feel like a manipulation tool.

### Robot tone

Short, structured, mission-like. Robot is useful for health, activity, steps, routines and clear progress. Robot can make habits feel precise without sounding emotional or dramatic.

### Wizard tone

Educational, mysterious, non-money rewards. Wizard can give кристаллы, explain learning missions and support privileges or family events. Wizard should feel curious and kind, not confusing.

### Father tone

Direct, personal, real-family request. Father is useful when honesty and closeness matter more than fantasy. A child may appreciate directness when the task is clearly a real request from the adult.

Tone must never obscure the basics: what to do, deadline, proof, reward, penalty if any, and who is responsible. If the tone makes terms less clear, it should be simplified.

Tone also affects trust over time. If Robot is always precise, the child learns that Robot missions are predictable. If Wizard is always educational, the child learns that Wizard tasks are about learning and privileges. If Santa is rare and warm, the child learns that Santa missions are special. Consistency helps characters feel real without making them unsafe.

## 9. Character economy

A character can have its own economy. This economy may include currency, reward type, generosity and rarity. Santa may be generous but rare. Robot may reward small healthy habits often. Wizard may give crystals for privileges. Father may pay in rubles directly.

Character economy must follow Family Economy rules. Exchange and currencies are parent-controlled. No gambling-like loops. No random loot-style appearances by default. No hidden deductions. No unclear conversion from character currency to real money.

A character economy should support story and engagement. It should help the child understand why this reward exists. Robot gives энергоядра because it is about movement. Wizard gives кристаллы because it is about privileges or learning. Santa gives снежинки because it is magical and rare.

Detailed economy rules are defined in [0201_Economy_Overview_t1.md](../02_Economy_Bible/0201_Economy_Overview_t1.md).

## 10. Character currencies

A character can issue a currency. Currency may be exchangeable or non-exchangeable. Currency can be spend-only. Some currencies may only fund goals or privileges.

Examples:

```text
🎅 Снежинки
Can be exchanged for rubles if parents allow.

🤖 Энергоядра
Used for movement and health missions.

🧙 Кристаллы
Can buy privileges, not rubles.
```

Character currency should be understandable. If a child earns 20 энергоядер, they should know what those are for. If кристаллы cannot be exchanged for rubles, this must be clear. If снежинки can be exchanged, the rate and approval flow must follow family economy rules.

Currency should not make character mode feel like a casino. It should not create random rewards or unpredictable conversion by default. It should make family learning more vivid.

## 11. Character generosity and rarity

Generosity means typical reward amount or value. Rarity means how often character appears. These are product concepts, not necessarily database fields yet. They help children feel character personality.

Examples:

```text
🎅 Дед Мороз
Generosity: high
Rarity: rare

🤖 Робот
Generosity: low/medium
Rarity: frequent

🧙 Волшебник
Generosity: non-money
Rarity: medium
```

Rarity must not create gambling-like compulsion. The product should not train the child to constantly check whether a rare character appeared. No random loot-style appearance by default. Parents control character availability.

Generosity should also be controlled. A generous character can create large reward obligations. If Santa promises too much too often, the family economy becomes hard to manage. Parent-facing tools should help adults see the cost and obligation impact of character use.

Rarity should be explained through family context, not chance addiction. Santa can be rare because the family uses him for holidays or special milestones. Robot can be frequent because daily movement is a habit. Wizard can be medium rarity because learning missions happen several times a week. These patterns are understandable and parent-controlled. They are different from random surprise mechanics that train the child to keep checking the app.

## 12. Character reputation

Character can have reputation separate from adult. Adult reputation still exists. Character reputation may be child-facing. Adult reputation may be parent-facing. Reputation should not shame. It should describe reliability.

Examples:

```text
🎅 Дед Мороз обычно выполняет обещания быстро.
🤖 Робот строгий, но честный.
🧙 Волшебник чаще дает привилегии, а не деньги.
```

Delayed reward obligations affect character and adult trust. If Santa promises rewards but the adult behind Santa delays payment, the child experiences Santa as unreliable. The product must not hide this. It can show simplified character reliability to the child and more detailed adult responsibility to the parent.

Reputation supports fairness. It helps the family talk about promises. It should not become a public ranking, shame label or punishment mechanic. Character reputation is a trust signal, not a moral judgment.

## 13. Character templates

Templates help families start quickly. A parent should not need to design every character from zero. Default templates can provide safe tone, avatar suggestion, default currency, reward style and rarity.

Templates should be editable. A family may want Santa to use снежинки, another may want Santa to use only gifts or family events. Robot can be strict in one family and funny in another. Wizard can focus on learning or privileges.

Templates should be safe by default. They should avoid manipulative language, unsafe promises, hidden penalties, public identity, unknown adult access or AI autonomy. Family can disable templates.

A template is not a global public character marketplace. It is a local starting point inside the family product.

Templates should also make safe defaults easier than unsafe customization. The easiest path should be a character with respectful language, clear task structure, no hidden penalties, no unknown adult access and parent-controlled rewards. If a family wants more advanced behavior, they can configure it deliberately. The default path should protect families that do not want to think through every edge case.

## 14. Default character examples

| Character | Tone | Best use | Reward style | Safety note |
| --- | --- | --- | --- | --- |
| Father | Direct, personal | Real help, family requests | Rubles, privileges, recognition | Clear real adult identity. |
| Mother | Warm, practical | Daily routines, care tasks | Rubles, recognition, family activities | Clear real adult identity. |
| Santa Claus | Magical, rare | Special missions, seasonal tasks | Snowflakes, gifts, goal contributions | Rare and parent-controlled. |
| Robot | Structured, mission-like | Steps, health habits, routines | Energy cores, streaks, small rewards | No pressure-first language. |
| Wizard | Educational, mysterious | Learning, reading, non-money rewards | Crystals, privileges, family events | Must keep terms clear. |
| Dragon | Energetic, challenge-like | Courage tasks, cleanup missions | Badges, crystals, progress | Avoid frightening tone. |
| Grandmother | Caring, family-centered | Poems, reading, family help | Rubles, gifts, recognition | Trusted adult permissions required. |
| Coach | Motivating, clear | Exercise, sports, consistency | Activity points, recognition | Avoid shame or body pressure. |

Default characters should be optional. Families can use only direct adult identity if they prefer. The product should not assume every family wants fantasy.

## 15. Custom characters

Parent can create custom character with name, avatar, tone, currency and reward style. Custom characters should be family-only. A custom character must be tied to real adult or family owner. Parent Owner may approve custom characters before they can send tasks or contracts.

Custom characters should avoid impersonating real external people. A family should not create a character that makes a child believe an unknown real person is contacting them. The product should avoid unsafe or frightening characters, especially for younger children.

Custom character settings should remain understandable. If a parent creates "Space Captain", the product should ask: who controls this character, what tone does it use, what rewards can it promise, what currency does it use, and who pays?

Custom characters add emotional flexibility, but also require guardrails. The more customizable the product becomes, the more important audit and permission controls become.

The product should help parents create characters that are understandable to children. A custom character should have a clear role: helper, coach, storyteller, direct family member, learning guide. If a custom character has no clear role, it may create noise. If it has a frightening or overly controlling role, it may harm trust. Character creation should therefore ask not only \"what is the name?\" but also \"when should this character be used?\"

## 16. Characters in tasks

A simple task can be shown through character. Task conditions remain clear. Character text should not hide deadline, reward or proof. The child sees mission-like text, but the task remains a family agreement.

Example:

```text
🤖 Робот X-17

Миссия:
Пройти 5000 шагов.

Срок:
до 20:00

Награда:
20 энергоядер.
```

Characters are especially useful for tasks that might otherwise feel repetitive. They can make a daily step goal, room cleanup or reading task feel more specific and intentional.

The product should still show task essentials in structured form. If the character text says "special mission", the screen still needs task, deadline, reward and required proof. Story is additive, not a replacement for clarity.

This matters for implementation later. A future screen should not rely only on a generated character paragraph. It should separate expressive text from structured task facts. The child can enjoy the paragraph, but the family agreement must remain readable even if the character text is ignored.

## 17. Characters in contracts

A character can propose contract. Contract must still show terms. Penalties must be visible before signing. Fantasy tone cannot hide real conditions.

Example:

```text
🎅 Дед Мороз

Предлагаю долгий контракт:

30 дней делать зарядку.

Награда:
1000 снежинок

Возможный штраф:
-100 снежинок за пропуск без причины.

Принять контракт?
```

Characters in contracts require extra care because contracts last longer and may include penalties or reward obligations. The child must understand what they accept. A playful button can exist, but it should still mean clear acceptance.

Detailed task and contract rules are defined in [0301_Tasks_vs_Contracts_t1.md](../03_Contracts_Bible/0301_Tasks_vs_Contracts_t1.md).

For contracts, character tone should usually be shorter and more structured than for simple tasks. A contract is not only a story. It contains conditions, duration, reward, possible penalty and responsibility. A character can introduce the contract warmly, but the terms should be displayed in a stable, plain format.

## 18. Characters and trusted adults

Trusted adults may have their own characters. Family owner controls access. Child cannot be contacted by unknown adults through character. Trusted adult task or contract creator must remain auditable. Payer must be explicit.

Example:

```text
👵 Бабушка

Выучи стихотворение до воскресенья.

Награда:
100 ₽
```

A trusted adult can be allowed to use direct identity only, or a limited set of characters. For example, grandmother can use "Бабушка" but not "Папа". She may be allowed to create tasks but not contracts. She may be allowed to promise rewards only up to a family-defined limit.

Trusted adult character permissions are safety features. They prevent confusion and keep responsibility clear.

Trusted adult scenarios are emotionally sensitive because the child may already trust the person outside the app. The product should not make that trust vague. If Grandmother sends a task, the child should not wonder whether it was actually Grandmother, Parent Owner or an unknown person using a grandmother-like character. Family approval and audit make this clear.

## 19. Characters and AI helper

Future AI may help generate character text. AI should be helper, not autonomous adult. AI cannot send tasks or contracts without approved adult action. AI cannot decide reward, penalty or approval independently. AI-generated text must preserve factual task or contract terms.

Adult writes:

```text
Убрать комнату до вечера, 40 снежинок.
```

AI helper suggests Santa style:

```text
🎅 Хо-хо-хо! У меня есть для тебя особая миссия...
```

Adult approves before sending.

AI style helper can save time and make character tone consistent. But it cannot impersonate unknown adults, invent obligations, add hidden penalties or change reward. If AI suggests text that changes facts, the adult must reject or edit it.

## 20. Safety and ethics

Characters are playful but powerful. A child may emotionally respond to a character more strongly than to a normal interface. Product must avoid manipulation. Fantasy mode should be parent-controlled. Older children may prefer transparency. Family decides level of character and fantasy.

System always stores real adult. No unknown adult access. No public chat. No public character marketplace. No deception for payments or penalties. Sensitive topics should use direct adult tone, not fantasy. A serious conflict, health concern, punishment discussion or emotional issue should not be hidden behind a magical character.

Character mode should increase warmth, not reduce consent. If a child signs a contract because Santa said it magically, but they do not understand conditions, the product failed. If a character makes a task more inviting while keeping terms clear, the product works.

Ethical character design means respecting the child. The product should not exploit belief, fear, scarcity or attachment. It should use story to help the family communicate better.

## 21. Age-appropriate character modes

### Simple character mode

For younger children:

- friendly avatar;
- short messages;
- simple missions;
- no complex economy.

Simple character mode should show clear tasks, visual rewards and minimal text. The child does not need complex reputation, exchange rates or contract details.

### Story mode

For children who enjoy fantasy:

- characters;
- currencies;
- missions;
- goals;
- limited contracts.

Story mode can make Family Economy memorable. It should still keep terms visible and avoid hidden consequences.

### Transparent mode

For older children and teens:

- characters may still exist;
- real adult identity may be more visible;
- contracts and economy are clearer;
- less fantasy, more responsibility.

Transparent mode respects maturity. Older children may enjoy characters as style, but they may also want to know exactly which adult is speaking and what the agreement means.

## 22. MVP vs future scope

| Feature | MVP | v1 | v2 | v3+ | Notes |
| --- | --- | --- | --- | --- | --- |
| Direct adult identity | ✅ | ✅ | ✅ | ✅ | Required for trust and safety. |
| Basic character selection | 🟡 | ✅ | ✅ | ✅ | Optional in MVP. |
| Default characters | 🟡 | ✅ | ✅ | ✅ | Safe templates first. |
| Custom characters | ⚪ | ✅ | ✅ | ✅ | Parent-controlled. |
| Multiple characters per adult | ⚪ | ✅ | ✅ | ✅ | Clear audit required. |
| Character-specific currency | ⚪ | 🟡 | ✅ | ✅ | Follows Economy Bible rules. |
| Character reputation | ⚪ | 🟡 | ✅ | ✅ | No shame mechanics. |
| Trusted adult character permissions | ⚪ | 🟡 | ✅ | ✅ | Parent Owner controls access. |
| AI text style helper | ⚪ | ⚪ | ⚪ | ✅ | Adult approves before sending. |
| Character avatar library | 🟡 | ✅ | ✅ | ✅ | Safe built-in avatars. |
| Seasonal characters | ⚪ | 🟡 | ✅ | ✅ | Parent-controlled availability. |
| Voice characters | ⚪ | ⚪ | ⚪ | 🔒 | Future/frozen. |

MVP should include direct adult identity and may include very basic character selection if it does not weaken safety or delay the core loop. v1 can introduce default and custom characters. v2 can deepen character economy, reputation and trusted adult permissions. v3+ can explore AI style helper, seasonal characters and voice only after safety is proven.

## 23. Product examples

### Direct father task

```text
👨 Папа

Помоги мне помыть машину до обеда.

Награда:
150 ₽
```

### Santa task

```text
🎅 Дед Мороз

Хо-хо-хо!

Сегодня у меня есть особое задание.

Убери комнату до вечера.

Награда:
40 снежинок.
```

### Robot mission

```text
🤖 Робот X-17

Миссия активна.

Пройти 5000 шагов.

Награда:
20 энергоядер.
```

### Wizard non-money reward

```text
🧙 Волшебник

Ты получил 15 кристаллов.

Кристаллы можно потратить на:
🎮 30 минут игры
🍕 любимую пиццу
🎬 семейный кино-вечер
```

### Character reputation

```text
🎅 Дед Мороз

Надежность:
обычно выполняет обещания быстро.

Награды:
редкие, но щедрые.
```

### Parent audit view

```text
Задание отправлено как:
🎅 Дед Мороз

Реальный автор:
Папа

Плательщик:
Папа
```

### AI style helper

```text
Черновик взрослого:
Убрать комнату до вечера, 40 снежинок.

Предложение ИИ:
🎅 Хо-хо-хо! У меня есть для тебя особая миссия...
```

### Trusted adult task

```text
👵 Бабушка

Выучи стихотворение до воскресенья.

Награда:
100 ₽
```

## 24. Product rules

- Character is not a real user.
- Character cannot remove adult accountability.
- Real adult must be stored internally.
- Payer must be explicit.
- Trusted adults need permissions.
- Child cannot receive character messages from unknown adults.
- No public character marketplace.
- No public chat.
- Character tone cannot hide task or contract conditions.
- Character tone cannot hide penalties.
- Character tone cannot hide payment obligations.
- AI cannot send as character without adult approval.
- Character economy follows Family Economy rules.
- Character rarity must not create gambling-like loops.
- Sensitive topics should use direct adult tone.

## Open Questions

- Should MVP include fantasy characters or only direct adult identity?
- Should character mode be enabled by default or introduced during onboarding?
- Should older children see the real adult behind a character?
- Which default characters should ship first?
- Should every character require a linked payer?
- Should trusted adults be allowed to create custom characters?
- Should character reputation be visible to children or only simplified?
- Should AI-generated character text be allowed in MVP or later?
- What character/avatar restrictions are needed for safety?
