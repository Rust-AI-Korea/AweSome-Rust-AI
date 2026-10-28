# Awesome Rust AI

국내외 러스트(Rust) 기반 인공지능(AI) 및 머신러닝(ML) 생태계의 핵심 라이브러리, 튜토리얼, 아티클을 체계적으로 집대성한 큐레이션 허브입니다.

> 고성능, 메모리 안정성, 무비용 추상화(Zero-cost Abstractions)라는 Rust의 강점을 살려 차세대 AI 인프라 및 추론 엔진을 구축하는 개발자들을 위한 오픈 리소스 가이드입니다.

---

## 📑 목차 (Table of Contents)
- [📦 딥러닝 프레임워크 (Deep Learning Frameworks)](#-딥러닝-프레임워크-deep-learning-frameworks)
- [⚡ LLM 추론 및 서빙 엔진 (LLM Inference & Serving)](#-llm-추론-및-서빙-엔진-llm-inference--serving)
- [🤖 에이전트 및 LLM 오케스트레이션 (Agents & Orchestration)](#-에이전트-및-llm-오케스트레이션-agents--orchestration)
- [📊 전통 머신러닝 및 데이터 과학 (Classical ML & Statistics)](#-전통-머신러닝-및-데이터-과학-classical-ml--statistics)
- [🔍 벡터 데이터베이스 및 임베딩 (Vector DB & Embeddings)](#-벡터-데이터베이스-및-임베딩-vector-db--embeddings)
- [🔤 자연어 처리, 음성 및 비전 (NLP, Speech & Computer Vision)](#-자연어-처리-음성-및-비전-nlp-speech--computer-vision)
- [🔢 수치 해석, 텐서 및 데이터 엔지니어링 (Math, Tensors & Data)](#-수치-해석-텐서-및-데이터-엔지니어링-math-tensors--data)
- [📚 학습 자료, 튜토리얼 및 한국어 아티클 (Tutorials & Articles)](#-학습-자료-튜토리얼-및-한국어-아티클-tutorials--articles)
- [📖 기여 가이드 (Contributor Guide)](#-기여-가이드-contributor-guide)

---

## 📦 딥러닝 프레임워크 (Deep Learning Frameworks)
- [Candle](https://github.com/huggingface/candle) - Hugging Face에서 개발한 미니멀리스트 딥러닝 프레임워크. 서버리스 환경, WebAssembly(WASM) 및 가벼운 모델 배포에 최적화.
- [Burn](https://github.com/tracel-ai/burn) - 유연성과 속도를 모두 갖춘 차세대 딥러닝 프레임워크. WGPU, CUDA, LibTorch, CubeCL 등 다양한 백엔드를 지원하며 모델 훈련부터 배포까지 완벽 지원.
- [dfdx](https://github.com/coreylowman/dfdx) - 컴파일 타임에 텐서 형상(Shape) 검사를 수행하여 타입 안정성을 극대화한 순수 Rust 심층 신경망 라이브러리.
- [tch-rs](https://github.com/LaurentMazare/tch-rs) - C++ PyTorch(LibTorch) API에 대한 포괄적이고 성숙한 Rust 바인딩.

## ⚡ LLM 추론 및 서빙 엔진 (LLM Inference & Serving)
- [Mistral.rs](https://github.com/EricLBuehler/mistral.rs) - GGUF, GGML, AWQ, GPTQ 양자화 및 멀티모달 모델을 고속으로 실행할 수 있는 실전 프로덕션용 LLM 추론 엔진.
- [tract](https://github.com/sonos/tract) - Sonos에서 개발한 고성능 신경망 추론 엔진. ONNX, TensorFlow 모델의 엣지/임베디드 디바이스 및 WASM 구동에 특화.
- [llama-cpp-rs](https://github.com/utilityai/llama-cpp-rs) - C++ 기반 로컬 LLM의 사실상 표준인 llama.cpp의 고성능 Rust 바인딩.
- [llm](https://github.com/rustformers/llm) - 다양한 오픈소스 대규모 언어 모델을 로컬 환경에서 손쉽게 실행할 수 있는 Rust 생태계 추론 툴킷.
- [Tabby](https://github.com/TabbyML/tabby) - Rust로 구축된 오픈소스 셀프 호스팅 AI 코딩 어시스턴트(GitHub Copilot 대체재).

## 🤖 에이전트 및 LLM 오케스트레이션 (Agents & Orchestration)
- [Rig](https://github.com/0xPlaygrounds/rig) - Rust 환경의 LangChain/LlamaIndex를 지향하는 강력한 AI 애플리케이션 및 에이전트 프레임워크 (OpenAI, Anthropic, Gemini, Ollama 등 지원, RAG 파이프라인 탑재).
- [Kalosm](https://github.com/floneum/kalosm) - 로컬 모델(Candle 기반)과 클라우드 LLM, 오디오(음성), 비전을 통합하여 복잡한 워크플로를 수행하는 멀티모달 AI 에이전트 프레임워크.
- [genai](https://github.com/jeremychone/rust-genai) - OpenAI, Anthropic, Gemini, Groq, Ollama 등 다양한 생성형 AI API를 일관된 Rust 타입 및 함수로 다루는 멀티 프로바이더 클라이언트.
- [llm-chain](https://github.com/sobelio/llm-chain) - 대규모 언어 모델을 연결하여 단계별 작업 체인을 구성할 수 있는 초기 Rust LLM 오케스트레이션 프레임워크.

## 📊 전통 머신러닝 및 데이터 과학 (Classical ML & Statistics)
- [linfa](https://github.com/rust-ml/linfa) - Python의 Scikit-learn에 대응하는 포괄적인 머신러닝 툴킷 (회귀, 분류, 클러스터링, 차원 축소 알고리즘 지원).
- [smartcore](https://github.com/smartcorelib/smartcore) - 고성능 분류, 회귀, SVM, 의사결정나무, 랜덤 포레스트를 제공하는 순수 Rust 머신러닝 라이브러리.
- [rurel](https://github.com/milanboers/rurel) - 유연하고 재사용 가능한 강화학습(Reinforcement Learning, Q-Learning) 구현체.

## 🔍 벡터 데이터베이스 및 임베딩 (Vector DB & Embeddings)
- [Qdrant](https://github.com/qdrant/qdrant) - Rust로 개발된 초고속 오픈소스 프로덕션급 벡터 검색 엔진 및 벡터 데이터베이스.
- [LanceDB](https://github.com/lancedb/lancedb) - 최신 Lance 컬럼형 데이터 포맷에 기반한 초경량 서버리스/임베디드 벡터 데이터베이스.
- [fastembed-rs](https://github.com/Anush008/fastembed-rs) - 복잡한 의존성 없이 초고속으로 텍스트 및 이미지 임베딩 벡터를 추출하는 경량 Rust 라이브러리.

## 🔤 자연어 처리, 음성 및 비전 (NLP, Speech & Computer Vision)
- [tokenizers](https://github.com/huggingface/tokenizers) - Hugging Face에서 제작한 산업 표준 수준의 초고속 텍스트 토크나이저 (BPE, WordPiece, Unigram).
- [whisper-rs](https://github.com/tazz4843/whisper-rs) - OpenAI Whisper C++ 포팅(whisper.cpp)에 대한 고성능 Rust 바인딩으로 로컬 음성 인식(STT) 구현.
- [image](https://github.com/image-rs/image) & [imageproc](https://github.com/image-rs/imageproc) - 컴퓨터 비전 전처리 및 2D 이미지 조작을 위한 Rust 핵심 생태계 크레이트.

## 🔢 수치 해석, 텐서 및 데이터 엔지니어링 (Math, Tensors & Data)
- [Polars](https://github.com/pola-rs/polars) - Apache Arrow 기반으로 병렬 처리를 극대화한 초고속 데이터프레임 라이브러리 (Pandas 대비 수십 배 빠른 성능).
- [Apache DataFusion](https://github.com/apache/datafusion) - 대규모 데이터 분석 및 ETL을 위한 Rust 네이티브 분산/인메모리 SQL 쿼리 엔진.
- [ndarray](https://github.com/rust-ndarray/ndarray) - N차원 배열 및 복잡한 선형대수 연산을 지원하는 Rust의 표준 과학 계산 라이브러리 (NumPy 스타일).
- [CubeCL](https://github.com/tracel-ai/cubecl) - Rust 문법으로 고성능 GPU 커널(WGPU, CUDA, ROCm)을 작성하고 JIT 컴파일하는 하드웨어 가속 플랫폼 (Burn 프레임워크의 핵심 가속기).

## 📚 학습 자료, 튜토리얼 및 한국어 아티클 (Tutorials & Articles)
- [Are We Learning Yet?](https://www.arewelearningyet.com/) - Rust 머신러닝 생태계의 전반적인 성숙도와 카테고리별 라이브러리 현황을 트래킹하는 대표 웹사이트.
- [The Burn Book](https://www.google.com/search?q=https://burn.dev/book/) - Tracel AI 공식 Burn 프레임워크 학습서 (설치부터 사용자 정의 모델 학습 및 ONNX 변환까지).
- [Hugging Face Candle Guide \& Examples](https://www.google.com/search?q=https://huggingface.co/docs/candle/main/en/index) - Candle 공식 문서 및 LLaMA, Whisper, Stable Diffusion 실행 공식 예제.
- [Rig 공식 가이드 및 문서](https://rig.rs/docs/) - Rig를 활용한 Rust 기반 AI 에이전트 및 RAG 구축 안내서.
- [Rust-AI-Korea Organization](https://www.google.com/search?q=https://github.com/Rust-AI-Korea) - 국내 러스트 인공지능/머신러닝 개발자들을 위한 오픈소스 모임 및 지식 공유 허브.
- *국내 개발자분들이 작성하신 유용한 블로그 글, 번역서, 실습 가이드 링크를 상시 모집하고 있습니다! PR로 추가해 주세요.*

## 📖 기여 가이드 (Contributor Guide)
Rust AI 생태계는 하루가 다르게 빠르게 성장하고 있습니다.
- 새로운 유용한 라이브러리나 툴을 발견하셨나요?
- 직접 작성하신 튜토리얼이나 기술 블로그 글이 있으신가요?
- 기존 설명에 보완이 필요한 부분이 보이시나요?

언제든 Pull Request(PR)나 **Issue**를 통해 자유롭게 기여해 주세요!

### 기여 방법
1. 저장소를 Fork합니다.
2. 적절한 카테고리에 형식에 맞춰 항목을 추가합니다:
   ```markdown
   - [프로젝트명](링크) - 프로젝트에 대한 핵심 설명 및 특징
   ```
3. 변경 사항을 커밋하고 브랜치를 생성한 뒤 PR을 보내주세요!
