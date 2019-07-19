---
title: "TL;DS - Differential Privacy at Scale: Uber and Berkeley Collaboration"
date: 2018-10-06T19:28:31+01:00
draft: false
tags: ["tl;dr", "differential privacy", "systems"]
---

These are my notes from watching the video [Differential Privacy at Scale: Uber and Berkeley Collaboration](https://www.usenix.org/conference/enigma2018/presentation/ensign) presented at [Enigma 2018](https://www.usenix.org/conference/enigma2018/program).

### Attack Surface:

SQL Database with trips.

### Attacks:

- Internal: Inside the company analysts retrieving the data using SQL
- External: External query makers

### Solution

Chorus + DP


### Why Anonymization not a solution?

- It has limited utility
- Subject to re-identification attacks

### Challenges for Practical General-purpose DP

- Usability for non-experts
- Broad support for analytics queries
- Easy integration with existing infra (data environments)

### What does broad support mean?

- System that can deploy multiple mechanisms

### What is Chorus?

- Automatically enforces DP for SQL queries
- Modular to support various mechanisms (supports 93% queries in workload)
- Works with standard SQL DBs
- Deployed at Uber

### How it works?

- Takes a SQL query and modifies it to an intrinsic private query (IPQ)
- IPQ has embedded DP mechanisms

### Mechanisms

- [Elastic Sensitivity](https://arxiv.org/abs/1706.09479)
	+ Scale of noise is defined by elastic sensitivity, privacy budget
	+ This is determined using dataflow analysis of query
- Sample & Aggregate
	+ Calculates sensitivity of the query as the query executes
	+ Done by partitioning data and aggregating results in differentially private way
- WPINQ
- Restricted Sensitivity

#### Note

These together support 94% queries in the workload

### Terms to Read

- Winsorized mean
- Laplace Mechanism

### Evaluation

- 18,774 SQL Queries
- Less than 1% error by elastic sensitivity
- Median performance overhead of 1.7% on database of 800 million records

### Research Paper

[Chorus: Differential Privacy via Query Rewriting](https://arxiv.org/pdf/1809.07750.pdf)




