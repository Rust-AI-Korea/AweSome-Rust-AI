# Awesome Rust AI

A curated hub systematically collecting key libraries, frameworks, tutorials, and community resources across the global Rust artificial intelligence (AI), machine learning (ML), and agent ecosystem.

> An open-source guide for developers leveraging Rust's core strengths—bare-metal performance, memory safety, concurrency, and zero-cost abstractions—to build production-ready AI infrastructure, inference engines, and intelligent autonomous agents.

---

## 📑 Table of Contents
- [📦 Deep Learning Frameworks](#-deep-learning-frameworks)
- [⚡ LLM Inference & Serving](#-llm-inference--serving)
- [🤖 Agents & LLM Orchestration](#-agents--llm-orchestration)
- [🎮 Reinforcement Learning (RL)](#-reinforcement-learning-rl)
- [📊 Classical Machine Learning & Statistics](#-classical-machine-learning--statistics)
- [🔍 Vector Databases & Embeddings](#-vector-databases--embeddings)
- [🔤 NLP, Speech & Computer Vision](#-nlp-speech--computer-vision)
- [🔢 Math, Tensors & Data Engineering](#-math-tensors--data-engineering)
- [📚 Tutorials, Documentation & Community Resources](#-tutorials-documentation--community-resources)
- [📖 Contributor Guide](#-contributor-guide)

---

## 📦 Deep Learning Frameworks
- [Burn](https://github.com/tracel-ai/burn) - Next-generation, production-grade deep learning framework balancing flexibility and raw speed. Features multi-backend hardware acceleration (WGPU, CUDA, ROCm, LibTorch, CubeCL) with end-to-end training, automatic differentiation, and deployment workflows.
- [Candle](https://github.com/huggingface/candle) - Minimalist, pure-Rust deep learning framework created by Hugging Face. Designed specifically for performance-critical model inference, serverless runtimes, and WebAssembly (WASM).
- [dfdx](https://github.com/coreylowman/dfdx) - Ergonomic, pure-Rust deep learning library featuring compile-time shape and type checking for maximum safety across neural networks.
- [tch-rs](https://github.com/LaurentMazare/tch-rs) - Comprehensive, battle-tested Rust bindings for PyTorch's underlying C++ engine (LibTorch).
- [RustGPT](https://github.com/tekaratzas/RustGPT) - A complete transformer-based LLM implemented from scratch in pure Rust using only `ndarray`, featuring custom tokenization, pre-training, instruction tuning, and full backpropagation without external ML frameworks.

## ⚡ LLM Inference & Serving
- [Mistral.rs](https://github.com/EricLBuehler/mistral.rs) - Fast, feature-complete LLM inference platform supporting multi-architecture models, multimodal vision-language models, and state-of-the-art quantization formats (GGUF, GGML, AWQ, GPTQ).
- [Text Generation Inference (TGI)](https://github.com/huggingface/text-generation-inference) - Hugging Face's industrial-grade production serving engine for LLMs, featuring continuous batching, FlashAttention, and token streaming powered by a Rust web server.
- [tract](https://github.com/sonos/tract) - Sonos's high-performance neural network inference engine supporting ONNX and TensorFlow models for embedded Linux, mobile, and WASM targets.
- [llama-cpp-rs](https://github.com/utilityai/llama-cpp-rs) - High-level, safe Rust bindings for `llama.cpp`, enabling optimized CPU/GPU quantized inference for open-weight models.
- [llm](https://github.com/rustformers/llm) - Rust-native ecosystem toolkit designed to inspect and run popular quantized open-source models with minimal system dependencies.
- [Tabby](https://github.com/TabbyML/tabby) - Self-hosted open-source AI coding assistant written in Rust, engineered as an on-premise alternative to GitHub Copilot.

## 🤖 Agents & LLM Orchestration
- [Goose](https://github.com/block/goose) - Open-source, extensible AI agent engine and desktop/CLI app written in Rust that goes beyond code suggestions to execute shell commands, edit files, and automate workflows via Model Context Protocol (MCP).
- [Rig](https://github.com/0xPlaygrounds/rig) - Opinionated, modular framework for building production-ready AI applications, autonomous agents, and RAG pipelines in Rust (supporting OpenAI, Anthropic, Gemini, Cohere, Groq, and Ollama).
- [Kalosm](https://github.com/floneum/kalosm) - Multimodal AI orchestration framework seamlessly unifying local on-device models (powered by Candle) with cloud APIs, speech recognition, and vision modules for complex agentic workflows.
- [genai](https://github.com/jeremychone/rust-genai) - Universal multi-provider client crate providing unified, idiomatic Rust types and streaming abstractions across OpenAI, Anthropic, Gemini, Groq, Cohere, DeepSeek, and Ollama.
- [langchain-rust](https://github.com/Abraxas-365/langchain-rust) - Rust implementation of LangChain abstractions for chaining prompts, memory buffers, tools, and multi-step agent decisions.
- [llm-chain](https://github.com/sobelio/llm-chain) - Modular orchestration framework for structuring multi-stage LLM chains, automated reasoning, and tool execution loops.

## 🎮 Reinforcement Learning (RL)
- [border](https://github.com/taku-y/border) - Comprehensive reinforcement learning library written in Rust, supporting vectorized environments, gym-like observation interfaces, and Deep Q-Networks (DQN) with PyTorch (tch-rs) integration.
- [rurel](https://github.com/milanboers/rurel) - Generic, zero-dependency reinforcement learning library offering flexible implementations of state-action spaces and Q-Learning algorithms.
- [gym-rs](https://github.com/MathisWellmann/gym-rs) - High-performance Rust implementation of standard OpenAI Gym environments (CartPole, MountainCar, Pendulum) for benchmarking agent control policies.

## 📊 Classical Machine Learning & Statistics
- [linfa](https://github.com/rust-ml/linfa) - Comprehensive classical machine learning toolkit modeled after Python's Scikit-learn, providing modular algorithms for clustering, regression, classification, SVMs, and PCA.
- [smartcore](https://github.com/smartcorelib/smartcore) - Pure-Rust machine learning engine featuring robust implementations of Decision Trees, Random Forests, Naive Bayes, K-Means, and matrix factorizations.
- [augurs](https://github.com/grafana/augurs) - High-throughput time-series analysis and forecasting library built by Grafana in Rust, supporting AutoARIMA and seasonal decomposition.

## 🔍 Vector Databases & Embeddings
- [Qdrant](https://github.com/qdrant/qdrant) - High-throughput, distributed vector search engine and database written entirely in Rust, featuring rich payload filtering and fast ANN indexing.
- [LanceDB](https://github.com/lancedb/lancedb) - Lightweight, serverless embedded vector database powered by the Lance columnar format, purpose-built for multi-modal AI data and low-latency disk-based retrieval.
- [Text Embeddings Inference (TEI)](https://github.com/huggingface/text-embeddings-inference) - Blazing-fast inference toolkit by Hugging Face for serving vector embeddings, re-rankers, and cross-encoders.
- [fastembed-rs](https://github.com/Anush008/fastembed-rs) - Low-overhead Rust crate for fast text and image embedding generation using ONNX Runtime without heavy external dependencies.
- [hora](https://github.com/hora-search/hora) - Lightweight approximate nearest neighbor (ANN) search library supporting multiple indexing algorithms (HNSW, BPTree, SSG).

## 🔤 NLP, Speech & Computer Vision
- [tokenizers](https://github.com/huggingface/tokenizers) - Industry-standard, ultra-fast tokenization library engineered by Hugging Face (supporting BPE, WordPiece, Unigram, and Byte-level encodings).
- [whisper-rs](https://github.com/tazz4843/whisper-rs) - Idiomatic Rust bindings for Georgi Gerganov's `whisper.cpp`, enabling high-performance on-device speech-to-text (STT) inference.
- [image](https://github.com/image-rs/image) & [imageproc](https://github.com/image-rs/imageproc) - Foundational Rust crates for 2D image reading, processing, color conversions, and computer vision feature extraction.
- [rust-bert](https://github.com/guillaume-be/rust-bert) - Ready-to-use NLP pipelines (summarization, translation, QA, sentiment analysis) based on Hugging Face Transformers implemented in Rust.

## 🔢 Math, Tensors & Data Engineering
- [Polars](https://github.com/pola-rs/polars) - High-performance DataFrame engine written in Rust on top of Apache Arrow, delivering multithreaded vectorization and query optimization.
- [Apache DataFusion](https://github.com/apache/datafusion) - Extensible, in-memory SQL query engine and computing pipeline written in Rust for big data analytics.
- [CubeCL](https://github.com/tracel-ai/cubecl) - Multi-target compute framework for writing high-performance, JIT-compiled GPU kernels (CUDA, ROCm, WGPU) entirely in Rust syntax.
- [ndarray](https://github.com/rust-ndarray/ndarray) - Fundamental N-dimensional array container and mathematical computation crate for scientific computing (NumPy equivalent).
- [nalgebra](https://github.com/dimforge/nalgebra) - Comprehensive linear algebra library providing general and fixed-size matrices, vector spaces, and geometric transformations.

## 📚 Tutorials, Documentation & Community Resources
- [Are We Learning Yet?](https://www.arewelearningyet.com/) - Central tracking portal evaluating the maturity, readiness, and active crates across the entire Rust machine learning landscape.
- [The Burn Book](https://burn.dev/) - Comprehensive official guide to Burn, covering project architecture, custom training loops, model building, and ONNX exports.
- [Hugging Face Candle Documentation](https://huggingface.github.io/candle/) - Official guides, tutorials, and practical implementation examples for running LLaMA, Whisper, Stable Diffusion, and Mistral in pure Rust.
- [Rig Official Guide & Documentation](https://rig.rs/docs/) - Architectural overviews, integration recipes, and production patterns for LLM agents, embeddings, and RAG pipelines.
- [Awesome Machine Learning with Rust](https://github.com/vaaaaanquish/Awesome-Rust-MachineLearning) - Community-maintained directory cataloging machine learning libraries and benchmarks in Rust.
- [Rust-AI-Korea Organization](https://github.com/Rust-AI-Korea) - Community and open-source collaboration hub fostering Rust-based AI/ML system development, translation, and technical sharing.

## 📖 Contributor Guide
The Rust AI ecosystem is expanding rapidly with new breakthroughs every month.
- Discovered an essential library, tool, or runtime?
- Authored a technical case study, tutorial, or reproducible benchmark?
- Identified outdated links or descriptions needing precision?

Contributions via Pull Requests (PRs) and **GitHub Issues** are always welcome!

### How to Contribute
1. Fork this repository.
2. Add your entry under the relevant category adhering to the standardized format:
   ```markdown
   - [Project Name](Link) - Concise summary highlighting key features, backends, and primary use cases.
