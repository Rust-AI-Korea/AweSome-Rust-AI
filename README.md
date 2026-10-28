# Awesome Rust AI

A curated hub systematically collecting key libraries, tutorials, and articles across the global Rust artificial intelligence (AI) and machine learning (ML) ecosystem.

> An open-source guide for developers leveraging Rust's core strengths—high performance, memory safety, and zero-cost abstractions—to build next-generation AI infrastructure and inference engines.

---

## 📑 Table of Contents
- [📦 Deep Learning Frameworks](#-deep-learning-frameworks)
- [⚡ LLM Inference & Serving](#-llm-inference--serving)
- [🤖 Agents & Orchestration](#-agents--orchestration)
- [📊 Classical ML & Statistics](#-classical-ml--statistics)
- [🔍 Vector DB & Embeddings](#-vector-db--embeddings)
- [🔤 NLP, Speech & Computer Vision](#-nlp-speech--computer-vision)
- [🔢 Math, Tensors & Data Engineering](#-math-tensors--data-engineering)
- [📚 Tutorials, Articles & Learning Resources](#-tutorials-articles--learning-resources)
- [📖 Contributor Guide](#-contributor-guide)

---

## 📦 Deep Learning Frameworks
- [Candle](https://github.com/huggingface/candle) - Minimalist deep learning framework developed by Hugging Face, optimized for serverless environments, WebAssembly (WASM), and lightweight model deployments.
- [Burn](https://github.com/tracel-ai/burn) - Next-generation deep learning framework offering both flexibility and speed. Supports diverse backends (WGPU, CUDA, LibTorch, CubeCL) with end-to-end training and deployment workflows.
- [dfdx](https://github.com/coreylowman/dfdx) - Pure Rust deep learning library with compile-time shape checking for maximum type safety.
- [tch-rs](https://github.com/LaurentMazare/tch-rs) - Comprehensive, mature Rust bindings for the C++ PyTorch (LibTorch) API.

## ⚡ LLM Inference & Serving
- [Mistral.rs](https://github.com/EricLBuehler/mistral.rs) - Fast, production-ready LLM inference engine supporting GGUF, GGML, AWQ, and GPTQ quantization along with multimodal models.
- [tract](https://github.com/sonos/tract) - High-performance neural network inference engine by Sonos, optimized for ONNX/TensorFlow model execution on edge devices, embedded hardware, and WASM.
- [llama-cpp-rs](https://github.com/utilityai/llama-cpp-rs) - High-performance Rust bindings for `llama.cpp`, the de facto standard for running local LLMs in C++.
- [llm](https://github.com/rustformers/llm) - Rust ecosystem toolkit designed to easily run various open-source large language models locally.
- [Tabby](https://github.com/TabbyML/tabby) - Self-hosted open-source AI coding assistant built with Rust (an open alternative to GitHub Copilot).

## 🤖 Agents & Orchestration
- [Rig](https://github.com/0xPlaygrounds/rig) - Robust framework for building portable, modular AI applications and agents in Rust (akin to LangChain/LlamaIndex; supports OpenAI, Anthropic, Gemini, Ollama, and RAG pipelines).
- [Kalosm](https://github.com/floneum/kalosm) - Multimodal AI agent framework integrating local models (via Candle) with cloud LLMs, speech, and vision to handle complex workflows.
- [genai](https://github.com/jeremychone/rust-genai) - Multi-provider client library providing a unified, idiomatic Rust API across OpenAI, Anthropic, Gemini, Groq, Ollama, and more.
- [llm-chain](https://github.com/sobelio/llm-chain) - Early-stage Rust LLM orchestration framework for building step-by-step task chains with large language models.

## 📊 Classical ML & Statistics
- [linfa](https://github.com/rust-ml/linfa) - Comprehensive classical machine learning toolkit modeled after Python's Scikit-learn (regression, classification, clustering, dimensionality reduction).
- [smartcore](https://github.com/smartcorelib/smartcore) - Pure Rust machine learning library featuring high-performance implementations of classification, regression, SVMs, decision trees, and random forests.
- [rurel](https://github.com/milanboers/rurel) - Flexible, reusable reinforcement learning (Q-learning) implementation.

## 🔍 Vector DB & Embeddings
- [Qdrant](https://github.com/qdrant/qdrant) - High-performance, open-source production-grade vector search engine and vector database written in Rust.
- [LanceDB](https://github.com/lancedb/lancedb) - Lightweight, serverless/embedded vector database built on the modern Lance columnar data format.
- [fastembed-rs](https://github.com/Anush008/fastembed-rs) - Lightweight Rust library for fast text and image embedding generation with minimal dependencies.

## 🔤 NLP, Speech & Computer Vision
- [tokenizers](https://github.com/huggingface/tokenizers) - Industry-standard, ultra-fast tokenization library by Hugging Face (supporting BPE, WordPiece, and Unigram).
- [whisper-rs](https://github.com/tazz4843/whisper-rs) - High-performance Rust bindings for `whisper.cpp`, enabling local speech-to-text (STT) inference.
- [image](https://github.com/image-rs/image) & [imageproc](https://github.com/image-rs/imageproc) - Core crates in the Rust graphics ecosystem for 2D image processing, computer vision preprocessing, and manipulation.

## 🔢 Math, Tensors & Data Engineering
- [Polars](https://github.com/pola-rs/polars) - Lightning-fast DataFrame library built on Apache Arrow, engineered for maximum multithreaded performance (orders of magnitude faster than pandas).
- [Apache DataFusion](https://github.com/apache/datafusion) - Rust-native in-memory SQL query engine for high-scale analytical queries and ETL workflows.
- [ndarray](https://github.com/rust-ndarray/ndarray) - Rust's fundamental scientific computing library offering N-dimensional arrays and linear algebra operations (NumPy equivalent).
- [CubeCL](https://github.com/tracel-ai/cubecl) - Hardware acceleration platform for writing high-performance GPU compute kernels (WGPU, CUDA, ROCm) in pure Rust with JIT compilation (core accelerator behind Burn).

## 📚 Tutorials, Articles & Learning Resources
- [Are We Learning Yet?](https://www.arewelearningyet.com/) - Central tracking hub monitoring the maturity and readiness of the Rust machine learning ecosystem.
- [The Burn Book](https://burn.dev/book/) - Official Tracel AI guide to the Burn framework (covering installation, custom model training, and ONNX export).
- [Hugging Face Candle Guide & Examples](https://huggingface.co/docs/candle/main/en/index) - Official documentation and practical examples for running LLaMA, Whisper, and Stable Diffusion using Candle.
- [Rig Official Documentation & Guides](https://rig.rs/docs/) - Architectural overview and practical guides for building AI agents and RAG pipelines in Rust.
- [Rust-AI-Korea Organization](https://github.com/Rust-AI-Korea) - Community hub for Korean and international Rust AI/ML developers sharing knowledge and open-source tooling.
- *Community-authored blog posts, translations, and hands-on guides are always welcome! Please submit a PR to add your resources.*

## 📖 Contributor Guide
The Rust AI ecosystem is evolving rapidly.
- Discovered an exciting new library or tool?
- Wrote a tutorial or an insightful engineering blog post?
- Spot areas where descriptions or links can be improved?

Contributions via Pull Requests (PRs) and **Issues** are warmly welcomed!

### How to Contribute
1. Fork this repository.
2. Add your entry under the relevant section following this format:
   ```markdown
   - [Project Name](Link) - Concise summary highlighting key features and capabilities
