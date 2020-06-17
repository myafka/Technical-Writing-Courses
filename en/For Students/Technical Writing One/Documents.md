<h1>Documents</h1>

> Estimated Time: 10 minutes

You can write sentences. You can write paragraphs. However, can you organize all those paragraphs into a coherent document?

<h2>State your document's scope</h2>

A good document begins by defining its scope. For example:

> This document describes the overall design of Project Frambus.

A better document additionally defines its non-scope, that is, the topics not covered that the target audience might expect your document to cover. For example:

> This document does not describe the design for the related technology, Project Froobus.

These scope and non-scope statements benefit not only the reader but also the writer (you). While writing, if the contents of your document veer away from the scope statement, then you must either refocus your document or modify your scope statement. When reviewing your first draft, delete (or branch off to another document) any sections that don't help satisfy the scope statement.

<h2>State your audience</h2>

A good document explicitly specifies its audience. For example:

> I wrote this document for the test engineers supporting Project Frambus.

Beyond the audience's role, a good audience declaration might also specify any prerequisite knowledge or experience. For example:

> This document assumes that you understand matrix multiplication and how to brew a really good cup of tea.

In some cases, the audience declaration must also specify prerequisite documents. For example:

> You must read "Project Froobus: A New Hope" prior to reading this document.

<h2>Establish your key points up front</h2>

Engineers and scientists are busy people who won't necessarily read all 76 pages of your design document. Imagine that your peers might only read the first paragraph of page one. When reviewing your documentation, ensure that the start of your document answers your readers' essential questions.

Professional writers focus considerable energy on page one to increase the odds of readers making it to page two. However, page one of any long document is the hardest page to write. Therefore, be prepared to revise page one many times.

Always write an executive summary (a TL;DR) for long engineering documents. Although the executive summary must be very short, expect to spend a lot of time writing it. A boring or confusing executive summary is a red flag warning potential readers to stay away.

<h2>Write for your audience</h2>

This course repeatedly emphasizes the importance of defining your audience. In this section, we focus on audience definition as a means of organizing your document.

<h3>Define audience</h3>

Answering the following questions helps you determine what your document should contain:

* Who is your target audience?
* What do your readers already know before they’ve read the document?
* What should your readers know or be able to do after they’ve read your document?

For example, suppose you have invented a new sorting algorithm. The following list contains some potential answers to the preceding questions:

* My target audience consists of all the software engineers in my organization.
* Most of my target audience studied sorting algorithms during school. However, about 25% of my target audience hasn't implemented or evaluated a sorting algorithm in many years.
* After reading this document:

    1. Readers know how the algorithm works.
    2. Readers can implement the algorithm in their desired language.
    3. Readers know the circumstances in which the algorithm outperforms the popular quicksort algorithm.
    4. Readers understand performance degradation in certain edge cases.

<h3>Organize</h3>

After defining the audience, organize the document to supply what readers should know or be able to do after reading the document. For example, the outline for the document could look as follows:

1. Overview of the algorithm

    a. Big O
  
    b. Implementation in pseudocode
  
2. Sample implementation in C

   a. Tips in implementing in other languages
  
3. Deeper analysis of algorithm

    a. Optimal datasets
    
    b. Edge case problems
  
Furthermore, use the audience definition to help you choose the right approach to writing your document. For example, the target audience studied sorting algorithms but about a quarter of your audience might not remember the details of different algorithms. Therefore, your document should probably insert links to existing tutorials on quicksort rather than trying to explain quicksort.

<h2>Break your topic into sections</h2>

You modularize code into files, classes, and methods. Modular code is easier to read, understand, maintain, and reuse. Making your document modular gives you the same benefits. You probably have strong intuition about functional modularity in code, but how do you apply those principles to your writing?

Imagine that you have an empty jar, which you need to pack with a collection of large rocks, coarse gravel, and sand. How would you pack the jar to ensure that you can get all of your material in the jar? Of course you’d place the large rocks first, then pour in the gravel, and fill in the remaining air space with the sand. If you tried to do this in the opposite order, you would fail.

Your reader’s head is much like an empty jar, and your information generally comes in three sizes: rocks, gravel, and sand. Sections are the rocks. You need to structure the space inside your reader’s jar-head with the rocks to accept the rest of the information.

But how do you decide what is a big rock versus what is gravel? One strategy is to record yourself talking, or free-write, about your topic for a short amount of time—maybe just 2 to 5 minutes. Yes, this takes discipline. Examine what you produced. Did you do the following?

* Describe concepts in vague, under-specified ways?
* List the steps that your audience needs to complete to reach a goal?
* Describe the permutations of properties that a system can express?

The under-specified things that you referred to are probably the large concepts that structure your topic. If your talk didn’t do this, go back and try this structure.

<h3>Exercise</h3>

The following passage is the introductory paragraph for a document. List the titles of the sections that you would break this topic into.

> AlienWarez is a large-scale machine learning system. AlienWarez is best at building models for high-dimensional, sparse feature spaces. AlienWarez automatically explores and learns feature crosses that explain your data. AlienWarez refers specifically to the model training system. You train a model by extracting features from your source (log) data, and writing a data source for the training system. The Seti infrastructure team also provides a complete serving system. You are responsible for starting your own serving cluster, and moving your model to serving. The Seti serving system can serve AlienWarez, Seti, and Sibyl models. This guide explains how to train a AlienWarez model, and how to serve the model in production.

<h3>Answer</h3>

Here is a possible outline:

1. Training a model

    a. Developing features
  
    b. Creating a data source
  
    c. ...
  
2. Serving a model

    a. Starting a serving cluster
  
    b. Moving your model into serving
  
    c. Retrieving a prediction from serving
  
    d. ...
  


**Next unit**: [Punctuation](Punctuation.md), an optional unit
