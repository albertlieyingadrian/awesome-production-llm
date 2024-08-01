# Awesome-Production-LLM
This repository contains a curated list of awesome open-source libraries for production large language models.

### Newly updated
- [2024.08.01] A new category [🍳LLM Cookbook / Examples](#llm-cookbook--examples) has been added.
 
### Quick links
||||
|---|---|---|
| [📚LLM Data Preprocessing](#llm-data-preprocessing) | [🤖LLM Training / Finetuning](#llm-training--finetuning) | [📊LLM Evaluation / Benchmark](#llm-evaluation--benchmark) |
| [🚀LLM Serving / Inference](#llm-serving--inference) | [🛠️LLM Application / RAG](#llm-application--rag) | [🧐LLM Testing / Monitoring](#llm-testing--monitoring) |
| [🛡️LLM Guardrails / Security](#llm-guardrails--security) | [🍳LLM Cookbook / Examples](#llm-cookbook--examples)  |  |


## LLM Data Preprocessing
- [data-juicer](https://github.com/modelscope/data-juicer) (`ModelScope`) ![](https://img.shields.io/github/stars/modelscope/data-juicer.svg?style=social) A one-stop data processing system to make data higher-quality, juicier, and more digestible for (multimodal) LLMs!
- [datatrove](https://github.com/huggingface/datatrove) (`HuggingFace`) ![](https://img.shields.io/github/stars/huggingface/datatrove.svg?style=social) Freeing data processing from scripting madness by providing a set of platform-agnostic customizable pipeline processing blocks.
- [dolma](https://github.com/allenai/dolma) (`AllenAI`) ![](https://img.shields.io/github/stars/allenai/dolma.svg?style=social) Data and tools for generating and inspecting OLMo pre-training data.
- [dataverse](https://github.com/UpstageAI/dataverse) (`Upstage`) ![](https://img.shields.io/github/stars/UpstageAI/dataverse.svg?style=social) The Universe of Data. All about data, data science, and data engineering
- [NeMo-Curator](https://github.com/NVIDIA/NeMo-Curator) (`NVIDIA`) ![](https://img.shields.io/github/stars/NVIDIA/NeMo-Curator.svg?style=social) Scalable toolkit for data curation
- [dps](https://github.com/EleutherAI/dps) (`EleutherAI`)![](https://img.shields.io/github/stars/EleutherAI/dps.svg?style=social) Data processing system for polyglot

## LLM Training / Finetuning
- [nanoGPT](https://github.com/karpathy/nanoGPT) (`karpathy`) ![](https://img.shields.io/github/stars/karpathy/nanoGPT.svg?style=social) The simplest, fastest repository for training/finetuning medium-sized GPTs.
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) ![](https://img.shields.io/github/stars/hiyouga/LLaMA-Factory.svg?style=social) A WebUI for Efficient Fine-Tuning of 100+ LLMs (ACL 2024)
- [peft](https://github.com/huggingface/peft) (`HuggingFace`) ![](https://img.shields.io/github/stars/huggingface/peft.svg?style=social) PEFT: State-of-the-art Parameter-Efficient Fine-Tuning.
- [llama-recipes](https://github.com/meta-llama/llama-recipes) (`Meta`) ![](https://img.shields.io/github/stars/meta-llama/llama-recipes.svg?style=social) Scripts for fine-tuning Meta Llama3 with composable FSDP & PEFT methods to cover single/multi-node GPUs.
- [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) (`NVIDIA`) ![](https://img.shields.io/github/stars/NVIDIA/Megatron-LM.svg?style=social) Ongoing research training transformer models at scale
- [litgpt](https://github.com/Lightning-AI/litgpt) (`LightningAI`) ![](https://img.shields.io/github/stars/Lightning-AI/litgpt.svg?style=social) 20+ high-performance LLMs with recipes to pretrain, finetune and deploy at scale.
- [trl](https://github.com/huggingface/trl) (`HuggingFace`) ![](https://img.shields.io/github/stars/huggingface/trl.svg?style=social) Train transformer language models with reinforcement learning.
- [LMFlow](https://github.com/OptimalScale/LMFlow) (`OptimalScale`) ![](https://img.shields.io/github/stars/OptimalScale/LMFlow.svg?style=social) An Extensible Toolkit for Finetuning and Inference of Large Foundation Models. Large Models for All.
- [gpt-neox](https://github.com/EleutherAI/gpt-neox) (`EleutherAI`) ![](https://img.shields.io/github/stars/EleutherAI/gpt-neox.svg?style=social) An implementation of model parallel autoregressive transformers on GPUs, based on the Megatron and DeepSpeed libraries
- [torchtune](https://github.com/pytorch/torchtune) (`PyTorch`) ![](https://img.shields.io/github/stars/pytorch/torchtune.svg?style=social) A Native-PyTorch Library for LLM Fine-tuning
- [xtuner](https://github.com/InternLM/xtuner) (`InternLM`) ![](https://img.shields.io/github/stars/InternLM/xtuner.svg?style=social) An efficient, flexible and full-featured toolkit for fine-tuning LLM (InternLM2, Llama3, Phi3, Qwen, Mistral, ...)
- [nanotron](https://github.com/huggingface/nanotron) (`HuggingFace`) ![](https://img.shields.io/github/stars/huggingface/nanotron.svg?style=social) Minimalistic large language model 3D-parallelism training

## LLM Evaluation / Benchmark
- [evals](https://github.com/openai/evals) (`OpenAI`) ![](https://img.shields.io/github/stars/openai/evals.svg?style=social) Evals is a framework for evaluating LLMs and LLM systems, and an open-source registry of benchmarks.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) (`EleutherAI`) ![](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness.svg?style=social) A framework for few-shot evaluation of language models.
- [opencompass](https://github.com/open-compass/opencompass) (`OpenCompass`) ![](https://img.shields.io/github/stars/open-compass/opencompass.svg?style=social) - OpenCompass is an LLM evaluation platform, supporting a wide range of models (Llama3, Mistral, InternLM2,GPT-4,LLaMa2, Qwen,GLM, Claude, etc) over 100+ datasets.
- [deepeval](https://github.com/confident-ai/deepeval) (`ConfidentAI`) ![](https://img.shields.io/github/stars/confident-ai/deepeval.svg?style=social) The LLM Evaluation Framework
- [lighteval](https://github.com/huggingface/lighteval) (`HuggingFace`) ![](https://img.shields.io/github/stars/huggingface/lighteval.svg?style=social) LightEval is a lightweight LLM evaluation suite that Hugging Face has been using internally with the recently released LLM data processing library datatrove and LLM training library nanotron.
- [evalverse](https://github.com/UpstageAI/evalverse) (`Upstage`) ![](https://img.shields.io/github/stars/UpstageAI/evalverse.svg?style=social) The Universe of Evaluation. All about the evaluation for LLMs.

## LLM Serving / Inference
- [ollama](https://github.com/ollama/ollama) (`Ollama`) ![](https://img.shields.io/github/stars/ollama/ollama.svg?style=social) Get up and running with Llama 3.1, Mistral, Gemma 2, and other large language models.
- [gpt4all](https://github.com/nomic-ai/gpt4all) (`NomicAI`) ![](https://img.shields.io/github/stars/nomic-ai/gpt4all.svg?style=social) GPT4All: Chat with Local LLMs on Any Device
- [llama.cpp](https://github.com/ggerganov/llama.cpp) ![](https://img.shields.io/github/stars/ggerganov/llama.cpp.svg?style=social) LLM inference in C/C++
- [FastChat](https://github.com/lm-sys/FastChat) (`LMSYS`) ![](https://img.shields.io/github/stars/lm-sys/FastChat.svg?style=social) An open platform for training, serving, and evaluating large language models. Release repo for Vicuna and Chatbot Arena.
- [vllm](https://github.com/vllm-project/vllm) ![](https://img.shields.io/github/stars/vllm-project/vllm.svg?style=social) A high-throughput and memory-efficient inference and serving engine for LLMs
- [guidance](https://github.com/guidance-ai/guidance) (`guidance-ai`) ![](https://img.shields.io/github/stars/guidance-ai/guidance.svg?style=social) A guidance language for controlling large language models.
- [LiteLLM](https://github.com/BerriAI/litellm) (`BerriAI`) ![](https://img.shields.io/github/stars/BerriAI/litellm.svg?style=social) Call all LLM APIs using the OpenAI format. Use Bedrock, Azure, OpenAI, Cohere, Anthropic, Ollama, Sagemaker, HuggingFace, Replicate, Groq (100+ LLMs)
- [OpenLLM](https://github.com/bentoml/OpenLLM) (`BentoML`) ![](https://img.shields.io/github/stars/bentoml/OpenLLM.svg?style=social) Run any open-source LLMs, such as Llama 3.1, Gemma, as OpenAI compatible API endpoint in the cloud.
- [text-generation-inference](https://github.com/huggingface/text-generation-inference) (`HuggingFace`) ![](https://img.shields.io/github/stars/huggingface/text-generation-inference.svg?style=social) Large Language Model Text Generation Inference
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) (`NVIDIA`) ![](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM.svg?style=social) TensorRT-LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs) and build TensorRT engines that contain state-of-the-art optimizations to perform inference efficiently on NVIDIA GPUs.
- [LMDeploy](https://github.com/InternLM/lmdeploy) (`InternLM`) ![](https://img.shields.io/github/stars/InternLM/lmdeploy.svg?style=social) LMDeploy is a toolkit for compressing, deploying, and serving LLMs.
- [RouteLLM](https://github.com/lm-sys/RouteLLM)  (`LMSYS`) ![](https://img.shields.io/github/stars/lm-sys/RouteLLM.svg?style=social) A framework for serving and evaluating LLM routers - save LLM costs without compromising quality!

## LLM Application / RAG
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) ![](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT.svg?style=social) AutoGPT is the vision of accessible AI for everyone, to use and to build on. Our mission is to provide the tools, so that you can focus on what matters.
- [langchain](https://github.com/langchain-ai/langchain) (`LangChain`) ![](https://img.shields.io/github/stars/langchain-ai/langchain.svg?style=social) Build context-aware reasoning applications
- [MetaGPT](https://github.com/geekan/MetaGPT) ![](https://img.shields.io/github/stars/geekan/MetaGPT.svg?style=social) The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming
- [dify](https://github.com/langgenius/dify) (`LangGenius`) ![](https://img.shields.io/github/stars/langgenius/dify.svg?style=social) Dify is an open-source LLM app development platform. Dify's intuitive interface combines AI workflow, RAG pipeline, agent capabilities, model management, observability features and more, letting you quickly go from prototype to production.
- [llama_index](https://github.com/run-llama/llama_index) (`LlamaIndex`) ![](https://img.shields.io/github/stars/run-llama/llama_index.svg?style=social) LlamaIndex is a data framework for your LLM applications
- [Flowise](https://github.com/FlowiseAI/Flowise) (`FlowiseAI`) ![](https://img.shields.io/github/stars/FlowiseAI/Flowise.svg?style=social) Drag & drop UI to build your customized LLM flow
- [mem0](https://github.com/mem0ai/mem0) (`Mem0`)  ![](https://img.shields.io/github/stars/mem0ai/mem0.svg?style=social) The memory layer for Personalized AI
- [haystack](https://github.com/deepset-ai/haystack) (`Deepset`) ![](https://img.shields.io/github/stars/deepset-ai/haystack.svg?style=social) LLM orchestration framework to build customizable, production-ready LLM applications. Connect components (models, vector DBs, file converters) to pipelines or agents that can interact with your data. 
- [GraphRAG](https://github.com/microsoft/graphrag) (`Microsoft`) ![](https://img.shields.io/github/stars/microsoft/graphrag.svg?style=social) A modular graph-based Retrieval-Augmented Generation (RAG) system
- [RAGFlow](https://github.com/infiniflow/ragflow) (`InfiniFlow`) ![](https://img.shields.io/github/stars/infiniflow/ragflow.svg?style=social) RAGFlow is an open-source RAG (Retrieval-Augmented Generation) engine based on deep document understanding.
- [llmware](https://github.com/llmware-ai/llmware) (`LLMware.ai`) ![](https://img.shields.io/github/stars/llmware-ai/llmware.svg?style=social) Unified framework for building enterprise RAG pipelines with small, specialized models
- [llama-agentic-system](https://github.com/meta-llama/llama-agentic-system) (`Meta`) ![](https://img.shields.io/github/stars/meta-llama/llama-agentic-system.svg?style=social) Agentic components of the Llama Stack APIs

## LLM Testing / Monitoring
- [promptflow](https://github.com/microsoft/promptflow) (`Microsoft`) ![](https://img.shields.io/github/stars/microsoft/promptflow.svg?style=social) Build high-quality LLM apps - from prototyping, testing to production deployment and monitoring.
- [langfuse](https://github.com/langfuse/langfuse) (`Langfuse`) ![](https://img.shields.io/github/stars/langfuse/langfuse.svg?style=social) Open source LLM engineering platform: Observability, metrics, evals, prompt management, playground, datasets. Integrates with LlamaIndex, Langchain, OpenAI SDK, LiteLLM, and more.
- [evidently](https://github.com/evidentlyai/evidently) (`EvidentlyAI`) ![](https://img.shields.io/github/stars/evidentlyai/evidently.svg?style=social) Evidently is ​​an open-source ML and LLM observability framework. Evaluate, test, and monitor any AI-powered system or data pipeline. From tabular data to Gen AI. 100+ metrics.
- [giskard](https://github.com/Giskard-AI/giskard) (`Giskard`) ![](https://img.shields.io/github/stars/Giskard-AI/giskard.svg?style=social) Open-Source Evaluation & Testing for LLMs and ML models
- [promptfoo](https://github.com/promptfoo/promptfoo) (`promptfoo`) ![](https://img.shields.io/github/stars/promptfoo/promptfoo.svg?style=social) Test your prompts, agents, and RAGs. Redteaming, pentesting, vulnerability scanning for LLMs. Improve your app's quality and catch problems. Compare performance of GPT, Claude, Gemini, Llama, and more. Simple declarative configs with command line and CI/CD integration.
- [phoenix](https://github.com/Arize-ai/phoenix) (`ArizeAI`) ![](https://img.shields.io/github/stars/Arize-ai/phoenix.svg?style=social) AI Observability & Evaluation
- [agenta](https://github.com/Agenta-AI/agenta) (`Agenta.ai`) ![](https://img.shields.io/github/stars/Agenta-AI/agenta.svg?style=social) The all-in-one LLM developer platform: prompt management, evaluation, human feedback, and deployment all in one place.

## LLM Guardrails / Security
- [NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) (`NVIDIA`) ![](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails.svg?style=social) NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversational systems.
- [guardrails](https://github.com/guardrails-ai/guardrails) (`GuardrailsAI`) ![](https://img.shields.io/github/stars/guardrails-ai/guardrails.svg?style=social) Adding guardrails to large language models.
- [PurpleLlama](https://github.com/meta-llama/PurpleLlama) (`Meta`) ![](https://img.shields.io/github/stars/meta-llama/PurpleLlama.svg?style=social) Set of tools to assess and improve LLM security.
- [llm-guard](https://github.com/protectai/llm-guard) (`ProtectAI`) ![](https://img.shields.io/github/stars/protectai/llm-guard.svg?style=social) The Security Toolkit for LLM Interactions

## LLM Cookbook / Examples
- [openai-cookbook](https://github.com/openai/openai-cookbook) (`OpenAI`) ![](https://img.shields.io/github/stars/openai/openai-cookbook.svg?style=social) Examples and guides for using the OpenAI API
- [gemini-cookbook](https://github.com/google-gemini/cookbook) (`Google`) ![](https://img.shields.io/github/stars/google-gemini/cookbook.svg?style=social) Examples and guides for using the Gemini API.
- [anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) (`Anthropic`) ![](https://img.shields.io/github/stars/anthropics/anthropic-cookbook.svg?style=social) A collection of notebooks/recipes showcasing some fun and effective ways of using Claude.
- [amazon-bedrock-workshop](https://github.com/aws-samples/amazon-bedrock-workshop) (`AWS`) ![](https://img.shields.io/github/stars/aws-samples/amazon-bedrock-workshop.svg?style=social) This is a workshop designed for Amazon Bedrock a foundational model service.
- [Phi-3CookBook](https://github.com/microsoft/Phi-3CookBook) (`Microsoft`) ![](https://img.shields.io/github/stars/microsoft/Phi-3CookBook.svg?style=social) This is a Phi-3 book for getting started with Phi-3. Phi-3, a family of open AI models developed by Microsoft.
- [mistral-cookbook](https://github.com/mistralai/cookbook) (`Mistral`) ![](https://img.shields.io/github/stars/mistralai/cookbook.svg?style=social) The Mistral Cookbook features examples contributed by Mistralers and our community, as well as our partners. 
- [amazon-bedrock-samples](https://github.com/aws-samples/amazon-bedrock-samples) (`AWS`) ![](https://img.shields.io/github/stars/aws-samples/amazon-bedrock-samples.svg?style=social) This repository contains examples for customers to get started using the Amazon Bedrock Service. This contains examples for all available foundational models
- [cohere-notebooks](https://github.com/cohere-ai/notebooks) (`Cohere`) ![](https://img.shields.io/github/stars/cohere-ai/notebooks.svg?style=social) Code examples and jupyter notebooks for the Cohere Platform
- [gemma-cookbook](https://github.com/google-gemini/gemma-cookbook) (`Google`) ![](https://img.shields.io/github/stars/google-gemini/gemma-cookbook.svg?style=social) A collection of guides and examples for the Gemma open models from Google.
- [upstage-cookbook](https://github.com/UpstageAI/cookbook) (`Upstage`) ![](https://img.shields.io/github/stars/UpstageAI/cookbook.svg?style=social) Upstage api examples and guides

## Acknowledgements
This project is inspired by [Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning).
