---
layout: post
title:  "06 - Concurrency and Parallelism"
date:   2016-07-25 12:12:00
categories: Episodes
---

{% include soundcloud.html number="275325675" %}

<br>

## Summary
A rambling discussion with the two village idiots struggling to come to terms with concurrency and parallelism

## Main discussion - Concurrency and Parallelism

### Things can happen at the same time - shocker! ;-)
- **Concurrency** - systems can be composed up from asynchronous actions - event driven!!
    - increases the amount of work that can be done on single threaded environments or single core machines
    - callbacks makes programming awkward ... there is a loss of comprehension, error handling is a big problem since 
    callbacks do not retain the original context
- **Parallelism** - problems are decomposed into discrete tasks or actions to fulfil a defined goal
    - usually only worth doing if the underlying hardware can run tasks in parallel
    - increases the amount of work that can be done on multi-threaded environments or multi-core / CPU / GPU machines

### Major innovations in Clojure
- Handling shared state: Dynamic Vars \| Atoms \| Refs \| Agents

#### Concurrency ... core.async
- Manifold and Aleph - Mr Zach Tellman - Lingua franca for asynchrony

#### Parallelism ... reducers
- Fundamentally, takes advantage of **trie** data structures
    - Unordered functions are applied over the sequence
    - Combining functions are associative

## Links
- <a href="https://vimeo.com/6624203" target="_blank">Guy Steele: Organizing Functional Code for Parallel Execution</a>
- <a href="http://clojure.org/reference/reducers" target="_blank">Rich Hickey: Reducers</a>

