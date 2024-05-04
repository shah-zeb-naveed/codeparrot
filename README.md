# Large Language Models Repository 🧠

This repository hosts various projects on large language modeling, focusing on diverse tasks with advanced techniques. Below is a concise overview:

## 🚀 Top Models on Hugging Face Hub
- [shahzebnaveed/NeuralHermes-2.5-Mistral-7B](https://huggingface.co/shahzebnaveed/NeuralHermes-2.5-Mistral-7B) 🔥 2k downloads
- [shahzebnaveed/StarlingHermes-2.5-Mistral-7B-slerp](https://huggingface.co/shahzebnaveed/StarlingHermes-2.5-Mistral-7B-slerp) 🔥 2k downloads

## Reinforcement Learning from Human Feedback
- Direct Preference Optimization on Mistral with Orca Dataset using QLoRa
    - [Model Link](https://huggingface.co/shahzebnaveed/StarlingHermes-2.5-Mistral-7B-slerp)
- Proximal Policy Optimization on GPT-2 to control sentiment of movie reviews using BERT as a reward model 

## Retrieval Augmented Generation on Databricks
- Using Databricks's built-in vector store and retrieval to implement a RAG Chatbot
- Indexed data and deployed model to Databricks Models endpoint

## Instruction Tuning
- Instruction fine-tuning LLAMA 2 using Alpaca dataset

## Optimization Techniques
- Quantization (Bitsandbytes)
- PEFT (LoRa, QLoRa)
- llama.cpp for GGUF format
    - [Model Link](https://huggingface.co/shahzebnaveed/EvolCodeLlama-7b-GGUF1)

## Mixture-of-Experts
- Fine-tuning google's switch base transformers for summarization task
- [Model Link](https://huggingface.co/shahzebnaveed/moe_switch_transformer_summarization)

## Merge-kit
- Merge-kit to create different merged models
- [Model Link](https://huggingface.co/shahzebnaveed/StarlingHermes-2.5-Mistral-7B-slerp)

## Prompt Tuning
- Fine-tuning Bloomz model using causal language modelling
    - [Model Link](https://huggingface.co/shahzebnaveed/bloomz-560m_prompt_tuning_clm)
- Fine-tuning T5 for prefix tuning using sequence-to-sequence
    - [Model Link](https://huggingface.co/shahzebnaveed/t5-large_PREFIX_TUNING_SEQ2SEQ)

## Causal Language Modelling
- **Overview:** Fine-tuning a GPT2-based model for Python code completion (Code Parrot)
    - [Model Link](https://huggingface.co/shahzebnaveed/codeparrot-ds)
- **Training:** GPT2 network trained from scratch using PyTorch and HuggingFace Transformers.
- **Azure Deployment:** Custom model with MLFlow PyFunc flavour due to Azure's limited native support.

## Masked Language Modelling
- **Overview:** Fine-tuning DistilBert on IMDB Dataset
    - [Model Link](https://huggingface.co/shahzebnaveed/distilbert-base-uncased-finetuned-imdb)

## Extractive Question Answering
- **Overview:** Fine-tuning BERT-base-cased
    - [Model Link](https://huggingface.co/shahzebnaveed/bert-finetuned-squad?context=My+name+is+Clara+and+I+live+in+Berkeley.&text=What%27s+my+name%3F)

## Translation
- **Overview:** Fine-tuning Helsinki-NLP/opus-mt-en-fr for English to French 
    - [Model Link](https://huggingface.co/shahzebnaveed/marian-finetuned-kde4-en-to-fr)

## Token Classification
- **Overview:** Fine-tuning roBERTa using LoRa (Low Rank Adaptation)
    - [Model Link](https://huggingface.co/shahzebnaveed/roberta-large-lora-token-cls)

## Langchain Chains
- ReAct agents with custom tool
- RAG with chat memory (Chroma and Pinecone)
- LangServe & Fast API to deploy RAG chatbot

## Multi-Agent Chats
- Python verification chat with Autogen where one agent executes the code

**Credits:**
- Adapted code submissions from HuggingFace NLP course.
- Blog posts/tutorials from [llm-course](https://github.com/mlabonne/llm-course).
- Databricks tutorial on RAG
