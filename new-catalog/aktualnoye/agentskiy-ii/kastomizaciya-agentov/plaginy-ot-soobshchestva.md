---
order: 4
title: Плагины и MCP сообщества
---

<note type="info">

Плагины и MCP-коннекторы для Claude Cowork и Code, разработанные участниками [сообщества «Нейросети | ilovedocs»](https://t.me/docsllm) под собственные юридические задачи. Если вашего плагина или коннектора нет в списке, или в карточке есть ошибка -- сообщите через [форму обратной связи](https://forms.yandex.ru/u/69b94a8f95add5352028591d/).

</note>

**Дата составления:** 2026-08-31\
**Статус:** 💡 Актуально

---

## Плагины

<table header="row">
<tr>
<td>

**Проект**

</td>
<td>

**Описание**

</td>
<td>

**Ссылки**

</td>
</tr>
<tr>
<td>

[**Плагин по legal design**](https://t.me/ilovedocs/3289)

*Сооснователь сообщества* [*Нейросети | ilovedocs*](https://t.me/docsllm) *Павел Мищенко*

</td>
<td>

Перерабатывает договор по методологии legal design: удаляет лишнее, переструктурирует информацию, переписывает формулировки, оформляет верстку

</td>
<td>

[Получить](https://s.salebot.pro//runetlex_academy_web120334_1?utm_source=ad&utm_medium=neuralnetworks&utm_campaign=)

</td>
</tr>
<tr>
<td>

**Плагин для NotebookLM**

*Выпускник курса* [*«Нейросети для юриста: от основ к системе»*](https://runetlex-academy.ru/neuralnetworks) *Алексей Мынка*

</td>
<td>

Подключает NotebookLM к Cowork как инструмент: создание ноутбуков, добавление источников, AI-резюме, генерация подкастов и квизов прямо из интерфейса Cowork

</td>
<td>

[notebooklm_plugin.zip](notebooklm_plugin.zip)

</td>
</tr>
<tr>
<td>

[**Многомодельный плагин**](https://t.me/docsllm/74603)

*Спикер курса* [*«Нейросети для юриста: от основ к системе»*](https://runetlex-academy.ru/neuralnetworks) *Ян Стригов*

</td>
<td>

Форк плагина Superpowers для Claude Code с разделением труда между моделями: Sonnet -- оркестратор (диспатч шагов, git), Opus -- план и ревью, Codex -- скептичное ревью плана и реализация. План создается до первой строки кода, два независимых ревью перед коммитом, возобновляемые сессии, экономия лимитов Claude

</td>
<td>

[GitHub](https://github.com/strigov/superpowers-strigov-ver), [Разбор](https://strigov.pro/p/2026-04-16-superpowers-plugin/)

</td>
</tr>
<tr>
<td>

[**Vassal-Litigator**](https://litigator-viz.vercel.app)

*Спикер курса* [*«Нейросети для юриста: от основ к системе»*](https://runetlex-academy.ru/neuralnetworks) *Ян Стригов*

</td>
<td>

12 скиллов и 13 команд для ведения судебного дела в Cowork: OCR и реестр документов, правовой анализ, stress-test позиции, разбор транскрипций заседаний, апелляция и кассация

</td>
<td>

[GitHub](https://github.com/strigov/vassal-litigator), [Разбор](https://strigov.pro/p/2026-05-10-vassal-litigator-cc-1-2/)

</td>
</tr>
<tr>
<td>

**Legal-плагин по российскому праву**\
*Выпускник курса* [*«Нейросети для юриста: от основ к системе»*](https://runetlex-academy.ru/neuralnetworks) *Алексей Мынка*

</td>
<td>

Адаптация официального Legal-плагина Anthropic под российское право: файл `legal.local.md` с плейбуком по ГК и процессуальным кодексам, отраслевым особенностям (корпоративное, водное, земельное, градостроительное право, недропользование), источникам проверки -- К+, Гарант, Право.ру

</td>
<td>

[legal-local plugin.zip](<legal-local plugin.zip>)

</td>
</tr>
<tr>
<td>

[**legal-brief**](https://t.me/docsllm/76262)

*Участник сообщества* [*Нейросети | ilovedocs*](https://t.me/docsllm) *Иван Кундиль*

</td>
<td>

Юридический форк плагинов Superpowers (obra / Jesse Vincent) и superpowers-strigov-ver под судебную работу: мульти-агентный конвейер «одна модель предлагает, другая критикует, сборка в единую позицию». На выходе -- черновик позиции и файл со списком использованных норм и практики с проверкой, что ссылки открываются (актуальность проверяется вручную).

</td>
<td>

[GitHub](https://github.com/KunDeal/legal-brief)

</td>
</tr>
<tr>
<td>

[**Ясность: грамматика, логика и риторика для юристов**](https://t.me/docsllm/81176)

*Участница сообщества* [*Нейросети | ilovedocs*](https://t.me/docsllm) *Софья Смирнова*

</td>
<td>

Три скилла для проверки правового текста: *грамматика* -- однозначна ли формулировка (синтаксис, «и/или», границы сроков, «вправе» или «обязан»); *логика* -- следует ли вывод из нормы и факта; *риторика* -- убедит ли текст адресата (линия спора, порядок аргументов, стресс-тест контрпозицией).

</td>
<td>

[GitHub](https://github.com/sky-magenta/damascus-ink-plugins), [Инструкции](https://sky-magenta.github.io/damascus-ink-plugins/)

</td>
</tr>
</table>

## MCP-коннекторы

<table header="row">
<tr>
<td>

**Коннектор**

</td>
<td>

**Описание**

</td>
<td>

**Ссылки**

</td>
</tr>
<tr>
<td>

[**Коннектор к практике ФАС**](https://blog.delay-rag.ru/mcp-konniektor-k-poisku-po-praktikie-fas)

*Спикер курса* [*«Нейросети для юриста: от основ к системе»*](https://runetlex-academy.ru/neuralnetworks) *Екатерина Якуненко*

</td>
<td>

MCP поверх [поискового сервиса](https://search.delay-rag.ru/) по практике ФАС (\~8 тыс. решений о нарушениях ФЗ «О рекламе»). Дает агенту три инструмента (поиск дел с фильтрами, карточка дела, список фильтров) и три слеш-команды; ответы опираются на реальную практику со ссылками. Подключение по одному URL, без авторизации, работает в Claude (включая Free), Cursor, Codex

</td>
<td>

URL: `https://dataset-interface.onrender.com/mcp/`

[Документация](https://blog.delay-rag.ru/mcp-konniektor-k-poisku-po-praktikie-fas/)

</td>
</tr>
<tr>
<td>

**Коннектор к Судакту**

*Выпускник курса* [*«Нейросети для юриста: от основ к системе»*](https://runetlex-academy.ru/neuralnetworks) *Алексей Мынка*

</td>
<td>

MCP-коннектор со скиллом к Судакту для поиска судебной практики: статистика и выборка по точечным запросам, кликабельные ссылки на дела. Работает в Claude Code (с кодом), не в Cowork

</td>
<td>

[GitHub](https://github.com/mynka999/sudact-mcp-server)

</td>
</tr>
<tr>
<td>

**Коннектор к NotebookLM**

*Максим Шедогубов*

</td>
<td>

MCP-сервер к [NotebookLM](./../../../instrumenty/specializirovannye-ii-servisy/notebooklm), написанный под работу на сервере: браузер не нужен, запросы идут напрямую, авторизация лежит в отдельном файле сессии, который сервер сам продлевает. Поэтому агент обращается к блокнотам круглосуточно и не требует, чтобы вы были залогинены на своем компьютере. 

</td>
<td>

[notebooklm-mcp.zip](notebooklm-mcp.zip)

</td>
</tr>
</table>

---

## Связанные статьи

-  [Кастомизация агентов](./_index) -- общий обзор и три уровня кастомизации

-  [Кастомизация Claude](./kastomizaciya-claude) -- как ставить плагины в Cowork

-  [Скиллы и плагины](./skills-i-plaginy) -- что такое плагин и из чего он состоит

-  [Claude Cowork](./../obzor-servisov/claude-cowork) -- основной интерфейс, в котором используются плагины

-  [Как внести вклад в Базу знаний](./../../../razvitie-bazy-znanii/kak-vnosit-vklad) -- предложить свой плагин в этот сборник или правку к карточке

---

Теги: #агентный-ии #плагины #сообщество #актуальное