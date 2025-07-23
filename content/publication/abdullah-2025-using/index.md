---
title: 'Using LLMs for Security Advisory Investigations: How Far are We?'
authors:
- Bayu Fedra Abdullah
- Yusuf Sulistyo Nugroho
- Brittany Reid
- Raula Gaikovina Kula
- Kazumasa Shimari
- Kenichi Matsumoto
date: '2025-06-01'
publishDate: '2025-07-23T05:21:01.949006Z'
publication_types:
- paper-conference
publication: '*2025 International Conference on Smart Computing, IoT and Machine Learning
  (SIML)*'
doi: 10.1109/SIML65326.2025.11080876
abstract: Large Language Models (LLMs) are increasingly used in software security,
  but their trustworthiness in generating accurate vulnerability advisories remains
  uncertain. This study investigates the ability of ChatGPT to (1) generate plausible
  security advisories from CVE-IDs, (2) differentiate real from fake CVE-IDs, and
  (3) extract CVE-IDs from advisory descriptions. Using a curated dataset of 100 real
  and 100 fake CVE-IDs, we manually analyzed the credibility and consistency of the
  model's outputs. The results show that ChatGPT generated plausible security advisories
  for 96 % of given input real CVE-IDs and $mathbf9 7 %$ of given input fake CVE-IDs,
  demonstrating a limitation in differentiating between real and fake IDs. Furthermore,
  when these generated advisories were reintroduced to ChatGPT to identify their original
  CVE-ID, the model produced a fake CVEID in 6% of cases from real advisories. These
  findings highlight both the strengths and limitations of ChatGPT in cybersecurity
  applications. While the model demonstrates potential for automating advisory generation,
  its inability to reliably authenticate CVE-IDs or maintain consistency upon re-evaluation
  underscores the risks associated with its deployment in critical security tasks.
  Our study emphasizes the importance of using LLMs with caution in cybersecurity
  workflows and suggests the need for further improvements in their design to improve
  reliability and applicability in security advisory generation.
tags:
- Training;Accuracy;Large language models;Refining;Machine learning;Chatbots;Reliability
  engineering;Software;Prompt engineering;Computer security;advisory;chatgpt;cve id;security;vulnerability
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/11080876
---
