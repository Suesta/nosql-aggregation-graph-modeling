# NoSQL Aggregation and Graph Modeling

This repository presents an academic case study on **NoSQL data modeling**, with a particular focus on **aggregate-oriented design**, **graph reasoning**, **polyglot persistence**, and **architectural trade-offs** in data-intensive systems.

The work was developed as part of a Master's-level assignment in **Non-Relational Database Architectures** and is shared here as a compact portfolio project that highlights data modeling skills, query-driven design, and system-level reasoning.

## Project Overview

The project explores several core concepts in NoSQL and distributed data systems through realistic scenarios and structured design decisions.

Main topics covered include:

- NoSQL foundations and motivation
- Polyglot persistence
- Aggregate-oriented data models
- Key-value, document, and column-family models
- Graph data models
- Schemaless design trade-offs
- Query-driven aggregate design
- Horizontal partitioning and distribution strategies
- Architectural comparison between relational, NoSQL, and NewSQL systems

A practical modeling exercise is also included, where document aggregates are designed for a **gym activity tracking scenario** with query-oriented document structures.

## Repository Contents

```text
.
├── LICENSE
├── M2.889_Suesta_Victor_nosql_pec1.pdf
└── README.md
````

## Main Deliverable

The central document in this repository is:

* **`M2.889_Suesta_Victor_nosql_pec1.pdf`**
  A full case study covering theoretical and applied aspects of NoSQL architectures, including:

  * heterogeneous data and NoSQL motivation
  * schemaless trade-offs
  * aggregate-oriented models
  * graph-oriented reasoning
  * document aggregate design based on query patterns
  * consistency, replication, sharding, and NewSQL trade-offs

## Technical Focus

Although this is an academic deliverable, the project reflects several skills that are highly relevant in data science and data-focused engineering roles:

* **Data modeling:** translating domain requirements into efficient storage structures
* **Architectural reasoning:** choosing between relational, aggregate-oriented, and graph-oriented approaches
* **Query-oriented design:** modeling around access patterns instead of only normalized entities
* **Distributed systems awareness:** understanding replication, partitioning, consistency, and scalability trade-offs
* **Technical communication:** explaining design decisions in a structured and concise way

## Key Takeaways

This project reinforced an important idea that is also highly relevant in real-world data work:
the best data model depends not only on the data itself, but also on **how the data will be accessed, updated, and scaled**.

In particular, the case study highlights that:

* aggregate-oriented models work well when data is usually accessed as a single unit
* graph models are especially useful when relationships are central to the problem
* schemaless approaches provide flexibility, but move part of the structural control to the application layer
* distributed architectures often require explicit trade-offs between consistency, availability, and performance

## Academic Context

This repository contains work developed within a **Master's in Data Science** context, in the subject **Non-Relational Database Architectures**.

The goal of sharing it publicly is not only academic documentation, but also to showcase practical thinking around modern data architectures and modeling decisions.

## Author

**Víctor Suesta**
Mathematics graduate with a Data Science profile and strong interest in machine learning, data architecture, analytics, and applied AI.
