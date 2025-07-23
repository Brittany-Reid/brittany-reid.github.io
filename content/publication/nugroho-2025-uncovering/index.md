---
title: Uncovering Intention Through LLM-Driven Code Snippet Description Generation
authors:
- Yusuf Sulistyo Nugroho
- Farah Danisha Salam
- Brittany Reid
- Raula Gaikovina Kula
- Kazumasa Shimari
- Kenichi Matsumoto
date: '2025-01-01'
publishDate: '2025-07-23T05:21:01.983451Z'
publication_types:
- paper-conference
publication: '*2025 International Conference on Smart Computing, IoT and Machine Learning
  (SIML)*'
doi: 10.1109/SIML65326.2025.11081156
abstract: Documenting code snippets is essential to pinpoint key areas where both
  developers and users should pay attention. Examples include usage examples and other
  Application Programming Interfaces (APIs), which are especially important for third-party
  libraries. With the rise of Large Language Models (LLMs), the key goal is to investigate
  the kinds of description developers commonly use and evaluate how well an LLM, in
  this case Llama, can support description generation. We use NPM Code Snippets, consisting
  of 185,412 packages with 1,024,579 code snippets. From there, we use 400 code snippets
  (and their descriptions) as samples. First, our manual classification found that
  the majority of original descriptions (55.5%) highlight example-based usage. This
  finding emphasizes the importance of clear documentation, as some descriptions lacked
  sufficient detail to convey intent. Second, the LLM correctly identified the majority
  of original descriptions as “Example” (79.75%), which is identical to our manual
  finding, showing a propensity for generalization. Third, compared to the originals,
  the produced description had an average similarity score of 0.7173, suggesting relevance
  but room for improvement. Scores below 0.9 indicate some irrelevance. Our results
  show that depending on the task of the code snippet, the intention of the document
  may differ from being instructions for usage, installations, or descriptive learning
  examples for any user of a library.
tags:
- Codes;Large language models;Documentation;Machine learning;Libraries;code snippets;description;readme
  files;software documentation
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/11081156
---
