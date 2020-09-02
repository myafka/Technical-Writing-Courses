# Lists and tables

> Estimated Time: 15 minutes

Good lists can transform technical chaos into something orderly. Technical readers generally love lists. Therefore, when writing, seek opportunities to convert prose into lists.

## Choose the correct type of list

The following types of lists dominate technical writing:

* bulleted lists
* numbered lists
* embedded lists

Use a **bulleted list** for *unordered* items; use a **numbered list** for *ordered* items. In other words:

* If you rearrange the items in a *bulleted* list, the list's meaning does not change.
* If you rearrange the items in a *numbered* list, the list's meaning changes.
For example, we've made the following a bulleted list because rearranging its items does not change the list's meaning:

> Bash provides the following string manipulation mechanisms:
> 
> * deleting a substring from the start of a string
> * reading an entire file into one string variable

The following list, by contrast, must be a numbered list because rearranging its items would change the list's meaning:

> Take the following steps to reconfigure the server:
> 
> 1. Stop the server.
> 2. Edit the configuration file.
> 3. Restart the server.

An **embedded list** (sometimes called a **run-in** list) contains items stuffed within a sentence. For example, the following sentence contains an embedded list with four items.

> The llamacatcher API enables callers to create and query llamas, analyze alpacas, delete vicugnas, and track dromedaries.

Generally speaking, embedded lists are a poor way to present technical information. Try to transform embedded lists into either bulleted lists or numbered lists. For example, you should convert the sentence containing the embedded list into the following passage:

> The llamacatcher API enables callers to do the following:
> 
> * Create and query llamas.
> * Analyze alpacas.
> * Delete vicugnas.
> * Track dromedaries.

### Exercise

Convert the following paragraph into one or more lists:

> Today at work, I have to code three unit tests, write a design document, and review Janet's latest document. After work, I have to wash my car without using any water and then dry it without using any towels.

Don't forget to introduce your list(s).

### Answer

Here's one possible answer:

> I must do the following at work today:
> 
> * Code three unit tests.
> * Write a design document.
> * Review Janet's latest document.
>
> After work, I must do the following:
> 
> 1. Wash my car without using any water.
> 2. Dry my car without using any towels.

The following is an alternative answer:

> I must do the following tasks today:
> 
> * At work:
>     * Code three unit tests.
>     * Write a design document.
>     * Review Janet's latest document.
> * After work:
>     1. Wash my car without using any water.
>     2. Dry my car without using any towels.

## Keep list items parallel

What separates effective lists from defective lists? Effective lists are **parallel**; defective lists tend to be nonparallel. All items in a parallel list look like they "belong" together. That is, all items in a parallel list match along the following parameters:

* grammar
* logical category
* capitalization
* punctuation

Conversely, at least one item in a **nonparallel** list fails at least one of the preceding consistency checks.

For example, the following list is parallel because all the items are plural nouns (grammar), edible (logical category), lower case (capitalization), and without periods or commas (punctuation).

* carrots
* potatoes
* cabbages

By contrast, the following list is painfully nonparallel along all four parameters:

* carrots
* potatoes
* The summer light obscures all memories of winter.

The following list is parallel because all the items are complete sentences with complete sentence capitalization and punctuation:

* Carrots contain lots of Vitamin A.
* Potatoes taste delicious.
* Cabbages provide oodles of Vitamin K.

The first item in a list establishes a pattern that readers expect to see repeated in subsequent items.

### Exercise

Is the following list parallel or nonparallel?

* Broccoli inspires feelings of love or hate.
* Potatoes taste delicious.
* Cabbages.

### Answer

The list is nonparallel. The first two items are complete sentences, but the third item is not a sentence. (Don't be fooled by the capitalization and punctuation of the third item.)

### Exercise

Is the following list parallel or nonparallel?

* The red dots represent sick trees.
* Immature trees are represented by the blue dots.
* The green dots represent healthy trees.

### Answer

This is a nonparallel list. The first and third items are in active voice, but the second item is in passive voice.

## Start numbered list items with imperative verbs

Consider starting all items in a numbered list with an imperative verb. An **imperative verb** is a command, such as **open** or **start**. For example, notice how all of the items in the following parallel numbered list begin with an imperative verb:

1. Download the Frambus app from Google Play or iTunes.
2. Configure the Frambus app's settings.
3. Start the Frambus app.

The following numbered list is nonparallel because two of the sentences start with an imperative verb, but the third item does not:

1. Instantiate the Froobus class.
2. Invoke the Froobus.Salmonella() method.
3. The process stalls.

### Exercise

Make the following list parallel. Ensure that each element in the result list begins with an imperative verb:

1. Stop Frambus
2. The key configuration file is ```/etc/frambus```. Open this file with an ASCII text editor.
3. In this file, you will see a parameter named Carambola, which is currently set to the default value (32). Change this value to 64.
4. When you are finished setting this parameter, save and close the configuration file
5. now, start Frambus again.

### Answer

The following is one possible answer:

1. Stop Frambus.
2. Open the key configuration file, ```/etc/frambus```, with an ASCII text editor.
3. Change the Carambola parameter from its default value (32) to 64.
4. Save and close the configuration file.
5. Restart Frambus.

## Punctuate items appropriately

If the list item is a sentence, use sentence capitalization and punctuation. Otherwise, do not use sentence capitalization and punctuation. For example, the following list item is a sentence, so we capitalized the **M** in **Most** and put a period at the end of the sentence:

* Most carambolas have five ridges.

However, the following list item is not a sentence, so we left the **t** in **the** in lowercase and omitted a period:

* the color of lemons

## Create useful tables

Analytic minds tend to love tables. Given a page containing multiple paragraphs and a single table, engineers' eyes zoom towards the table.

Consider the following guidelines when creating tables:

* Label each column with a meaningful header. Don't make readers guess what each column holds.
* Avoid putting too much text into a table cell. If a table cell holds more than two sentences, ask yourself whether that information belongs in some other format.
* Although different columns can hold different types of data, strive for parallelism within individual columns. For instance, the cells within a particular table column should not be a mixture of numerical data and famous circus elephants.

> **Note**: Some tables don't render well across all form factors. For example, a table that looks great on your laptop may look awful on your phone.

## Introduce each list and table

We recommend introducing each list and table with a sentence that tells readers what the list or table represents. In other words, give the list or table context. Terminate the introductory sentence with a colon rather than a period.

Although not a requirement, we recommend putting the word **following** into the introductory sentence. For example, consider the following introductory sentences:

> The following list identifies key performance parameters:

> Take the following steps to install the Frambus package:

> The following table summarizes our product's features against our key competitors' features:

### Exercise

Write an introductory sentence for the following table:

Languages  | Inventor| Year Introduced| Key Feature
------------- | -------------| -------------| -------------
Lisp  | John McCarthy | 1958 | recursion
C++  | Bjarne Stroustrup | 1979 | OOP
Python  | Guido van Rossum | 1994| simplicity

### Answer

Here are a couple of possible introductory sentences for the table:

> The following table contains a few key facts about some popular programming languages:
> The following table identifies the inventor, year of invention, and key feature of three popular programming languages:


**Next unit**: [Paragraphs](Paragraphs.md)

