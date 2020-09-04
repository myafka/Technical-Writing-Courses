<h1>Документы</h1>

> Расчетное время: 10 минут

Вы можете писать предложения. Вы можете писать абзацы. Однако можно ли организовать все эти абзацы в единый документ?

<h2>State your document's scope</h2>

A good document begins by defining its scope. For example:

> Этот документ описывает общий дизайн Project Frambus.

A better document additionally defines its non-scope, that is, the topics not covered that the target audience might expect your document to cover. For example:

> Этот документ не описывает дизайн соответствующей технологии, Project Froobus.

These scope and non-scope statements benefit not only the reader but also the writer (you). While writing, if the contents of your document veer away from the scope statement, then you must either refocus your document or modify your scope statement. When reviewing your first draft, delete (or branch off to another document) any sections that don't help satisfy the scope statement.

<h2>Укажите свою аудиторию</h2>

В хорошем документе четко указывается его аудитория. Например:

> Я написал этот документ для инженеров-тестировщиков, поддерживающих Project Frambus.

Beyond the audience's role, a good audience declaration might also specify any prerequisite knowledge or experience. For example:

> В этом документе предполагается, что вы понимаете умножение матриц и знаете, как приготовить действительно хорошую чашку чая.

In some cases, the audience declaration must also specify prerequisite documents. For example:

> Вы должны прочитать «Проект Фрообус: Новая надежда» перед чтением этого документа.

<h2>Establish your key points up front</h2>

Engineers and scientists are busy people who won't necessarily read all 76 pages of your design document. Imagine that your peers might only read the first paragraph of page one. When reviewing your documentation, ensure that the start of your document answers your readers' essential questions.

Professional writers focus considerable energy on page one to increase the odds of readers making it to page two. However, page one of any long document is the hardest page to write. Therefore, be prepared to revise page one many times.

Always write an executive summary (a TL;DR) for long engineering documents. Although the executive summary must be very short, expect to spend a lot of time writing it. A boring or confusing executive summary is a red flag warning potential readers to stay away.

<h2>Напишите для своей аудитории</h2>

Этот курс неоднократно подчеркивает важность определения вашей аудитории. В этом разделе мы сосредоточимся на определении аудитории как средстве организации вашего документа.

<h3>Определите аудиторию</h3>

Ответы на следующие вопросы помогут вам определить, что должен содержать ваш документ:

- Кто ваша целевая аудитория?
- Что ваши читатели уже знают до того, как прочитают документ?
- Что ваши читатели должны знать или уметь делать после прочтения вашего документа?

Например, предположим, что вы изобрели новый алгоритм сортировки. Следующий список содержит некоторые возможные ответы на предыдущие вопросы:

- My target audience consists of all the software engineers in my organization.

- Большая часть моей целевой аудитории изучала алгоритмы сортировки в школе. Однако около 25% моей целевой аудитории не внедряли и не оценивали алгоритм сортировки в течение многих лет.

- После прочтения этого документа:

    1. Читатели знают, как работает алгоритм.
    2. Читатели могут реализовать алгоритм на желаемом языке.
    3. Читатели знают обстоятельства, при которых алгоритм превосходит популярный алгоритм быстрой сортировки.
    4. Читатели понимают снижение производительности в некоторых крайних случаях.

<h3>Организовать</h3>

После определения аудитории организуйте документ так, чтобы предоставить читателям то, что читатели должны знать или уметь делать после прочтения документа. Например, схема документа может выглядеть следующим образом:

1. Обзор алгоритма

    a. Big O

    б. Реализация в псевдокоде

2. Пример реализации на C

    а. Советы по реализации на других языках

3. Более глубокий анализ алгоритма

    а. Оптимальные наборы данных

    б. Проблемы с крайним случаем

Кроме того, используйте определение аудитории, чтобы выбрать правильный подход к написанию документа. Например, целевая аудитория изучала алгоритмы сортировки, но около четверти вашей аудитории может не помнить детали различных алгоритмов. Следовательно, ваш документ, вероятно, должен содержать ссылки на существующие руководства по быстрой сортировке, а не пытаться объяснить быструю сортировку.

<h2>Разбейте тему на разделы</h2>

You modularize code into files, classes, and methods. Modular code is easier to read, understand, maintain, and reuse. Making your document modular gives you the same benefits. You probably have strong intuition about functional modularity in code, but how do you apply those principles to your writing?

Представьте, что у вас есть пустая банка, которую вам нужно заполнить коллекцией из крупных камней, крупного гравия и песка. Как бы вы упаковали банку, чтобы в нее поместился весь материал? Конечно, сначала нужно положить большие камни, затем насыпать гравий и заполнить оставшееся воздушное пространство песком. Если вы попытаетесь сделать это в обратном порядке, у вас ничего не получится.

Your reader’s head is much like an empty jar, and your information generally comes in three sizes: rocks, gravel, and sand. Sections are the rocks. You need to structure the space inside your reader’s jar-head with the rocks to accept the rest of the information.

But how do you decide what is a big rock versus what is gravel? One strategy is to record yourself talking, or free-write, about your topic for a short amount of time—maybe just 2 to 5 minutes. Yes, this takes discipline. Examine what you produced. Did you do the following?

- Describe concepts in vague, under-specified ways?
- List the steps that your audience needs to complete to reach a goal?
- Describe the permutations of properties that a system can express?

The under-specified things that you referred to are probably the large concepts that structure your topic. If your talk didn’t do this, go back and try this structure.

<h3>Упражнение</h3>

The following passage is the introductory paragraph for a document. List the titles of the sections that you would break this topic into.

> AlienWarez is a large-scale machine learning system. AlienWarez is best at building models for high-dimensional, sparse feature spaces. AlienWarez automatically explores and learns feature crosses that explain your data. AlienWarez refers specifically to the model training system. You train a model by extracting features from your source (log) data, and writing a data source for the training system. The Seti infrastructure team also provides a complete serving system. You are responsible for starting your own serving cluster, and moving your model to serving. The Seti serving system can serve AlienWarez, Seti, and Sibyl models. This guide explains how to train a AlienWarez model, and how to serve the model in production.

<h3>Ответ</h3>

Вот возможный план:

1. Обучение модели

    а. Разработка функций

    б. Создание источника данных

    c. ...

2. Обслуживание модели

    а. Запуск обслуживающего кластера

    б. Перенос вашей модели на обслуживание

    c. Получение прогноза из обслуживания

    d. ...

**Next unit**: [Punctuation](Punctuation.md), an optional unit
