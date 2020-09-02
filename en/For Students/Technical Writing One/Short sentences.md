# Short sentences

> Estimated Time: 20 minutes

Software engineers generally try to minimize the number of lines of code in an implementation for the following reasons:

* Shorter code is typically easier for others to read.
* Shorter code is typically easier to maintain than longer code.
* Extra lines of code introduce additional points of failure.

In fact, the same rules apply to technical writing:

* Shorter documentation reads faster than longer documentation.
* Shorter documentation is typically easier to maintain than longer documentation.
* Extra lines of documentation introduce additional points of failure.

Finding the shortest documentation implementation takes time but is ultimately worthwhile. Short sentences communicate more powerfully than long sentences, and short sentences are usually easier to understand than long sentences.

## Focus each sentence on a single idea

Focus each sentence on a single idea, thought, or concept. Just as statements in a program execute a single task, sentences should execute a single idea. For example, the following very long sentence contains multiple thoughts:

> The late 1950s was a key era for programming languages because IBM introduced Fortran in 1957 and John McCarthy introduced Lisp the following year, which gave programmers both an iterative way of solving problems and a recursive way.

Breaking the long sentence into a succession of single-idea sentences yields the following result:

> The late 1950s was a key era for programming languages. IBM introduced Fortran in 1957. John McCarthy invented Lisp the following year. Consequently, by the late 1950s, programmers could solve problems iteratively or recursively.

### Exercise

Convert the following overly long sentence to a series of shorter sentences. Don't revise too much; just end up with a few sentences instead of only one.

> In bash, use the if, then, and fi statements to implement a simple conditional branching block in which the if statement evaluates an expression, the then statement introduces a block of statements to run when the if expression is true, and the fi statement marks the end of the conditional branching block.

### Answer

In bash, use an `if`, `then`, and `fi` statement to implement a simple conditional branching block. The `if` statement evaluates an expression. The `then` statement introduces a block of statements to run when the `if` expression is true. The `fi` statement marks the end of the conditional branching block. (The resulting paragraph remains unclear but is still much easier to read than the original sentence.)

## Convert some long sentences to lists

Inside many long technical sentences is a list yearning to break free. For example, consider the following sentence:

> To alter the usual flow of a loop, you may use either a **break** statement (which hops you out of the current loop) or a **continue** statement (which skips past the remainder of the current iteration of the current loop).

When you see the conjunction **or** in a long sentence, consider refactoring that sentence into a bulleted list. When you see an embedded list of items or tasks within a long sentence, consider refactoring that sentence into a bulleted or numbered list. For example, the preceding example contains the conjunction **or**, so let's convert that long sentence to the following bulleted list:
----

To alter the usual flow of a loop, call one of the following statements:

* `break`, which hops you out of the current loop.
* `continue`, which skips past the remainder of the current iteration of the current loop.

### Exercise

Refactor the following sentences into something shorter and clearer. Make sure that your answer contains a list:

1. To get started with the Frambus app, you must first find the app at a suitable store, pay for it using a valid credit or debit card, download it, configure it by assigning a value for the `Foo` variable in the `/etc/Frambus` file, and then run it by saying the magic word twice.
2. KornShell was invented by David Korn in 1983, then a computer scientist at Bell Labs, as a superset of features, enhancements, and improvements over the Bourne Shell (which it was backwards compatible with), which was invented by Stephen Bourne in 1977 who was also a computer scientist at Bell Labs.

### Answer

Take the following steps to get started with the Frambus app:

1. Find the app at a suitable store.
2. Pay for the app using a valid credit or debit card.
3. Download the app.
4. Configure the app by assigning a value for the Foo variable in the `/etc/Frambus` file.
5. Run the app by saying the magic word twice.

The following two Bell Labs computer scientists invented popular shells:

* Stephen Bourne invented the Bourne Shell in 1977.
* David Korn invented the KornShell in 1983.

The KornShell's features are a backwards-compatible superset of the Bourne Shell's.

## Eliminate or reduce extraneous words

Many sentences contain filler—textual junk food that consumes space without nourishing the reader. For example, see if you can spot the unnecessary words in the following sentence:

> An input value greater than 100 causes the triggering of logging.

Replacing **causes the triggering of** with the much shorter verb **triggers** yields a shorter sentence:

> An input value greater than 100 triggers logging.

With practice, you'll spot the extraneous words and take inordinate glee in removing or reducing them. For example, consider the following sentence:

> This design document provides a detailed description of Project Frambus.

The phrase **provides a detailed description of** reduces to the verb **details**, so the resulting sentence becomes:

> This design document details Project Frambus.

The following table suggests replacements for a few common bloated phrases:

Wordy  | Concise
------------- | -------------
at this point in time | now
determine the location of  | find
is able to | can

### Exercise

Shorten the following sentences without changing their meaning:

1. In spite of the fact that Arnold writes buggy code, he writes error-free documentation.
2. Changing the sentence from passive voice to active voice enhances the clarification of the key points.
3. Determine whether Rikona is able to write code in COBOL.
4. Frambus causes the production of bugs, which will be chronicled in logs by the LogGenerator method.

### Answer

Here are some possible solutions:

1. Although Arnold writes buggy code, he writes error-free documentation.
    **Alternative answer**: Arnold writes buggy code. However, he writes error-free documentation.
2. Changing the sentence from passive voice to active voice clarifies the key points.
3. Determine whether Rikona can code in COBOL.
4. Frambus produces bugs, which the LogGenerator method logs.

## Reduce subordinate clauses (optional)

A **clause** is an independent logical fragment of a sentence, which contains an actor and an action. Every sentence contains the following:

* a main clause
* zero or more subordinate clauses

Subordinate clauses modify the idea in the main clause. As the name implies, subordinate clauses are less important than the main clause. For example, consider the following sentence:

> Python is an interpreted programming language, which was invented in 1991.

> * main clause: Python is an interpreted programming language
> * subordinate clause: which was invented in 1991

You can usually identify subordinate clauses by the words that introduce them. The following list (by no means complete) shows common words that introduce subordinate clauses:

* which
* that
* because
* whose
* until
* unless
* since

Some subordinate clauses begin with a comma and some don't. The highlighted subordinate clause in the following sentence, for example, begins with the word *because* and does not contain a comma:

> I prefer to code in C++ because I like strong data typing.

When editing, scrutinize subordinate clauses. Keep the `one sentence = one idea` formula in mind. Do the subordinate clauses in a sentence *extend* the single idea or do they *branch off* into a separate idea? If the latter, consider dividing the offending subordinate clause(s) into separate sentences.

### Exercise

Determine which of the sentences contain subordinate clauses that should be branched off into separate sentences. (Don't rewrite the sentences, just identify the sentences that should be rewritten.)

1. Python is an interpreted language, which means that the language can execute source code directly.
2. Bash is a modern shell scripting language that takes many of its features from KornShell 88, which was developed at Bell Labs.
3. Lisp is a programming language that relies on Polish prefix notation, which is one of the systems invented by the Polish logician Jan Łukasiewicz.
4. I don't want to say that Fortran is old, but only radiocarbon dating can determine its true age.

### Answer

We've shaded the subordinate clauses.

1. Python is an interpreted language, which means that the language can execute source code directly. **The subordinate clause in this sentence extends the main idea, so this sentence is fine as is.**
2. Bash is a modern shell scripting language that takes many of its features from KornShell 88, which was developed at Bell Labs. **The first subordinate clause extends the main idea, but the second subordinate clause goes in another direction. Divide this sentence in two.**
3. Lisp is a programming language that relies on Polish prefix notation, which is one of the systems invented by the Polish logician Jan Łukasiewicz. **The first subordinate clause is clearly critical to the sentence, but the second subordinate clause takes the reader too far away from the main clause. Divide this sentence in two.**
4. I don't want to say that Fortran is old, but only radiocarbon dating can determine its true age. **The subordinate clause is critical to the sentence, so this sentence is fine as is.**

## Distinguish that from which

**That** and **which** both introduce subordinate clauses. What's the difference between them? Well, in some countries, the two words are pretty much interchangeable. Inevitably though, alert readers from the United States will angrily announce that you confused the two words again.

In the United States, reserve **which** for nonessential subordinate clauses, and use **that** for an essential subordinate clause that the sentence can't live without. For example, the key message in the following sentence is that Python is an interpreted language; the sentence can survive without *Guido van Rossum invented*:

> Python is an interpreted language, **which** Guido van Rossum invented.

By contrast, the following sentence requires *don't involve linear algebra*:

> Fortran is perfect for mathematical calculations **that** don't involve linear algebra.

If you read a sentence aloud and hear a pause just before the subordinate clause, then use **which**. If you don't hear a pause, use **that**. Go back and read the preceding two example sentences. Do you hear the pause in the first sentence?

Place a comma before **which**; do not place a comma before **that**.


**Next unit**: [Lists and tables](Lists%20and%20tables.md)
