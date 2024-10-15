# README: Learning LLM, Grammar-Constrained Decoding, and SPARQL

Welcome to my journey into the world of advanced AI and NLP concepts, focusing on Large Language Models (LLMs), Grammar-Constrained Decoding (GCD), and SPARQL for querying knowledge graphs. This repository documents my learning process, insights, and practical implementations in these fields.

## Overview

This repository contains my progress and projects as I explore:

- **Knowledge Graphs**: Learning the fundamentals of knowledge representation and using SPARQL to interact with and query data in knowledge graphs.
- **Large Language Models (LLMs)**: Understanding tokenization, fine-tuning, and prompt engineering.
- **Grammar-Constrained Decoding (GCD)**: Guiding language models to generate structured output without fine-tuning.
- **SPARQL**: Using SPARQL to query and navigate knowledge graphs.

Each section provides insights, learning notes, and project links showcasing practical implementations.

## Large Language Models (LLMs)

### Tokenization

Tokenization is a fundamental part of working with LLMs. It involves breaking down text into smaller units called tokens (words, subwords, or characters). I explored various types of tokenization, including:

- **Word, Subword, Character, and Sentence Tokenization**
- **Byte-Pair Encoding (BPE)**: An efficient way to compress input text sequences.

**Projects**:
- https://github.com/monirmo97/LLM/blob/main/Tokenizer.ipynb
- https://github.com/monirmo97/LLM/blob/main/Different_Type_of_tokenization.ipynb

### Fine-Tuning

Fine-tuning involves training pre-trained models further to adapt them to specific tasks. I experimented with several methods:

- **Full Fine-Tuning**: Updating the entire model.
- **Parameter Efficient Fine-Tuning (PEFT)**: Reducing computational needs by updating a subset of parameters.
- **LoRA and QLoRA**: Fine-tuning approaches that only modify smaller matrices, preserving efficiency.

**Projects**:
- https://github.com/monirmo97/LLM/tree/main/Train_Test_GPT2
- https://github.com/monirmo97/LLM/tree/main/Train_Test_GPT2/gpt2-finetune-freeze
- https://github.com/monirmo97/LLM/tree/main/Train_Test_GPT2/gpt2-fintuning-LoRa-QRaLo

### Prompt Engineering

Prompt engineering involves crafting inputs that effectively steer language models towards desired outputs. I explored various prompt types, such as instruction, completion, scenario, and demonstration prompts.

## Grammar-Constrained Decoding (GCD)

### Overview

Grammar-Constrained Decoding ensures that generated text adheres to a predefined grammar, which is useful for structured NLP tasks like entity extraction or generating code. This approach helps LLMs produce text with a specific structure without the need for additional fine-tuning.

### Example Project
I implemented GCD to extract structured information, specifically subject-relation-object triplets from unstructured text, ensuring the output adhered to grammar rules.

**Project**: https://github.com/monirmo97/Grammar_Constrained_Decoding

## Knowledge Graphs and SPARQL

### Overview

I learned about knowledge graphs through online resources, including video tutorials, to understand how to model and interact with them effectively.

Knowledge graphs allow for the representation of information in a graph format, enabling machines to understand the relationships between different entities. To interact with this data, I learned SPARQL, a query language used for retrieving and manipulating RDF data.

### Learning and Application

- **SPARQL Queries**: I wrote SPARQL queries to navigate RDF data, extract relationships, and create property paths for more complex navigations.
- **Examples**: https://github.com/monirmo97/LLM/tree/main/Knowledge_Graphs_SPARQL

## Regular Meetings and Resources

Throughout my journey, I had regular meetings with my mentor, Jay, to discuss progress, new concepts, and resources. These meetings provided guidance on the latest references, including videos, articles, GitHub notebooks, and research papers.

### Key References and Resources

- https://www.youtube.com/watch?v=CiU1sMbL3k4&list=PLNXdQl4kBgzubTOfY5cbtxZCgg9UTe-uF
- https://www.youtube.com/@AndrejKarpathy
- https://github.com/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb
- https://github.com/openai/openai-cookbook
- https://github.com/epfl-dlab/transformers-CFG

