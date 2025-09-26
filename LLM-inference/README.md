# LLM Inference (Week 1 Project)

## Objective
Run a pre-trained language model (DistilGPT2) using Hugging Face `transformers` and experiment with text generation parameters.

## Setup
- Google Colab (recommended, CPU/GPU friendly)
- Python 3.10+
- Libraries:
  ```bash
  pip install transformers

## Steps Implemented:

Installed and imported transformers.

Created a pipeline for text-generation using distilgpt2.

Generated text from custom prompts.

## Experimented with:

temperature (randomness vs determinism)

top_k (restrict vocabulary choices)

top_p (nucleus sampling)

max_length (output size)

## Results

Low temperature (0.1): Repetitive, safe completions.

High temperature (1.2): More creative, sometimes nonsensical.

Smaller top_k (10): Very limited, repetitive wording.

Larger top_k (100): More variety, richer outputs.

## Learnings

Hugging Face pipelines simplify model loading (tokenizer + model in one).

Sampling parameters directly shape model creativity.

Even small models like distilgpt2 can produce interesting completions.

## Files

llm_inference.ipynb: Colab notebook with code and experiments.

README.md: This file.
