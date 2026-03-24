# Hands-On Large Language Models (Learning Repository)

This repository is designed as a structured, practical learning path for mastering Large Language Models (LLMs). It focuses on understanding concepts, implementing them through code, and building real-world applications.

---

## Overview

This project follows the concepts from the book *Hands-On Large Language Models*, but restructures them into a more practical and implementation-focused roadmap.

The goal is not just to read or follow notebooks, but to:

* Understand core LLM concepts deeply
* Apply those concepts through code
* Experiment with models and workflows
* Build real-world AI systems

---

## Learning Roadmap

### Phase 1: Foundations

This phase introduces the fundamental building blocks of language models.

* Introduction to Language Models
* Tokens and Embeddings
* Transformer Architecture

Objective: Build a strong conceptual understanding of how LLMs process and generate text.

---

### Phase 2: Core Applications

This phase focuses on applying LLMs to standard NLP tasks.

* Text Classification
* Text Clustering and Topic Modeling
* Prompt Engineering

Objective: Learn how to solve practical NLP problems using LLMs.

---

### Phase 3: Advanced Techniques

This phase explores more advanced capabilities of modern LLM systems.

* Advanced Text Generation Techniques
* Semantic Search
* Retrieval-Augmented Generation (RAG)

Objective: Build intelligent systems that combine LLMs with external knowledge sources.

---

### Phase 4: Multimodal and Embeddings

This phase expands beyond text-only models.

* Multimodal Language Models
* Embedding Models

Objective: Work with models that process multiple data types and improve semantic understanding.

---

### Phase 5: Fine-Tuning and Custom Models

This phase focuses on adapting models to specific use cases.

* Fine-tuning for Classification
* Fine-tuning for Text Generation

Objective: Customize LLMs for production-level applications.

---

## Repository Structure

```
.
├── chapter01/
├── chapter02/
├── chapter03/
...
├── chapter12/
├── bonus/
└── README.md
```

Each chapter contains:

* Jupyter notebooks
* Code implementations
* Practical experiments

---

## Setup and Installation

Recommended environment:

* Python 3.10 or higher
* PyTorch
* Transformers library

Install dependencies:

```bash
pip install -r requirements.txt
```

You can run the notebooks using:

* Google Colab (recommended for GPU support)
* Local environment (if properly configured)

---

## What You Will Learn

By completing this repository, you will be able to:

* Understand transformer-based architectures
* Work with tokenization and embeddings
* Build NLP pipelines using LLMs
* Implement retrieval-based systems (RAG)
* Fine-tune models for specific tasks
* Explore multimodal AI systems

---

## [Bonus content!](bonus/)

We attempted to put as much information into the book without it being overwhelming. However, even with a 400-page book there is still much to discover! 

We continue to create more guides that compliment the book and go more in-depth into new and [exciting topics]((bonus/)):

| [A Visual Guide to Mamba](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mamba-and-state)             |  [A Visual Guide to Quantization](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization) | [The Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/) |
:-------------------------:|:-------------------------:|:-------------------------:
![](images/mamba.png)  |  ![](images/quant.png) |  ![](images/diffusion.png)
**[A Visual Guide to Mixture of Experts](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts)**  | **[A Visual Guide to Reasoning LLMs](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-reasoning-llms)**  |  **[The Illustrated DeepSeek-R1](https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1)**
![](images/moe.png)  |  ![](images/reasoning.png) |  ![](images/deepseek.png)


---

## Suggested Learning Approach

To get the most out of this repository:

1. Study each concept carefully before running code
2. Execute all notebooks yourself
3. Modify and experiment with examples
4. Build small projects after each phase
5. Revisit complex topics multiple times

---

## Future Improvements

This repository can be extended with:

* Project-based learning modules
* Real-world datasets
* API integrations (e.g., OpenAI, Hugging Face)
* Deployment examples using FastAPI or Streamlit

---

## Final Note

This repository is intended to serve as a complete learning path for Large Language Models, guiding you from foundational concepts to advanced applications.

Consistent practice and experimentation will significantly improve your understanding and practical skills.
