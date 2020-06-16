<h1>Words</h1>

>Estimated Time: 10 minutes

We researched documentation extensively, and it turns out that the best sentences in the world consist primarily of words.

<h2>Define new or unfamiliar terms</h2>

When writing or editing, learn to recognize terms that might be unfamiliar to some or all of your target audience. When you spot such a term, take one of the following two tactics:

* If the term already exists, link to a good existing explanation. (Don't reinvent the wheel.)

* If your document is introducing the term, define the term. If your document is introducing many terms, collect the definitions into a glossary.

<h2>Use terms consistently</h2>

If you change the name of a variable midway through a method, your code won’t compile. Similarly, if you rename a term in the middle of a document, your ideas won’t compile (in your users’ heads).

The moral: apply the same unambiguous word or term consistently throughout your document. Once you've named a component **thingy**, don't rename it **thingamabob**. For example, the following paragraph mistakenly renames **Protocol Buffers** to **protobufs**:

> Protocol Buffers provide their own definition language. Blah, blah, blah. And that's why protobufs have won so many county fairs.

Yes, technical writing is cruel and restrictive, but at least technical writing provides an excellent workaround. Namely, when introducing a long-winded concept name or product name, you may also specify a shortened version of that name. Then, you may use that shortened name throughout the document. For example, the following paragraph is fine:

> **Protocol Buffers** (or **protobufs** for short) provide their own definition language. Blah, blah, blah. And that's why protobufs have won so many county fairs.

<h2>Use acronyms properly</h2>

On the initial use of an unfamiliar acronym within a document or a section, spell out the full term, and then put the acronym in parentheses. Put both the spelled-out version and the acronym in boldface. For example:

> This document is for engineers who are new to the **Telekinetic Tactile Network** (**TTN**) or need to understand how to order TTN replacement parts through finger motions.

You may then use the acronym going forward, as in the following example:

> If no cache entry exists, the Mixer calls the **OttoGroup Server** (**OGS**) to fetch Ottos for the request. The OGS is a repository that holds all servable Ottos. The OGS is organized in a logical tree structure, with a root node and two levels of leaf nodes. The OGS root forwards the request to the leaves and collects the responses.

Do not cycle back-and-forth between the acronym and the expanded version in the same document.

<h3>Use the acronym or the full term?</h3>

Sure, you can introduce and use acronyms properly, but *should* you use acronyms? Well, acronyms do reduce sentence size. For example, *TTN* is two words shorter than *Telekinetic Tactile Network*. However, acronyms are really just a layer of abstraction; readers must mentally expand recently learned acronyms to the full term. For example, readers convert *TTN* to *Telekinetic Tactile Network* in their heads, so the "shorter" acronym actually takes a little longer to process than the *full* term.

Heavily used acronyms develop their own identity. After a number of occurrences, readers generally stop expanding acronyms into the full term. Many Web developers, for example, have forgotten what *HTML* expands to.

Here are the guidelines for acronyms:

* Don't define acronyms that would only be used a few times.
* Do define acronyms that meet both of the following criteria:
  * The acronym is significantly shorter than the full term.
  * The acronym appears many times in the document.

<h3>Exercise</h3>

Fix the following passage. Assume that this passage is the initial instance of the term **MapReduce** in the document and that **MR** is the best abbreviation.

> Jeff Dean invented MapReduce in 1693, implementing the algorithm on a silicon-based computer fabricated from beach sand, wax-paper, a quill pen, and a toaster oven. This version of MR held several world performance records until 2014.

(Please note that the preceding passage is meant to be humorous, not factual.)

<h3>Answer</h3>

You could take a few different approaches here. One approach is to associate the acronym MR with the full term and then use that acronym:

> Jeff Dean invented **MapReduce** (**MR**) in... This version of MR held several...

Alternatively, you could decide that defining an acronym for such a short passage puts too much burden on readers, so you'll simply use the full term MapReduce every time:

> Jeff Dean invented **MapReduce** in... This version of MapReduce held several...

Incidentally, a more thorough technical writer would also convert "beach sand, wax-paper, a quill pen, and a toaster oven" into a bulleted list. However, that's another story for another lesson.

---

<h2>Disambiguate pronouns</h2>

Many pronouns point to a previously introduced noun. Such pronouns are analogous to pointers in programming. Like pointers in programming, pronouns tend to introduce errors. Improperly using pronouns causes the cognitive equivalent of a null pointer error in your readers’ heads. In many cases, you should simply avoid the pronoun and just reuse the noun. However, the utility of a pronoun sometimes outweighs its risk (as in this sentence).

Consider the following pronoun guidelines:

* Only use a pronoun *after* you've introduced the noun; never use the pronoun before you've introduced the noun.
* Place the pronoun as close as possible to the referring noun. In general, if more than five words separate your noun from your pronoun, consider repeating the noun instead of using the pronoun.
* If you introduce a second noun between your noun and your pronoun, reuse your noun instead of using a pronoun.

<h3>It and they</h3>

The following pronouns cause the most confusion in technical documentation:

* it
* they, them, and their

For example, in the following sentence, does **It** refer to Python or to C++?

> Python is interpreted, while C++ is compiled. **It** has an almost cult-like following.

As another example, what does **their** refer to in the following sentence?

> Be careful when using Frambus or Carambola with HoobyScooby or BoiseFram because a bug in **their** core may cause accidental mass unfriending.

<h3>This and that</h3>

Consider two additional problem pronouns:

* this

* that

For example, in the following ambiguous sentence, **This** could refer to Frambus, to Foo, or to both:

> You may use either Frambus or Foo to calculate derivatives. **This** is not optimal.

Use either of the following tactics to disambiguate **this** and **that**:

* Replace **this** or **that** with the appropriate noun.

* Place a noun immediately after **this** or **that**.

For example, either of the following sentences disambiguate the previous example:

> **Overlapping functionality** is not optimal.

> **This overlapping functionality** is not optimal.

<h3>Exercise</h3>

Identify all possible meanings for the ambiguous pronouns in each of the following passages:

1. Aparna and Phil share responsibilities with Maysam and Karan and they are the next ones on call.

2. You may import Carambola data via your configuration file or dynamically at run time. This may be a security risk.

<h3>Answer</h3>

1. The pronoun **they** could refer to any of the following:

  * Aparna and Phil
  * Maysam and Karan
  * Aparna, Phil, Maysam, and Karan
  
2. The pronoun **this** could refer to any of the following:

  * importing via the configuration file
  * importing dynamically at run time
  * both


**Next unit**: Active voice
