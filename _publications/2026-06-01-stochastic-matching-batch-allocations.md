---
title: "Stochastic Matching with Batch Allocations"
collection: publications
category: working
permalink: /publication/2026-06-01-stochastic-matching-batch-allocations
excerpt: 'A variant of stochastic matching in which agents receive batches of items: hardness-of-approximation results via new reductions, together with randomized approximation algorithms beating the classical 1 - 1/e ratio.'
date: 2026-06-01
venue: 'Undergraduate honors thesis, Stanford University'
citation: 'Michael Cho. &quot;Stochastic Matching with Batch Allocations.&quot; Undergraduate honors thesis, Stanford University, advised by Jan Vondrák. Work in progress.'
---

This project defines and studies a variation on stochastic matching problems in which agents receive *batches* of items rather than single items. The problem originated as a variant of online stochastic matching, but the offline version turns out to be an interesting variation on submodular welfare maximization in its own right.

I first proved hardness-of-approximation results using novel reductions from existing hardness results. In the course of that work, I observed that standard approaches — LP relaxations and continuous greedy — often perform poorly precisely in the instances where a global maximum matching does well. Exploiting this, I gave randomized approximation algorithms that beat the classical $1 - 1/e$ approximation ratio by taking the better of a global maximum matching and an LP relaxation.

This was my undergraduate honors thesis at Stanford, advised by Jan Vondrák. We have preliminary results improving the approximation ratio further, and the work is ongoing.
