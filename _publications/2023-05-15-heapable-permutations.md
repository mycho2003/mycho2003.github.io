---
title: "Efficient Methods of Calculating the Number of Heapable Permutations"
collection: publications
category: manuscripts
permalink: /publication/2023-05-15-heapable-permutations
excerpt: 'An exact counting algorithm for heapable permutations, improving on the previously best-known factorial-time algorithm.'
date: 2023-05-15
venue: 'Discrete Applied Mathematics'
citation: 'B. Chen, M. Cho, M. Tutuncu-Macias, and T. Tzolov. &quot;Efficient methods of calculating the number of heapable permutations.&quot; <i>Discrete Applied Mathematics</i> 331 (2023), pp. 126&ndash;137.'
---

Heapable permutations arise from a variation on the Longest Increasing Subsequence problem based on heaps. Our main result is an exact counting algorithm with runtime $O(n^3 1.74^n)$, improving on the best previously known algorithm, which ran in $O(n!)$ time.

I discovered a key connection between the Motzkin numbers and the algorithm's runtime, which allowed us to prove our time complexity. I also found several symmetry results in the counting scheme and completed the proof of a core lemma, leading to improved upper and lower bounds.

The work began as a group project at PROMYS, on a topic proposed by Professor Michael Mitzenmacher, and led to a new sequence contributed to the OEIS.
