---
title: "RoutineHub: A Framework for Persona-Conditioned Activity Chain Generation via Structured Templates and RAG-Augmented LLM Refinement"
collection: publications
category: manuscripts
permalink: /publication/routinehub
excerpt: 'An end-to-end activity chain generation framework combining symbolic reasoning and deep learning to predict personalized daily routines.'
date: 2025-07-01
venue: 'Travel Behaviour and Society (In Preparation)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: '<b>Y. Sang</b>, Y. Tang, A. Qu, and J. Zhao. "RoutineHub: A Framework for Persona-Conditioned Activity Chain Generation via Structured Templates and RAG-Augmented LLM Refinement." <i>Manuscript prepared for submission to Travel Behaviour and Society</i>.'
---

## Abstract

This paper presents RoutineHub, an end-to-end activity chain generation framework that combines symbolic reasoning and deep learning to predict personalized daily routines. Using the Singapore HITS2012 dataset (21,936 users, 85,882 trips), we developed a dual-architecture system: (1) a Transformer-based sequence-to-sequence model with joint activity-time prediction and temporal consistency constraints; (2) an LLM-augmented retrieval system with template-guided generation and uncertainty modeling. We implemented rare pattern mining with Bernoulli modeling and boosting mechanisms to capture low-frequency behavioral patterns, expanding the activity taxonomy from 15 to 27 types through LLM-based subdivision. The system achieves fine-grained temporal modeling with 15-minute precision slots and persona-based conditioning, incorporating demographic features, workday patterns, and activity dependencies for realistic schedule generation.

## Key Contributions

- Designed end-to-end activity chain generation framework combining symbolic reasoning and deep learning
- Engineered dual-architecture system: Transformer seq2seq model + LLM-augmented retrieval
- Implemented rare pattern mining with Bernoulli modeling and boosting mechanisms
- Achieved fine-grained temporal modeling with 15-minute precision slots
- Expanded activity taxonomy from 15 to 27 types through LLM-based subdivision

## Advisor

Professor Jinhua Zhao, Massachusetts Institute of Technology (MIT)

