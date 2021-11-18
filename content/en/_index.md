---
title: Patterns of Distributed Systems
type: docs
---

# Patterns of Distributed Systems

Official website address

Patterns of Distributed Systems

Distributed systems provide a particular challenge to program. They often require us to have multiple copies of data, which need to keep synchronized. Yet we cannot rely on processing nodes working reliably, and network delays can easily lead to inconsistencies. Despite this, many organizations rely on a range of core distributed software handling data storage, messaging, system management, and compute capability. These systems face common problems which they solve with similar solutions. This article recognizes and develops these solutions as patterns, with which we can build up an understanding of how to better understand, communicate and teach distributed system design.

## What this is about

For the last several months, I have been conducting workshops on distributed systems at Thoughtworks. One of the key challenges faced while conducting the workshops was how to map the theory of distributed systems to open source code bases such as Kafka or Cassandra, while keeping the discussions generic enough to cover a broad range of solutions. The concept of patterns provided a nice way out.

Pattern structure, by its very nature, allows us to focus on a specific problem, making it very clear why a particular solution is needed. Then the solution description enables us to give a code structure, which is concrete enough to show the actual solution but generic enough to cover a broad range of variations. This patterns technique also allows us to link various patterns together to build a complete system. This gives a nice vocabulary to discuss distributed system implementations.

What follows is a first set of patterns observed in mainstream open source distributed systems. I hope that this set of patterns will be useful to all developers.
