# Hands-On-Large-Language-Models
Understanding how LLMs work from scratch

## Chapter_1:
#### The Google Colab notebook details setting up a text generation pipeline using Hugging Face's `transformers` library. It covers installing dependencies, loading the `microsoft/Phi-3-mini-4k-instruct` model and tokenizer, and configuring a text generation pipeline. Key learnings include practical steps for utilizing pre-trained models, understanding tokenizer-model interaction, and controlling generation parameters for basic text creation.

## Chapter_2:
#### Explains how contextualized word embeddings are generated using language models (e.g., BERT-style embeddings) instead of static word vectors. 
#### Demonstrates how tokens, embeddings, and models work together in PyTorch to represent words, sentences, and documents numerically.
#### Shows the difference between word-level embeddings vs sentence/document embeddings and when to use each.
#### Builds foundational intuition for LLMs from scratch, especially how text is converted into meaningful vector representations for downstream tasks.

## Chapter_3:
#### Explains the internal working of a causal Large Language Model (LLM), including how logits and probabilities are computed for next-token prediction.
#### Demonstrates different decoding strategies such as greedy decoding, temperature scaling, top-k, and top-p (nucleus sampling).
#### Shows how decoding parameters influence output quality, diversity, and determinism.
#### Provides practical intuition on how text generation works inside an LLM, beyond high-level API usage.
