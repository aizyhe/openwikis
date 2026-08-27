<div align="center">

# OpenWikis Open-Source Tech Book Series

## Four Authoritative Guides: AI Algorithm · AI Infra · Cloud Computing · Embodied Intelligence

**A free, open-source system of technical books covering foundation models (Transformer, MoE, RLHF), AI infrastructure (GPU microarchitecture, distributed training, inference optimization, model quantization), cloud computing (virtualization, Kubernetes, cloud-native, FinOps) and embodied intelligence (SLAM, reinforcement learning, VLA) — with ready-to-download PDFs.**

[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/aizyhe/openwikis?style=social)](https://github.com/aizyhe/openwikis)
![AI Algorithm](https://img.shields.io/badge/AI_Algorithm-18ch-EF4444)
![AI Infra](https://img.shields.io/badge/AI_Infra-18ch-7C3AED)
![Cloud Computing](https://img.shields.io/badge/Cloud_Computing-18ch-2563EB)
![Embodied AI](https://img.shields.io/badge/Embodied_AI-18ch-16A34A)

**Language**: [English](README.en.md) · [中文](README.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Deutsch](README.de.md)

</div>

---

OpenWikis is a free, open-source repository of technical books, hosting four systematic volumes — **AI Algorithm Authoritative Guide**, **AI Infrastructure Authoritative Guide**, **Cloud Computing Authoritative Guide**, and **Embodied Intelligence Authoritative Guide** (each with 18 chapters + 4 appendices), available as **full PDF downloads** and **online chapter navigation**.

Written from a cross-vendor comparison perspective, the series covers **LLM algorithms & inference, GPU & distributed training, cloud-native & Kubernetes, and robotics & embodied intelligence** — from algorithmic principles to engineering practice, from a single machine to 10K-GPU clusters, from the cloud to the physical world. It serves AI engineers, cloud architects, researchers, and students as a one-stop technical knowledge base. Each book stands alone and can be read independently or cross-referenced.

---

## 📚 Book Catalog

**Keywords**: LLM · Transformer · Attention · MoE · RLHF · Distributed Training · GPU · CUDA · Inference Optimization · Model Quantization · vLLM · Kubernetes · Cloud-Native · Virtualization · FinOps · Embodied Intelligence · Robotics · VLA · Reinforcement Learning

| Book | TOC | Content | PDF | Chapters |
| --- | --- | --- | --- | --- |
| **AI Algorithm Authoritative Guide** | [TOC.md](algo/TOC.md) | [Chapter index](algo/AI算法权威指南.md) | [📖 Download](algo/AI算法权威指南.pdf) | 18 ch. + 4 appendices |
| **AI Infrastructure Authoritative Guide** | [TOC.md](infra/TOC.md) | [Chapter index](infra/AI%20Infra权威指南.md) | [📖 Download](infra/AI%20Infra权威指南.pdf) | 18 ch. + 4 appendices |
| **Cloud Computing Authoritative Guide** | [TOC.md](cloud/TOC.md) | [Chapter index](cloud/云计算权威指南.md) | [📖 Download](cloud/云计算权威指南.pdf) | 18 ch. + 4 appendices |
| **Embodied Intelligence Authoritative Guide** | [TOC.md](embodied/TOC.md) | [Chapter index](embodied/具身智能权威指南.md) | [📖 Download](embodied/具身智能权威指南.pdf) | 18 ch. + 4 appendices |

---

## 🧠 AI Algorithm Authoritative Guide

A complete algorithmic journey from Transformer to foundation models and intelligent systems, balancing theoretical derivation with engineering practice and tracking the latest 2026 open-source architectures.

- **Architecture foundations (ch. 1-4)**: Transformer principles & data flow, tokenization & positional encodings (RoPE, ALiBi) for text/image/speech, core components (FFN, normalization), autoregressive generation & decoding strategies
- **Training & scaling (ch. 5-9)**: training & optimization, pretraining & data (synthetic data, scaling laws), post-training alignment (SFT/RLHF/DPO), modern architectures (MoE, hybrid & linear attention), frontier model cases (DeepSeek-V4, Kimi K3, Qwen 3.8 Max, GLM 5.3)
- **Efficient inference & generation (ch. 10-14)**: long context & KV Cache, speculative decoding, reinforcement learning principles, reasoning augmentation & chain-of-thought, generative models (diffusion LMs), multimodality (VLM/VLA)
- **Intelligent systems & engineering (ch. 15-18)**: agent systems & cognitive architectures, world models, safety & evaluation, FlashAttention's GPU-level efficient implementation

> For LLM algorithm engineers, NLP/multimodal researchers, and practitioners who want to master Transformer internals and inference optimization.

---

## ⚡ AI Infrastructure Authoritative Guide

An end-to-end reference for AI infrastructure from GPU microarchitecture to 10K-GPU clusters, grounded in public technical reports and open-source systems from NVIDIA, Google, Meta, and Microsoft, with code-level detail and engineering trade-offs.

- **Hardware & software (ch. 1-5)**: AI Infra overview & Scaling Law, GPU microarchitecture (SIMT/SIMD, SM & Warp scheduling, memory hierarchy, Tensor Core), AI accelerator ecosystem (AMD ROCm, Google TPU, custom silicon), CUDA & Triton high-performance kernels (FlashAttention, fused kernels), ML compilers (PyTorch 2.0, JAX/XLA, TensorRT)
- **Training & inference (ch. 6-11)**: distributed training (DDP/FSDP, tensor/pipeline/sequence/expert parallelism), NCCL collective communication & networking (NVLink/NVSwitch, InfiniBand/RoCEv2), training systems engineering (fault tolerance, checkpointing, mixed precision), inference optimization (vLLM, PagedAttention, Continuous Batching, KV Cache), model quantization (GPTQ, AWQ, SmoothQuant) & compression
- **Data & platforms (ch. 12-15)**: RAG & vector search, AI storage & data engineering, cluster topologies & scheduling (SLURM, K8s GPU scheduling), cloud-native MLOps & AI platforms
- **Measurement & practice (ch. 16-18)**: performance metrics & MFU analysis, AI Infra theoretical calculation handbook (FLOPs, memory planning, communication bandwidth, cost estimation), large-scale AI cluster construction

> For AI infrastructure engineers, training/inference platform developers, system architects, and distributed systems practitioners.

---

## ☁️ Cloud Computing Authoritative Guide

Full-stack cloud computing knowledge from virtualization to multi-cloud strategy, anchored on real products from AWS, Azure, GCP, Alibaba Cloud, Tencent Cloud, and Huawei Cloud, examining architectural principles and design trade-offs.

- **Foundation (ch. 1-3)**: cloud definitions & economics, virtualization (CPU/memory/I/O, KVM & QEMU), service models (IaaS/PaaS/Serverless/CaaS) & selection framework
- **Resource services (ch. 4-7)**: compute services (instance families, auto-scaling, spot instances, bare metal), cloud storage (block/object/file, consistency design, backup & DR), cloud networking (VPC, load balancing, CDN, DNS), containers (Namespace/Cgroups, runtimes, CNI/CSI, image distribution)
- **Platforms & data (ch. 8-13)**: cloud-native design patterns, Kubernetes orchestration, service mesh & microservices, cloud databases, messaging & event-driven, big data & AI
- **Governance & operations (ch. 14-18)**: cloud security & compliance, observability, DevOps & platform engineering, FinOps cost governance, multi-cloud architecture & migration

> For cloud architects, backend engineers, SREs, DevOps engineers, and technical managers.

---

## 🦾 Embodied Intelligence Authoritative Guide

A systematic authoritative reference from rigid-body dynamics to VLA foundation models and robotics. Built from first principles, it bridges classical methods and the frontier, walking through each method from formalization and mathematical derivation to engineering implementation.

- **Basics & overview (ch. 1-3)**: definitions & core scientific questions, rigid-body motion & dynamics (pose representation, Lie groups, kinematics & dynamics, contact & friction), robot hardware & system architecture
- **Perception & control (ch. 4-7)**: multimodal perception (vision/touch/force/proprioception), state estimation & SLAM, neural scene representation, motion planning & model predictive control, grasping & dexterous manipulation
- **Embodied foundation models (ch. 8-12)**: world models, reinforcement learning, imitation learning (diffusion policy, action chunking), vision-language models (VLM), vision-language-action models (VLA)
- **Systems & deployment (ch. 13-18)**: data engines & Sim-to-Real transfer, training infrastructure, edge deployment & model compression, safety, alignment & evaluation, industry landscape & humanoid robot commercialization

> For engineers & researchers in robotics, autonomous driving, and AI, as well as product & investment professionals tracking embodied intelligence.

---

## ✨ Key Features

- **Systematic** — Four books, each with 18 chapters + 4 appendices, covering complete knowledge from principles to practice; ideal as teaching references and team training material
- **Cross-vendor / cross-model comparison** — Horizontally compare implementations of the same problem (object storage consistency, managed K8s, Serverless cold starts, GPUs & accelerators...), distilling general patterns
- **Principles first** — Deep dives into Transformer attention, GPU microarchitecture, distributed-training parallelism strategies, virtualization, and Kubernetes scheduling — not just usage
- **Code-level detail** — Code/Kernel-level implementation details, and the engineering trade-offs behind architecture decisions
- **Engineering practice** — Production-ready capabilities: performance engineering, FinOps cost governance, fault-tolerant training, inference optimization, observability, and Sim-to-Real transfer
- **Continuous evolution** — Tracking the latest open-source models (DeepSeek-V4, Kimi K3, Qwen, GLM), GPU microarchitecture, 10K-GPU clusters, and VLA foundation models

---

## 🗺️ Reading Guide

| Audience | Recommended Path |
| --- | --- |
| AI algorithm engineers / LLM practitioners | AI Algorithm Guide: architecture foundations → training & scaling → efficient inference |
| AI Infra engineers / distributed systems practitioners | AI Infra Guide GPU microarchitecture (ch. 2) → distributed training |
| Cloud architects / SRE / backend engineers | Cloud Computing Guide foundation (ch. 1-3) → resource services |
| Robotics / embodied intelligence engineers & researchers | Embodied Intelligence Guide: perception → learning & control → VLA foundation models |
| Technical managers | Cloud FinOps (ch. 17), AI Infra Performance & Cost (ch. 16), Embodied AI industry & commercialization (ch. 18) |

> Each book ships with a full TOC and terminology appendix for on-demand reading.

---

## 📥 How to Read

Every book is available both as a **full PDF download** and **online chapter navigation**:

| Method | Description |
| --- | --- |
| **Download PDF** | Click the "📖 Download" link in the book catalog above for a beautifully typeset full-text PDF |
| **Read online** | Click "Chapter index" to open each book's TOC page and jump to any chapter on demand |
| **Full TOC** | Each book's `TOC.md` provides a complete chapter index to quickly locate topics of interest |

---

## 📖 Citation

When citing these books in articles, papers, or internal docs, we suggest:

> hezhiyong. *AI Algorithm / AI Infrastructure / Cloud Computing / Embodied Intelligence Authoritative Guide*[M]. OpenWikis, v1.0.1, 2026. https://github.com/aizyhe/openwikis

---

## 🤝 Contributing

Welcome to submit corrections and improvement suggestions via [Issues](https://github.com/aizyhe/openwikis/issues), or contribute content via Pull Requests. A community contribution guide is on the way.

---

## 📄 License

Licensed under **CC BY-NC 4.0 (Attribution-NonCommercial)**. You may share this content and create derivative works, but must give credit and may not use it commercially. See [LICENSE](LICENSE) for details.

---

## 👤 Author

| | |
| --- | --- |
| Author | hezhiyong |
| Email | [aizyhe@126.com](mailto:aizyhe@126.com) |
| Version | v1.0.1 |
| Date | 2026-06-25 |
