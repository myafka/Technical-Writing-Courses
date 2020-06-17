<h1>Clear sentences</h1>

>Estimated Time: 10 minutes

Comedy writers seek the funniest results, horror writers strive for the scariest, and technical writers aim for the clearest. In technical writing, clarity takes precedence over all other rules. This unit suggests a few ways to make your sentences beautifully clear.

<h2>Choose strong verbs</h2>

Many technical writers believe that the verb is the most important part of a sentence. Pick the right verb and the rest of the sentence will take care of itself. Unfortunately, some writers reuse only a small set of mild verbs, which is like serving your guests stale crackers and soggy lettuce every day. Picking the right verb takes a little more time but produces more satisfying results.

To engage and educate readers, choose precise, strong, specific verbs. Reduce imprecise, weak, or generic verbs, such as the following:

* forms of be: is, are, am, was, were, etc.
* occur
* happen

For example, consider how strengthening the weak verb in the following sentences ignites a more engaging sentence:

Weak Verb | Strong Verb
The error occurs when clicking the Submit button.| Clicking the Submit button **triggers** the error.
This error message **happens** when... | The system **generates** this error message when...
We **are** very careful to ensure... | We carefully **ensure**...

Many writers rely on forms of be as if they were the only spices on the rack. Sprinkle in different verbs and watch your prose become more appetizing. That said, a form of be is sometimes the best choice of verb, so don't feel that you have to eliminate every form of be from your writing.

Note that generic verbs often signal other ailments, such as:

* an imprecise or missing actor in a sentence
* a passive voice sentence

<h3>Exercise</h3>

Clarify the following sentences by picking more specific verbs. Along the way, feel free to rearrange the sentences and to add, modify, or delete words:

1. When a variable declaration doesn't have a datatype, a compiler error happens.
2. Compiler errors occur when you leave off a semicolon at the end of a statement.

<h3>Answer</h3>

1. A few possible answers:
  * When a variable declaration doesn't **specify** a datatype, the compiler **generates** an error message.
  * If you **declare** a variable but don't **specify** a datatype, the compiler **generates** an error message.
2. A few possible answers:
  * Compilers **issue** errors when you **omit** a semicolon at the end of a statement.
  * A missing semicolon at the end of a statement **triggers** compiler errors.
  
-----

<h2>Reduce there is/there are</h2>

Sentences that start with **There is** or **There are** marry a generic noun to a generic verb. Generic weddings bore readers. Show true love for your readers by providing a real subject and a real verb.

In the best case scenario, you may simply delete **There is** or **There are** (and possibly another word or two later in the sentence). For example, consider the following sentence:

> There is a variable called `met_trick` that stores the current accuracy.

Removing **There is** replaces the generic subject with a better subject. For example, either of the following sentences is clearer than the original:

> A variable named `met_trick` stores the current accuracy.

> The `met_trick` variable stores the current accuracy.

You can sometimes repair a **There is** or **There are** sentence by moving the true subject and true verb from the end of the sentence to the beginning. For example, notice that the pronoun **you** appears towards the end of the following sentence:

> There are two disturbing facts about Perl you should know.

Replacing **There are** with **You** strengthens the sentence:

> You should know two disturbing facts about Perl.

In still other situations, writers start sentences with **There is** or **There are** to avoid the hassle of creating true subjects or verbs. If no subject exists, consider creating one. For example, the following **There is** sentence does not identify the receiving entity:

> There is no guarantee that the updates will be received in sequential order.

Replacing "There is" with a meaningful subject (such as **clients**) creates a clearer experience for the reader:

> Clients might not receive the updates in sequential order.

<h3>Exercise</h3>

Clarify the following sentences by removing **There is**, and possibly rearranging, adding, modifying, or deleting other words:

1. There is a lot of overlap between X and Y.
2. There is no creator stack for the main thread.
3. There is a low-level, TensorFlow, Python interface to load a saved model.
4. There is a sharding function named `distribute` that assigns keys.

<h3>Answer</h3>

1. X and Y overlap a lot.
2. The main thread does not provide a creator stack.
3. TensorFlow provides a low-level Python interface to load a saved model.
4. The `distribute` sharding function assigns keys.

----

<h2>Minimize certain adjectives and adverbs (optional)</h2>

Adjectives and adverbs perform amazingly well in fiction and poetry. Thanks to adjectives, plain old grass becomes **prodigal** and **verdant**, while lifeless hair transforms into something **silky** and **flowing**. Adverbs push horses to run **madly** and **freely** and dogs to bark **loudly** and **ferociously**. Unfortunately, adjectives and adverbs sometimes make technical readers bark loudly and ferociously. That's because adjectives and adverbs tend to be too loosely defined and subjective for technical readers. Worse, adjectives and adverbs can make technical documentation sound dangerously like marketing material. For example, consider the following passage from a technical document:

>Setting this flag makes the application run screamingly fast.

Granted, **screamingly fast** gets readers attention but not necessarily in a good way. Feed your technical readers factual data instead of marketing speak. Refactor amorphous adverbs and adjectives into objective numerical information. For example:

>Setting this flag makes the application run 225-250% faster.

Does the preceding change strip the sentence of some of its charm? Yes, a little, but the revamped sentence gains accuracy and believability.

> **Note**: Don't confuse educating your readers (technical writing) with publicizing or selling a product (marketing writing). When your readers expect education, provide education; don't intersperse publicity or sales material inside educational material.


**Next unit**: Short sentences
