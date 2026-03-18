---
author: Bronwen Aker
presentation_type: Workshop
date: 2026-03-21
updated: 2026-03-21
---

> [!info]- Table of Contents
> ```table-of-contents
> title: 
> style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
> minLevel: 0 # Include headings from the specified level
> maxLevel: 0 # Include headings up to the specified level
> include: 
> exclude: 
> includeLinks: true # Make headings clickable
> hideWhenEmpty: false # Hide TOC if no headings are found
> debugInConsole: false # Print debug info in Obsidian console
> ````


# A

## Adversarial Prompting

Using prompts to attack, test, or bypass AI system protections.

## AGI (Artificial General Intelligence)

Hypothetical AI with human-level intelligence across all domains that doesn't exist yet.

## AI (Artificial Intelligence)

Computer systems that can perform tasks typically requiring human intelligence, like understanding language or recognizing patterns.

## Alignment

Ensuring AI behavior matches human values and intentions.

## Anthropic

AI safety company that created Claude.

## API (Application Programming Interface)

Way for programs to interact with AI models programmatically instead of through a chat interface.

## Attention Mechanism

Core component of transformers that helps models focus on relevant parts of the input.

# B

## Batch Processing

Sending multiple prompts at once for efficiency instead of one at a time.

## BERT (Bidirectional Encoder Representations from Transformers)

Google's model architecture designed for understanding language rather than generating it.

# C

## Chain-of-Thought (CoT)

Prompting technique where you ask the model to "think step by step" to improve reasoning.

## ChatGPT

OpenAI's conversational AI based on GPT models.

## Checkpoint

Saved snapshot of a model during training.

## Claude

Anthropic's LLM family, focused on safety and helpfulness.

## Closed Source Model

Proprietary model accessible only through APIs or specific interfaces.

## Confabulation

Model making up plausible-sounding information, similar to hallucination.

## Context Overflow

Attempting to exceed the context window to cause errors or expose system behavior.

## Context Window

Maximum amount of text a model can "remember" and work with at one time.

# D

## DAN (Do Anything Now)

Popular jailbreak technique trying to create an unrestricted alter ego for the AI.

## Data Poisoning

Contaminating training data to manipulate how the model behaves.

## Delimiter

Special characters used to separate sections in prompts, such as backticks (```), hashes (###), or XML tags.

## Delimiter Confusion

Using delimiters to trick the model into treating instructions as data or vice versa.

## Deterministic Output

Setting temperature to 0 to get the same response every time for the same prompt.

## Direct Injection

Attacker directly crafts a malicious prompt through the input interface.

# E

## Embedding

Converting text into numbers (vectors) that capture meaning, allowing the model to understand semantic similarity.

## Evasion Attack

Crafting inputs specifically to bypass content filters or security measures.

# F

## Few-Shot

Including 2-5 examples in your prompt to demonstrate the pattern you want.

## Fine-tuning

Additional training on specific types of data to make the model better at particular tasks.

# G

## Gemini

Google's multimodal AI model, formerly known as Bard.

## GPT (Generative Pre-trained Transformer)

OpenAI's series of LLMs including GPT-3.5, GPT-4, and others.

## Guardrails

Safety measures and restrictions built into AI systems to prevent harmful outputs.

# H

## Hallucination

When the model confidently states false information as fact.

# I

## In-Context Learning

Model adapting its behavior based solely on examples and instructions in the prompt, without any retraining.

## Indirect Injection

Hiding malicious instructions in external content (websites, documents) that the LLM processes.

## Inference

Using the trained model to actually generate responses from new inputs.

## Instruction Following

Model's ability to understand and execute explicit commands in prompts.

# J

## Jailbreaking

Attempts to bypass the model's safety guardrails and ethical constraints to get prohibited outputs.

# L

## Latency

Time between sending your prompt and getting a response back.

## LLaMA

Meta's open source LLM family.

## LLM (Large Language Model)

AI system trained on massive amounts of text to understand and generate human language.

## LoRA (Low-Rank Adaptation)

Efficient way to fine-tune models by adding small trainable components instead of retraining everything.

# M

## Max Tokens

Maximum length allowed for the model's response.

## Membership Inference

Attack that determines whether specific data was included in the training set.

## Meta-Prompt

Prompt that defines how to create other prompts or guides the prompting workflow.

## Model

The trained AI system itself that processes your input and generates responses.

## Model Extraction

Attempting to recreate or steal a model's functionality through repeated queries.

## Multimodal

AI that can process multiple types of input (text, images, audio) instead of just text.

# N

## NLP (Natural Language Processing)

Field of AI focused on making computers understand and work with human language.

# O

## One-Shot

Providing exactly one example to show the model what you want.

## Open Source Model

AI model with publicly available code and weights that anyone can use, modify, or run locally.

## OpenAI

AI research company that created ChatGPT and DALL-E.

# P

## Parameters

The billions of internal settings that determine how the model behaves; more parameters generally means more capability.

## Payload

Malicious content or instructions hidden within a seemingly innocent prompt.

## Perplexity

(1) Metric measuring prediction quality; lower is better. (2) AI-powered search engine.

## PII (Personally Identifiable Information)

Data that identifies specific individuals, which models should refuse to generate or expose.

## Pre-training

Initial phase where the model learns general language understanding from vast datasets.

## Priming

Setting expectations or context at the start of a prompt to influence how the model responds.

## Prompt

The input or instructions you give to an LLM to get a desired output.

## Prompt Chaining

Breaking complex tasks into steps where each prompt uses the output from the previous one.

## Prompt Engineering

Crafting effective prompts to get better, more reliable results from LLMs.

## Prompt Injection

Inserting malicious instructions into a prompt to override intended behavior, similar to SQL injection but for LLMs.

## Prompt Leaking

Extracting the hidden system prompt or instructions through cleverly designed queries.

## Prompt Template

Reusable prompt structure with placeholders you can fill in for different uses.

# Q

## Quantization

Compressing models to use less memory and compute, making them run on smaller hardware.

# R

## Red Teaming

Systematically attacking AI systems to find vulnerabilities and weaknesses before bad actors do.

## Responsible Disclosure

Ethically reporting security vulnerabilities to developers privately before going public.

## Retrieval-Augmented Generation (RAG)

Combining LLMs with database lookups to provide accurate, current information beyond the training data.

## RLHF (Reinforcement Learning from Human Feedback)

Training method using human ratings to teach models what outputs are good versus bad.

## Role/Persona

Telling the model to act as a specific character or expert to guide its tone and expertise.

## Role-Playing Attack

Using personas or scenarios to convince the model to bypass restrictions.

# S

## Safety Classifier

Automated system that screens inputs and outputs for harmful content before processing.

## Social Engineering

Manipulating the AI through psychological techniques (flattery, urgency, authority) to bypass restrictions.

## Stop Sequence

Text that tells the model to stop generating, useful for controlling output length.

## Structured Output

Requesting responses in specific formats like JSON, XML, or tables for easier parsing.

## System Prompt

Initial instructions that set the model's behavior for an entire conversation, often hidden from regular users.

# T

## Temperature

Setting that controls how random or creative the output is; higher values produce more creative responses, lower values produce more focused ones.

## Token

Basic unit the model uses to process text, roughly 3-4 characters or 0.75 words in English.

## Tokenization

How text gets split into tokens; different models tokenize differently.

## Top-p (Nucleus Sampling)

Sampling method controlling which tokens the model considers when generating text.

## Training

Process of teaching an AI by feeding it huge amounts of text data so it learns patterns and relationships in language.

## Training Data Extraction

Trying to recover specific examples from the model's training data, potentially exposing sensitive information.

## Transformer

The underlying neural network architecture that makes modern LLMs work, using "attention" to understand relationships between words.

## TTP (Tactics, Techniques, and Procedures)

Specific methods and patterns used to achieve objectives, borrowed from cybersecurity to describe prompt engineering approaches.

# U

## Universal Adversarial Prompt

Attack prompt that works across multiple different models.

# W

## Weaponization

Using LLMs to generate malicious content like malware, phishing emails, or exploit code.

# Z

## Zero-Day Prompt

Novel prompt injection technique not yet known to defenders.

## Zero-Shot

Asking the model to do something without giving it any examples, just instructions.




