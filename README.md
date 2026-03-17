# Hi, I'm Xiaorui (Frida) Liu

**Graduate Student** building at the intersection of **AI/ML**, **high-performance computing**, and **full-stack engineering**.

I design systems that span the entire stack — from hand-written CUDA kernels on A100 GPUs to cloud-deployed web services, from training LLMs from scratch to building natural language interfaces for DeFi protocols.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat&logo=solidity&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-000000?style=flat&logoColor=white)

**HPC / Systems**

![NVSHMEM](https://img.shields.io/badge/NVSHMEM-76B900?style=flat&logo=nvidia&logoColor=white)
![MPI](https://img.shields.io/badge/MPI-0078D4?style=flat&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Modal](https://img.shields.io/badge/Modal-000000?style=flat&logoColor=white)

**Web / Cloud**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=flat&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

**Blockchain**

![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat&logo=ethereum&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-1C1C1C?style=flat&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=flat&logo=hardhat&logoColor=black)

---

## Featured Projects

### [Cryptocurrency Smart Contract](https://github.com/Xiaorui333/Cryptocurrency_Smart-Contract) `Python` `Solidity` `Rust` `CUDA`

A full-stack blockchain & AI portfolio spanning 12 projects — from cryptographic primitives (SHA-256, ECDSA) through Bitcoin node infrastructure and a 12 GB blockchain SQL database, to Ethereum smart contracts (Uniswap V2 implemented in Foundry) and a capstone DeFi application with a natural language interface powered by self-hosted LLaMA via vLLM.

| Highlights | |
|---|---|
| Bitcoin Core full node | Docker + Modal cloud deployment |
| Text-to-SQL blockchain explorer | GPT-3.5 → dynamic schema → live query execution |
| vLLM + LLaMA 3.1-8B | Self-hosted OpenAI-compatible inference on H100s |
| Uniswap V2 from scratch | Foundry implementation with full test coverage |
| NL-to-DeFi interface | Plain English → swap/liquidity smart contract calls |

---

### [HPC for AI](https://github.com/Xiaorui333/neu-hpc-for-ai) `CUDA` `C` `Python` `MPI`

Building the GPU kernels that power modern LLMs — from scratch, one layer at a time. Progresses from CPU threading through tiled GEMM, FlashAttention, FlashAttention-2 (with full backward pass and warp partitioning), distributed multi-GPU attention via MPI, DeepSeekV3-style Mixture-of-Experts, to FlashMoE with NVSHMEM RDMA kernel fusion. All tested on NVIDIA A100s.

| Highlights | |
|---|---|
| FlashAttention 1 & 2 | Custom CUDA kernels with online softmax, warp-level optimization |
| Distributed FA-2 | Multi-GPU with CUDA-aware MPI (HPC-X, 1–8 A100s) |
| DeepSeekV3 MoE | Full route-dispatch-compute pipeline + pybind11 PyTorch extensions |
| FlashMoE RDMA | Fused compute + communication via NVSHMEM (ICML 2025 approach) |

---

### [LLM — From Fundamentals to Alignment](https://github.com/Xiaorui333/LLM) `Python` `PyTorch`

A four-project series building from manual backpropagation through a GPT transformer built from scratch (TinyShakespeare), to LLM alignment techniques: self-alignment via instruction backtranslation (LLaMA-7B + LoRA) and Direct Preference Optimization (DPO) with both LLM-as-Judge and PairRM pipelines. Models published to Hugging Face Hub.

| Highlights | |
|---|---|
| GPT from scratch | Token/positional embeddings, multi-head attention, transformer blocks, top-k/nucleus sampling |
| Self-Alignment | LLaMA-7B backtranslation + 5-point LLM curation → fine-tuned model on HF Hub |
| DPO Training | Preference datasets via GPT-4o-mini judge & PairRM ranking → Llama-3.2-1B alignment |

---

### [Applied Machine Learning](https://github.com/Xiaorui333/Applied-Machine-learning) `Python` `TensorFlow` `Keras`

Nine end-to-end ML projects spanning computer vision, audio recognition, time-series forecasting, and medical imaging. Covers transfer learning (VGG16, EfficientNetB0, MobileNetV2), hyperparameter optimization (Hyperband, Bayesian, Random Search), and production-grade evaluation.

| Highlights | |
|---|---|
| COVID-19 CT diagnosis | 97.17% accuracy on 425K images (EfficientNetB0 + Bayesian HPO) |
| Diabetic retinopathy | 95.5% accuracy, 0.99 AUC (fine-tuned EfficientNetB0) |
| ECG classification | 99.6% accuracy (CNN + BiLSTM hybrid) |
| Time-series forecasting | LSTM with 37% MAE improvement over baseline (Jena Climate) |

---

### [Self-Improving AI](https://github.com/Xiaorui333/Self-Improving-AI) `Python` `PyTorch`

Research-focused projects on reinforcement learning and AI self-improvement: Markov Decision Process (MDP) applied to supply chain inventory optimization, Monte Carlo Policy Gradient (REINFORCE) implementation, and reproduction of the RPM-MCTS paper for reasoning with planning via Monte Carlo Tree Search.

| Highlights | |
|---|---|
| MDP for supply chain | Value iteration & policy optimization for inventory management |
| REINFORCE algorithm | Monte Carlo policy gradient from scratch |
| RPM-MCTS reproduction | LLM reasoning via Monte Carlo Tree Search |

---

### [Application Engineering](https://github.com/Xiaorui333/Application_Engineering) `Java` `Spring Boot` `PostgreSQL`

Six progressive assignments evolving from desktop Swing GUIs to cloud-deployed REST services: personal profile manager, CRUD address book, OpenAI-powered chat app, YouTube Data API service (Spring Boot + Docker + Fly.io), database-cached search with jOOQ + PostgreSQL, and a persistent AI chat application with full conversation history.

| Highlights | |
|---|---|
| Spring Boot REST API | YouTube search service deployed on Fly.io via Docker |
| Database caching | PostgreSQL + jOOQ type-safe SQL, cache-first retrieval |
| Persistent AI chat | OpenAI GPT-3.5 + PostgreSQL message history + Swing UI |
| Full progression | Swing → Spring Boot → Docker → Cloud → Database → AI integration |

---

## Let's Connect

[![GitHub](https://img.shields.io/badge/GitHub-Xiaorui333-181717?style=flat&logo=github)](https://github.com/Xiaorui333)
