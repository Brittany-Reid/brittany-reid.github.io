---
title: Improving Developer Efficiency through Code Reuse
authors:
- Brittany Reid
date: '2023-01-01'
publishDate: '2024-01-09T05:20:42.945311Z'
publication_types:
- thesis
abstract: Code reuse is an integral part of modern software development, where most
  software is built using existing software artefacts. Ranging from the copy-pasting
  of code fragments to the use of third-party libraries, developers frequently turn
  to the internet to find already-made solutions to difficult programming tasks and
  save development time. However, the large amount of libraries and code online can
  make finding the best solution difficult, and reuse is not necessarily straightforward.
  Most online code snippets do not run, meaning developers need to spend time correcting
  errors, and when example code snippets are meant to demonstrate API usage, this
  can present a barrier to using new libraries. This work studies ways to aid developers
  in the code reuse process, in order to improve their efficiency. We look at ways
  to more easily connect developers to the wealth of libraries and usage examples
  online from within their programming environment with our tool for Node.js, Node
  Code Query (NCQ). We then evaluate how well developers perform compared to the conventional
  code reuse process and found that developers using our tool solve tasks faster and
  have to try fewer libraries. Additionally, we study what problems online Node.js
  code snippets have and how to best correct them automatically, to save developers
  time in this step of the reuse process. We find that through the combination of
  the TypeScript compiler’s error detection and codefixes, and our line deletion and
  custom fixes, we can increase the percentage error-free snippets in our dataset
  from 26.3% to 74.94%. Finally, we compare the emerging AI code snippet generation
  and pair programmer technologies to current online code snippet reuse practices,
  particularly looking at how snippets generated by GitHub’s Copilot extension and
  those retrieved from Stack Overflow using Google might differ. We find that for
  the same set of queries, Copilot returned more snippets, with fewer errors and that
  were more relevant. Ultimately, this work provides further evidence of how automating
  the code reuse process can improve developer efficiency, and proposes a series of
  solutions to that end. Additionally, we provide a comparison between existing and
  emerging reuse processes. As the state of code reuse changes, helping developers
  understand the strengths of weaknesses of these approaches will become increasingly
  important.
tags:
- software engineering
- code reuse
- code correction
- code generation
- code search
- static analysis
- node.js
- javascript
- java
- python
links:
- name: URL
  url: https://hdl.handle.net/2440/139921
---