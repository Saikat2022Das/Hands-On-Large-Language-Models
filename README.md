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

## Chapter_6:
#### This notebook provides a comprehensive introduction to prompt engineering techniques using the Phi-3-mini language model. Here's what someone can learn from it:
##### Setting up an LLM Pipeline: How to load a pre-trained language model (microsoft/Phi-3-mini-4k-instruct) and its tokenizer, then set up a text generation pipeline using the transformers library.
##### Basic Prompting and Generation: Fundamental concepts of interacting with an LLM by sending messages and interpreting generated text.
##### Prompt Templating: Understanding how to format prompts effectively for chat-based models using apply_chat_template to ensure proper communication with the LLM.
##### Controlling Generation with Parameters: How to influence the creativity and diversity of the LLM's output using parameters like do_sample and temperature.
##### Advanced Prompt Engineering Strategies: Structured Prompting: Building complex prompts by defining elements like persona, instructions, context, data format, audience, and tone for specific tasks like summarization.
##### In-Context Learning (One-Shot): Guiding the model's behavior by providing a single example within the prompt to teach it a new task or concept.
##### Chain Prompting: Breaking down complex tasks into smaller, sequential prompts, where the output of one prompt serves as input for the next, enabling more structured problem-solving.
##### Reasoning Techniques (Chain-of-Thought, Zero-Shot Chain-of-Thought, Tree-of-Thought): Exploring methods to elicit step-by-step reasoning from LLMs, from providing explicit examples to using meta-prompts like "Let's think step-by-step" or simulating multiple expert perspectives to arrive at a solution. In essence, the notebook teaches practical skills for interacting with and getting better, more controlled, and more complex outputs from large language models through various prompting strategies.
