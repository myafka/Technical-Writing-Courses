# Lists and tables

> Estimated Time: 15 minutes

Хорошие списки могут превратить технический хаос в нечто упорядоченное. Технические читатели обычно любят списки. Поэтому когда пишите, ищите возможности преобразовать прозу в списки.

## Choose the correct type of list

Следующие типы списков чаще всего используются в технической документации:

- bulleted lists
- numbered lists
- вложенные списки

Используйте **маркированный список** для *неупорядоченных* элементов; используйте **нумерованный список** для *упорядоченных* элементов. Другими словами:

- If you rearrange the items in a *bulleted* list, the list's meaning does not change.
- If you rearrange the items in a *numbered* list, the list's meaning changes. For example, we've made the following a bulleted list because rearranging its items does not change the list's meaning:

> Bash provides the following string manipulation mechanisms:
> - deleting a substring from the start of a string
> - reading an entire file into one string variable

Следующий список, напротив, должен быть нумерованным, потому что перестановка его элементов изменит смысл списка:

> Take the following steps to reconfigure the server:
> 1. Stop the server.
> 2. Edit the configuration file.
> 3. Restart the server.

**Вложенный список** (иногда называемый **перечисление**) содержит элементы чучел в предложении. Например, следующее предложение содержит встроенный список из четырех элементов.

> API llamacatcher позволяет вызывающим абонентам создавать лам и запрашивать их, анализировать альпак, удалять викуний и отслеживать дромадеров.

Вообще говоря, вложенные списки — плохой способ представления технической информации. Попробуйте преобразовать вложенные списки в маркированные или нумерованные списки. Например, вы должны преобразовать предложение, содержащее вложенный список, в такой отрывок:

> API llamacatcher позволяет вызывающим абонентам:
> - Создавать и запрашивать лам.
> - Анализировать альпак.
> - Удалять викуний.
> - Отслеживать дромадеров.

### Exercise

Convert the following paragraph into one or more lists:

> Сегодня на работе мне нужно написать три модульных теста, написать проектный документ и просмотреть последний документ Джанет. После работы я должен помыть машину без воды, а затем высушить ее без полотенец.

Не забудьте представить свой список(списки).

### Answer

Here's one possible answer:

> I must do the following at work today:
> - Написать три модульных теста.
> - Написать дизайн-документ.
> - Просмотреть последний документ Джанет.
> After work, I must do the following:
> 1. Помыть машину без воды.
> 2. Высушить машину без полотенец.

А вот другой ответ:

> I must do the following tasks today:
> - At work:
>     - Написать три модульных теста.
>     - Написать дизайн-документ.
>     - Просмотреть последний документ Джанет.
> - After work:
>     1. Помыть машину без воды.
>     2. Высушить машину без полотенец.

## Keep list items parallel

Что отличает эффективные списки от дефектных? Эффективные списки **параллельны**; дефектные списки обычно не параллельны. Все элементы в параллельном списке выглядят так, как будто они «принадлежат» друг другу. То есть все элементы в параллельном списке совпадают по параметрам:

- grammar
- logical category
- регистр
- punctuation

Conversely, at least one item in a **nonparallel** list fails at least one of the preceding consistency checks.

Например, следующий список является параллельным, потому что все элементы являются существительными во множественном числе (грамматика), съедобными (логическая категория), со строчной буквы (регистр) и без точек и запятых (пунктуация).

- моркови
- картофеля
- капусты

By contrast, the following list is painfully nonparallel along all four parameters:

- моркови
- картофеля
- The summer light obscures all memories of winter.

Следующий список является параллельным, потому что все элементы представляют собой полные предложения с заглавными буквами и знаками препинания:

- Carrots contain lots of Vitamin A.
- Potatoes taste delicious.
- Cabbages provide oodles of Vitamin K.

The first item in a list establishes a pattern that readers expect to see repeated in subsequent items.

### Exercise

Is the following list parallel or nonparallel?

- Broccoli inspires feelings of love or hate.
- Potatoes taste delicious.
- Cabbages.

### Answer

The list is nonparallel. The first two items are complete sentences, but the third item is not a sentence. (Don't be fooled by the capitalization and punctuation of the third item.)

### Exercise

Is the following list parallel or nonparallel?

- The red dots represent sick trees.
- Immature trees are represented by the blue dots.
- The green dots represent healthy trees.

### Answer

This is a nonparallel list. The first and third items are in active voice, but the second item is in passive voice.

## Start numbered list items with imperative verbs

Попробуйте начать все элементы в нумерованном списке с повелительного наклонения. **Глаголы в повелительном наклонении** — это команда, например **откройте** или **начните**. Например, обратите внимание, как все элементы в следующем списке с параллельной нумерацией начинаются с повелительного глагола:

1. Download the Frambus app from Google Play or iTunes.
2. Configure the Frambus app's settings.
3. Start the Frambus app.

Следующий нумерованный список не является параллельным, потому что два предложения начинаются с повелительного глагола, а третье предложение — нет:

1. Instantiate the Froobus class.
2. Invoke the Froobus.Salmonella() method.
3. The process stalls.

### Exercise

Сделайте следующий список параллельным. Убедитесь, что в результате каждый элемент в списке начинается с повелительного глагола:

1. Остановите Frambus
2. Ключевой файл конфигурации — `/etc/frambus` . Откройте этот файл в текстовом редакторе ASCII.
3. In this file, you will see a parameter named Carambola, which is currently set to the default value (32). Change this value to 64.
4. When you are finished setting this parameter, save and close the configuration file
5. теперь запустите Frambus снова.

### Answer

The following is one possible answer:

1. Остановите Frambus.
2. Open the key configuration file, `/etc/frambus`, with an ASCII text editor.
3. Change the Carambola parameter from its default value (32) to 64.
4. Save and close the configuration file.
5. Restart Frambus.

## Punctuate items appropriately

Если элементом списка является предложение, используйте заглавные буквы и знаки препинания. В противном случае не используйте заглавные буквы и знаки препинания. Например, следующий элемент списка является предложением, поэтому мы используем заглавную **У** в **У большинства** и ставим точку в конце предложения:

- Most carambolas have five ridges.

Однако, следующий элемент списка не является предложением, поэтому мы оставили **ц** в **цвет** в нижнем регистре и убрали точку:

- the color of lemons

## Create useful tables

Аналитические умы любят таблицы. На странице, содержащей несколько абзацев и одну таблицу, взгляд инженеров останавливается на таблице.

Consider the following guidelines when creating tables:

- Обозначьте каждый столбец осмысленным заголовком. Не заставляйте читателей догадываться, что содержит каждый столбец.
- Не помещайте слишком много текста в ячейку таблицы. Если в ячейке таблицы содержится более двух предложений, спросите себя, может лучше использовать другой формат для этой информации.
- Although different columns can hold different types of data, strive for parallelism within individual columns. For instance, the cells within a particular table column should not be a mixture of numerical data and famous circus elephants.

> **Примечание**. Некоторые таблицы не отображаются во всех форматах. Например, таблицы, которая отлично смотрится на вашем ноутбуке, может выглядеть ужасно на вашем телефоне.

## Introduce each list and table

Мы рекомендуем, для каждого списка и таблицы писать вводное предложение, которое сообщает читателям, что это за список или таблица. Другими словами, укажите контекст списка или таблицы. Заканчивайте вводное предложение двоеточием, а не точкой.

Хотя это и не является обязательным требованием, мы рекомендуем во вводном предложении вставить слово **«следующее»**. Например, рассмотрим следующие вводные предложения:

> The following list identifies key performance parameters:

> Take the following steps to install the Frambus package:

> The following table summarizes our product's features against our key competitors' features:

### Exercise

Write an introductory sentence for the following table:

Languages | Inventor | Year Introduced | Key Feature
--- | --- | --- | ---
Lisp | John McCarthy | 1958 | recursion
C++ | Bjarne Stroustrup | 1979 | OOP
Python | Guido van Rossum | 1994 | simplicity

### Answer

Here are a couple of possible introductory sentences for the table:

> The following table contains a few key facts about some popular programming languages:

> The following table identifies the inventor, year of invention, and key feature of three popular programming languages:

**Следующий блок**: [Абзацы](Paragraphs.md)
