# LLMs for Topic Segmentation

This repository is a Latex report for research work into the use of generative LLMs for topic segmentation

### Motivation

[Adarga](https://adarga.ai) is a London-based company that sells products aiming to speed up the process of intelligence analysis. They process thousands of long documents in order to extract keywords, relationships, metadata and context. A user can then query this unstructured data in a variety of ways, including generating reports, Q&A with a chatbot or 

In order to make this possible, very long documents must first be split up into smaller segments which fit within the context length of Adarga's fine-tuned models. This task was already being done by BERT-based sentence similarity, but we were tasked with investigating if generative LLMs can be prompted to give better segments.

### Authors
This research project was conducted over the summer of 2023 at [Adarga](https://adarg.ai). It was completed in 12 weeks, as a collaboration between two interns: [myself (Pierre Mackenzie)]((https://pierre.wiki)) as a data scientist and [Maya Shah](https://www.linkedin.com/in/maya--shah/) as a SWE, under the supervision of research scientists [Patrick Frenett](https://www.linkedin.com/in/patrick-frenett/) and [Alex Nim](https://alexnim.com/about.html).

It was written up by me over the following months as a paper-style report, although I no longer had access to the codebase.