---
title: Using the TypeScript compiler to fix erroneous Node. js snippets
authors:
- Brittany Reid
- Christoph Treude
- Markus Wagner
date: -01-01
publishDate: '2024-01-09T02:13:25.964238Z'
publication_types:
- paper-conference
publication: '*2023 IEEE 23rd International Working Conference on Source Code Analysis
  and Manipulation (SCAM)*'
doi: 10.1109/SCAM59687.2023.00031
abstract: 'Most online code snippets do not run. This means that developers looking
  to reuse code from online sources must manually find and fix errors. We present
  an approach for automatically evaluating and correcting errors in Node.js code snippets:
  Node Code Correction (NCC). NCC leverages the ability of the TypeScript compiler
  to generate errors and inform code corrections through the combination of TypeScript’s
  builtin codefixes, our own targeted fixes, and deletion of erroneous lines. Compared
  to existing approaches using linters, our findings suggest that NCC is capable of
  detecting a larger number of errors per snippet and more error types, and it is
  more efficient at fixing snippets. We find that 73.7% of the code snippets in NPM
  documentation have errors; with the use of NCC’s corrections, this number was reduced
  to 25.1%. Our evaluation confirms that the use of the TypeScript compiler to inform
  code corrections is a promising strategy to aid in the reuse of code snippets from
  online sources.'
tags:
- node.js
- static analysis
- error correction
- documentation
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10356712
---
