---
layout: project
title: Project
excerpt: ADAPQO
permalink: /projects/ADAPQO
name: Adaptive Query Optimization Architectures to Support Heterogeneous Data Intensive Applications
type: CMU
img:
status: Active
website: https://dbr-haslab.github.io/adapqo/
description:
partners:
external_collaborations:
financing:
region:  PT
classes: wide
sitemap: false
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
---


The state-of-the-art in query optimization is being challenged as developers create new DBMSs
to target new workloads and environments to meet the demands of the emerging data economy (e.g.,
GenAI applications). Building a query optimizer requires deep technical expertise and a long time
to mature. Moreover, machine learning can be used for key aspects of query optimization, such as
cardinality and cost estimation, and even search-space exploration. However, existing optimizers limit
the visibility into their inner state and the applicability of such techniques. Finally, instead of being
developed as vertically integrated systems, novel database systems are often assembled from a set of
open source components that do not always match the assumptions built in the optimizer, namely,
regarding relative costs, further reducing its usefulness.

Our approach to this challenge rests on the observation that query optimization is itself a large-
scale data processing problem and seeks to engineer the foundation for a next-generation open-source
query optimizer by designing a persistent and observable data-centric core that can be used as a service.
Having such an optimizer core can accelerate research and industrial product development in the data
platform space, as developers can simplify their design and tasks by using the new optimizer as a
service.