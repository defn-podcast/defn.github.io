---
layout: post
title:  "04 – Collections"
date:   2016-06-27 12:12:00
categories: Episodes
---

{% include soundcloud.html number="271111530" %}

<br>

## Summary
An overview of core and contributed collections and their use.

## Overview of Persistent Collections

- Immutable Persistent Collections
    - List vs Vector
    - Linked list vs tree implementation
    - Map vs Set
        - Key can be anything
        - KV \| Unique KV
- Relational operations on set are outside of core
- Seq library
    - ISeq (first, rest, cons)
- Interop with Java iterable
- Functions are written to work against the Seq interface
    - Seq in, Seq out
- Immutability and Persistence
    - What is it?
    - Why is it important?
    - Implementation notes
        - <a href="http://hypirion.com/musings/understanding-persistent-vector-pt-1" 
            target="_blank">Deep dive 1</a>
        - <a href="http://hypirion.com/musings/understanding-persistent-vector-pt-2" 
            target="_blank">Deep dive 2</a>
- Lazy collections
    - What does it mean to be lazy?
    - What does it mean to hold on the head?
        - Eager operations
- Sometimes you need side effects so you cannot be lazy
    - Doall, doseq
- Persistent vs. Transient
    - Performance
- Specter - Nathan Marz
    - Ensure output format of collection operations is controlled
    - Editing operations
    - <a href="https://www.youtube.com/watch?v=VTCy_DkAJGk" 
        target="_blank">Clojure West 2016 presentation</a> 

#### Community contributed collections - shout out to
- Chris Houser - <a href="https://github.com/clojure/data.zip/" target="_blank">Data.zip</a>
- Michał Marczyk - <a href="https://github.com/michalmarczyk/ctries.clj" target="_blank">Ctries</a> and 
<a href="https://github.com/clojure/data.avl" target="_blank">AVL</a>
- Mark Engelberg - <a href="https://github.com/clojure/data.priority-map/" target="_blank">Priority maps</a>
- Peter Schuck - Lean Hash Maps <a href=" https://www.youtube.com/watch?v=GibNOQVelFY" target="_blank">Clojure West 2016 
presentation</a>


