# Transformer25

This repository contains all the code and data for our SemEval‑2025 submission for the multimodal idiomaticity task (Task 
ADMIRE: Advancing Multimodal Idiomaticity Representation ), where the goal is to pair idiomatic expressions with image
descriptions that convey their meanings. We tackle the two text‑only subtasks (Subtask A - Static Images and Subtask B - Image
Sequences) through a minimal similarity‑based pipeline, combining embeddings from pre‑trained BERT language models with 
ChatGPT‑generated additional text. By measuring semantic similarity in this enriched embedding space, we investigate how
effectively large language models can capture the non‑compositional nuances of idioms, which is, an ability that is crucial for
avoiding downstream misinterpretations.
