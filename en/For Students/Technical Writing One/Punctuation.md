<h1>Punctuation (optional)</h1>

> Estimated Time: 5 minutes

This optional unit provides a quick refresher on punctuation marks.

<h2>Commas</h2>

Programming languages enforce clear rules about punctuation. In English, by contrast, the rules regarding commas are somewhat hazier. As a guideline, insert a comma wherever a reader would naturally pause somewhere within a sentence. For the musically inclined, if a period is a whole note rest, then a comma is perhaps a half-note or quarter-note rest. In other words, the pause for a comma is shorter than that for a period. For example, if you read the following sentence aloud, you probably rest briefly before the word *just*:

> C behaves as a mid-level language, just a couple of steps up in abstraction from assembly language.

Some situations *require* a comma. For example, use commas to separate items in an embedded list like the following:

> Our company uses C++, Python, Java, and JavaScript.

You might be wondering about a list's final comma, the one inserted between items N-1 and N. This comma—known as the **serial comma** or **Oxford comma** —is controversial. We recommend supplying that final comma simply because technical writing requires picking the least ambiguous solution. That said, we actually prefer circumventing the controversy by converting embedded lists into bulleted lists.

In sentences that express a condition, place a comma between the condition and the consequence. For example, both of the following sentences supply the comma in the correct place:

> If the program runs slowly, try the --perf flag.

> If the program runs slowly, then try the --perf flag.

You can also wedge a quick definition or digression between a pair of commas as in the following example:

> Python, an easy-to-use language, has gained significant momentum in recent years.

Finally, avoid using a comma to paste together two independent thoughts. For example, the comma in the following sentence is guilty of a punctuation felony called a **comma splice**:

> Samantha is a wonderful coder, she writes abundant tests.

Use a period rather than a comma to separate two independent thoughts. For example:

> Samantha is a wonderful coder. She writes abundant tests.

<h3>Exercise</h3>

Add commas where appropriate to the following passage:

> Protocol Buffers sometimes known as protobufs are our team's main structured data format. Use Protocol Buffers to represent store and transfer structured data. Unlike XML Protocol Buffers are compiled. Consequently clients transmit Protocol Buffers efficiently which has led to rapid adoption.

Hint: Read the passage aloud and put a comma everywhere you hear a short pause.

<h3>Answer</h3>

Here is one possible solution:

> Protocol Buffers, sometimes known as protobufs, are our team's main structured data format. Use Protocol Buffers to represent, store, and transfer structured data. Unlike XML, Protocol Buffers are compiled. Consequently, clients transmit Protocol Buffers efficiently, which has led to rapid adoption.

<h2>Semicolons</h2>

A period separates distinct thoughts; a semicolon unites highly related thoughts. For example, notice how the semicolon in the following sentence unites the first and second thoughts:

> Rerun Frambus after updating your configuration file; don't rerun Frambus after updating existing source code.

The thoughts preceding and following the semicolon must each be grammatically complete sentences. For example, the following semicolon is incorrect because the passage following the semicolon is not a complete sentence:

> Rerun Frambus after updating your configuration file; not after updating existing source code.

Before using a semicolon, ask yourself whether the sentence would still make sense if you flipped the thoughts to opposite sides of the semicolon. For example, reversing the earlier example still yields a valid sentence:

> Don't rerun Frambus after updating existing source code; rerun Frambus after updating your configuration file.

You should almost always use commas, not semicolons, to separate items in an embedded list. For example, the following use of semicolons is incorrect:

> Style guides are bigger than the moon; more essential than oxygen; and completely inscrutable.

Many sentences place a transition word or phrase immediately after the semicolon. In this situation, place a comma after the transition. Note the comma after the transition in the following two examples:

> Frambus provides no official open source package for string manipulation; however, subsets of string manipulation packages are available from other open source projects.

> Even seemingly trivial code changes can cause bugs; therefore, write abundant unit tests.

<h3>Exercise</h3>

Which of the following periods or commas could you replace with a semicolon?

1. Python is a popular programming language. The C language was developed long before Python.
2. Model learning for a low value of X appears in the top illustration. Model learning for a high value of X appears in the bottom illustration.
3. I'm thankful for my large monitor, powerful CPU, and blazing bandwidth.

<h3>Answer</h3>

1. You may not convert the period in #1 to a semicolon because the two sentences are only vaguely related.
2. You may replace the period in #2 with a semicolon because the two sentences are so highly related.
3. You may not convert the commas in #3 to semicolons. Use commas to separate items in an embedded list.

<h2>Em-Dashes</h2>

Em-dashes are compelling punctuation marks, rich with punctuation possibilities. An em-dash represents a longer pause—a bigger break—than a comma. If a comma is a quarter note rest, then an em-dash is a half-note rest. For example:

> C++ is a rich language—one requiring extensive experience to master.

Writers sometimes use a pair of em-dashes to block off a digression, as in the following example:

> **Protocol Buffers** — often nicknamed **protobufs** — encode structured data in an efficient yet extensible format.

Could we have used commas instead of em-dashes in the preceding examples? Sure. Why did we choose an em-dash instead of a comma? Feel. Art. Experience. Remember—punctuation in English is squishy and malleable.

<h2>Parentheses</h2>

Use parentheses to hold minor points and digressions. Parentheses inform readers that the enclosed text isn't critical.

The rules regarding periods and parentheses have tripped up many a writer. Here are the standards:

* If a pair of parentheses holds an entire sentence, the period goes inside the closing parenthesis.
* If a pair of parentheses ends a sentence but does not hold the entire sentence, the period goes just outside the closing parenthesis.

For example:

> (Incidentally, Protocol Buffers make great birthday gifts.)

> Binary mode relies on the more compact native form (described later in this document).

**Next unit**: [Markdown](Markdown.md)
