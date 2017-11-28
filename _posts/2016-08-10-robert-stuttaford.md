---
layout: post
title:  "#07 – Datomic with Robert Stuttaford"
date:   2016-08-10 12:12:00
categories: Episodes
---

{% include soundcloud.html number="277716719" %}

<br>

## Summary

A tour of Datomic and a field report from Robert - a leading edge production pioneer.

## Discusssion

- Why Clojure at Cognician?
- Wow - the Cognician Stack though
- Why Datomic?
    - Datomic production readiness
    - Datomic Architecture
    - Querying with Datomic
    - Database queries across time (past, present and future)
    - Datomic schemas - pros and cons
- Production scale at Cognician
    - Tooling - the REPL and Clojure
    - Scaling Datomic (esp caching)
    - Transactor (incl serialisation)
    - Storage backends (and interchangeability!)
    - What is the Pro support like?
    - Options for Licensing Datomic
- The awesome POWER of Temporal data
        - <a href="https://en.wikipedia.org/wiki/SQL:2011" target="_blank">ANSI SQL2011</a>
    - Excision - can Datomic forget me?
    - Annotated transactions - auditing and troubleshooting
    - Ctrl-Z in a database!!
- Database functions
- Licensing model, planning and the cloud
- Drivers for JVM / Non-JVM clients (REST API)
- Datascript (Nikita Prokopov)

## Links

### Learning resources:

- <a href="http://www.learndatalogtoday.org" target="_blank">Learn Datalog</a>
- <a href="http://www.datomic.com/training.html" target="_blank">Datomic training</a>
- <a href="https://github.com/clojure-cookbook/clojure-cookbook/tree/master/06_databases"
     target="_blank">Clojure cookbook on databases</a>
- <a href="http://tonsky.me/blog/unofficial-guide-to-datomic-internals/"
     target="_blank">Datomic internals (unofficial)</a>
- <a href="https://clojurians.slack.com" target="_blank">#datomic on Clojurians Slack</a>
- <a href="https://groups.google.com/forum/#!forum/datomic" target="_blank">Datomic Google group</a>

### References

- <a href="https://github.com/tonsky/rum"
     target="_blank">Using Datascript and Rum, by tonsky (Nikita Prokopov), another star Cognician developer</a>
- <a href="https://github.com/robert-stuttaford/stuttaford.me/blob/master/src/stuttaford/client/components/codex.cljs"
     target="_blank">Codex - By Robert</a>
