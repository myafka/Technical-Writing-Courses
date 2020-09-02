# Punctuation (optional)

> Расчетное время: 5 минут

Этот дополнительный модуль позволяет быстро вспомнить знаки препинания.

## Запятые

Programming languages enforce clear rules about punctuation. In English, by contrast, the rules regarding commas are somewhat hazier. As a guideline, insert a comma wherever a reader would naturally pause somewhere within a sentence. For the musically inclined, if a period is a whole note rest, then a comma is perhaps a half-note or quarter-note rest. In other words, the pause for a comma is shorter than that for a period. For example, if you read the following sentence aloud, you probably rest briefly before the word *just*:

> C behaves as a mid-level language, just a couple of steps up in abstraction from assembly language.

Some situations *require* a comma. For example, use commas to separate items in an embedded list like the following:

> Наша компания использует C ++, Python, Java и JavaScript.

You might be wondering about a list's final comma, the one inserted between items N-1 and N. This comma—known as the **serial comma** or **Oxford comma** —is controversial. We recommend supplying that final comma simply because technical writing requires picking the least ambiguous solution. That said, we actually prefer circumventing the controversy by converting embedded lists into bulleted lists.

В предложениях, выражающих условие, ставьте запятую между условием и следствием. Например, оба следующих предложения ставят запятую в правильном месте:

> Если программа работает медленно, попробуйте флаг --perf.

> If the program runs slowly, then try the --perf flag.

Вы также можете вставить быстрое определение или отступление между запятыми, как в следующем примере:

> Python, простой в использовании язык, в последние годы набирает обороты.

Finally, avoid using a comma to paste together two independent thoughts. For example, the comma in the following sentence is guilty of a punctuation felony called a **comma splice**:

> Саманта прекрасный программист, она пишет множество тестов.

Для разделения двух независимых мыслей используйте точку, а не запятую. Например:

> Samantha is a wonderful coder. She writes abundant tests.

### Упражнение

При необходимости добавьте запятые к следующему отрывку:

> Protocol Buffers sometimes known as protobufs are our team's main structured data format. Use Protocol Buffers to represent store and transfer structured data. Unlike XML Protocol Buffers are compiled. Consequently clients transmit Protocol Buffers efficiently which has led to rapid adoption.

Подсказка: прочтите отрывок вслух и ставьте запятую везде, где вы слышите короткую паузу.

### Ответ

Вот одно из возможных решений:

> Буферы протокола, иногда известные как protobufs, являются основным форматом структурированных данных нашей команды. Используйте буферы протокола для представления, хранения и передачи структурированных данных. В отличие от XML, буферы протокола компилируются. Следовательно, клиенты эффективно передают буферы протокола, что привело к быстрому внедрению.

## Точка с запятой

Точка разделяет отдельные мысли; точка с запятой объединяет тесно связанные мысли. Например, обратите внимание, как точка с запятой в следующем предложении объединяет первую и вторую мысли:

> Перезапустите Frambus после обновления файла конфигурации; не запускайте Frambus повторно после обновления существующего исходного кода.

Мысли, предшествующие и следующие за точкой с запятой, должны быть грамматически законченными предложениями. Например, следующая точка с запятой неверна, потому что отрывок, следующий за точкой с запятой, не является полным предложением:

> Перезапустите Frambus после обновления файла конфигурации; не после обновления существующего исходного кода.

Before using a semicolon, ask yourself whether the sentence would still make sense if you flipped the thoughts to opposite sides of the semicolon. For example, reversing the earlier example still yields a valid sentence:

> Не запускайте заново Frambus после обновления существующего исходного кода; перезапустите Frambus после обновления файла конфигурации.

You should almost always use commas, not semicolons, to separate items in an embedded list. For example, the following use of semicolons is incorrect:

> Руководства по стилю больше луны; важнее кислорода; и совершенно непостижимо.

Many sentences place a transition word or phrase immediately after the semicolon. In this situation, place a comma after the transition. Note the comma after the transition in the following two examples:

> Frambus provides no official open source package for string manipulation; however, subsets of string manipulation packages are available from other open source projects.

> Even seemingly trivial code changes can cause bugs; therefore, write abundant unit tests.

### Упражнение

Какие из следующих точек или запятых вы можете заменить точкой с запятой?

1. Python is a popular programming language. The C language was developed long before Python.
2. Обучение модели для низкого значения X показано на верхнем рисунке. Обучение модели для высокого значения X показано на нижнем рисунке.
3. Я благодарен за свой большой монитор, мощный процессор и невероятную пропускную способность.

### Ответ

1. Вы не можете преобразовать точку в # 1 в точку с запятой, потому что эти два предложения связаны лишь смутно.
2. Вы можете заменить точку в # 2 точкой с запятой, потому что эти два предложения очень связаны.
3. Вы не можете преобразовывать запятые в # 3 в точку с запятой. Используйте запятые для разделения элементов во встроенном списке.

## Em-Dashes

Em-dashes are compelling punctuation marks, rich with punctuation possibilities. An em-dash represents a longer pause—a bigger break—than a comma. If a comma is a quarter note rest, then an em-dash is a half-note rest. For example:

> C++ is a rich language—one requiring extensive experience to master.

Writers sometimes use a pair of em-dashes to block off a digression, as in the following example:

> **Protocol Buffers** — often nicknamed **protobufs** — encode structured data in an efficient yet extensible format.

Could we have used commas instead of em-dashes in the preceding examples? Sure. Why did we choose an em-dash instead of a comma? Feel. Art. Experience. Remember—punctuation in English is squishy and malleable.

## Скобки

Используйте круглые скобки для мелких замечаний и отступлений. Скобки информируют читателей о том, что прилагаемый текст не критичен.

Правила относительно точек и скобок сбивают с толку многих писателей. Вот стандарты:

- If a pair of parentheses holds an entire sentence, the period goes inside the closing parenthesis.
- Если пара скобок завершает предложение, но не содержит всего предложения, точка выходит за пределы закрывающей скобки.

Например:

> (Incidentally, Protocol Buffers make great birthday gifts.)

> Двоичный режим основан на более компактной собственной форме (описанной далее в этом документе).

**Next unit**: [Markdown](Markdown.md)
