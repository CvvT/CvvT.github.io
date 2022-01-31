---
title: "SyzScope: Revealing High-Risk Security Impacts of Fuzzer-Exposed Bugs in Linux kernel"
collection: publications
permalink: /publication/2021-11-11-usenix_zou
excerpt: 'In this paper, we develop SyzScope, a system that can automatically uncover new" high-risk" impacts given a bug with seemingly" low-risk" impacts.'
date: 2021-11-11
venue: 'USENIX Security Symposium '
paperurl: 'http://CvvT.github.io/files/sec22summer_zou.pdf'
---
Fuzzing has become one of the most effective bug finding approach for software. In recent years, 24*7 continuous fuzzing platforms have emerged to test critical pieces of software, eg, Linux kernel. Though capable of discovering many bugs and providing reproducers (eg, proof-of-concepts), a major problem is that they neglect a critical function that should have been built-in, ie, evaluation of a bug's security impact. It is well-known that the lack of understanding of security impact can lead to delayed bug fixes as well as patch propagation. In this paper, we develop SyzScope, a system that can automatically uncover new" high-risk" impacts given a bug with seemingly" low-risk" impacts. From analyzing over a thousand low-risk bugs on syzbot, SyzScope successfully determined that 183 low-risk bugs (more than 15%) in fact contain high-risk impacts, eg, control flow hijack and arbitrary memory write, some of which still do not have patches available yet.

[Download paper here](http://CvvT.github.io/files/sec22summer_zou.pdf)