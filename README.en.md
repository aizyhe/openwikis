<div align="center">

# OpenWikis · Open-Source Authoritative Technical Guides

**An authoritative open-source guide system covering AI Algorithm, AI Infrastructure, Cloud Computing, Embodied Intelligence and more, with a cross-vendor comparison perspective.**

[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-important)](LICENSE)
![AI Algorithm](https://img.shields.io/badge/AI_Algorithm-18ch-EF4444)
![AI Infra](https://img.shields.io/badge/AI_Infra-18ch-7C3AED)
![Cloud Computing](https://img.shields.io/badge/Cloud_Computing-18ch-2563EB)
![Embodied AI](https://img.shields.io/badge/Embodied_AI-18ch-16A34A)

**Language**: [English](README.en.md) · [中文](README.md)

</div>

---

This repository hosts a series of "authoritative guide"-level technical books, currently including the **AI Algorithm Authoritative Guide**, **AI Infrastructure Authoritative Guide**, **Cloud Computing Authoritative Guide**, and **Embodied Intelligence Authoritative Guide**. Written from a cross-vendor comparison perspective, the series covers AI algorithms & foundation models, GPU compute and distributed training, inference optimization, virtualization, cloud-native and Kubernetes, and embodied intelligence & robotics — spanning from algorithms and cloud to the physical world. Each book stands alone and can be read independently or together.

---

## 📚 Book Catalog

| Book | TOC | Content | PDF | Chapters |
| --- | --- | --- | --- | --- |
| **AI Algorithm Authoritative Guide** | [TOC.md](algo/TOC.md) | [Chapter index](algo/AI算法权威指南.md) | [📖 Download](algo/AI算法权威指南.pdf) | 18 ch. + 4 appendices |
| **AI Infrastructure Authoritative Guide** | [TOC.md](infra/TOC.md) | [Chapter index](infra/AI%20Infra权威指南.md) | [📖 Download](infra/AI%20Infra权威指南.pdf) | 18 ch. + 4 appendices |
| **Cloud Computing Authoritative Guide** | [TOC.md](cloud/TOC.md) | [Chapter index](cloud/云计算权威指南.md) | [📖 Download](cloud/云计算权威指南.pdf) | 18 ch. + 4 appendices |
| **Embodied Intelligence Authoritative Guide** | [TOC.md](embodied/TOC.md) | [Chapter index](embodied/具身智能权威指南.md) | [📖 Download](embodied/具身智能权威指南.pdf) | 18 ch. + 4 appendices |

---

## 🧠 AI Algorithm Authoritative Guide

An authoritative guide from the Transformer architecture to foundation models, agent systems, and intelligent systems. Starting from Transformer, it balances theoretical derivation and engineering practice, tracking the latest 2026 open-source architecture cases.

- **Architecture foundations (ch. 1-4)**: Transformer principles & data flow, tokenization & positional encodings (RoPE, ALiBi) for text/image/speech, core components (FFN, normalization), autoregressive generation & decoding strategies
- **Training & scaling (ch. 5-9)**: training & optimization, pretraining & data (synthetic data, scaling laws), post-training alignment (SFT/RLHF/DPO), modern architectures (MoE, hybrid & linear attention), frontier model cases (DeepSeek-V4, Kimi K3, Qwen 3.8 Max, GLM 5.3)
- **Efficient inference & generation (ch. 10-14)**: long context & KV Cache, speculative decoding, reinforcement learning principles, reasoning augmentation & chain-of-thought, generative models (diffusion LMs), multimodality (VLM/VLA)
- **Intelligent systems & engineering (ch. 15-18)**: agent systems & cognitive architectures, world models, safety & evaluation, FlashAttention's GPU-level efficient implementation

---

## ⚡ AI Infrastructure Authoritative Guide

End-to-end AI infrastructure from GPU microarchitecture to 10K-GPU clusters. Referenced against public technical reports and open-source systems from NVIDIA, Google, Meta, and Microsoft, with code-level detail and engineering trade-offs.

- **GPU microarchitecture & basics (ch. 1-4)**: AI Infra overview & Scaling Law, SIMT/SIMD paradigms, NVIDIA GPU architecture (SM, Tensor Core, Warp scheduling, memory hierarchy), AI accelerator ecosystem (AMD ROCm, Google TPU, custom silicon from cloud & internet companies), CUDA & Triton high-performance kernels (FlashAttention, fused kernels)
- **Distributed training & communication (ch. 5-8)**: data parallelism (DDP/FSDP), model parallelism (tensor/pipeline/sequence/expert), 5D parallel composition, DeepSpeed ZeRO, collective communication (NCCL internals, NVLink/NVSwitch, InfiniBand/RoCEv2), 10K-GPU training stability, fault tolerance & distributed checkpointing, mixed-precision training
- **Inference & model optimization (ch. 9-12)**: inference engines (vLLM, PagedAttention, Continuous Batching, KV Cache), model quantization (GPTQ, AWQ, SmoothQuant), sparsity & knowledge distillation, RAG & vector search, AI storage & data engineering
- **Platforms & framework optimization (ch. 13-16)**: AI cluster topologies & scheduling (SLURM, K8s GPU scheduling), cloud-native MLOps, ML compilers (TorchDynamo, JAX/XLA, TensorRT), performance engineering & cost optimization
- **Design & practice (ch. 17-18)**: AI Infra theoretical calculation handbook (FLOPs, memory planning, communication bandwidth, cost estimation), large-scale AI cluster construction

---

## ☁️ Cloud Computing Authoritative Guide

Full-stack cloud computing knowledge from virtualization to multi-cloud strategy. Anchored on real products from AWS, Azure, GCP, Alibaba Cloud, Tencent Cloud, and Huawei Cloud, examining architectural principles and design trade-offs.

- **Foundation (ch. 1-3)**: cloud definitions & economics, virtualization (CPU/memory/I/O, KVM & QEMU), service models (IaaS/PaaS/Serverless/CaaS) & selection framework
- **Resource services (ch. 4-7)**: compute services (instance families, auto-scaling, spot instances, bare metal), cloud storage (block/object/file, consistency design, backup & DR), cloud networking (VPC, load balancing, CDN, DNS), containers (Namespace/Cgroups, runtimes, CNI/CSI, image distribution)
- **Platforms & data (ch. 8-13)**: cloud-native design patterns, Kubernetes orchestration, service mesh & microservices, cloud databases, messaging & event-driven, big data & AI
- **Governance & operations (ch. 14-18)**: cloud security & compliance, observability, DevOps & platform engineering, FinOps cost governance, multi-cloud architecture & migration

---

## 🦾 Embodied Intelligence Authoritative Guide

An authoritative reference from rigid-body dynamics to VLA foundation models and robotics. Built from first principles, bridging classical methods and the frontier, so readers know both the "how" and the "why".

- **Basics & overview (ch. 1-3)**: definitions & core scientific questions, rigid-body motion & dynamics (pose representation, Lie groups SO(3)/SE(3), kinematics & dynamics), robot hardware & system architecture
- **Perception & modeling (ch. 4-6)**: multimodal perception (vision/touch/proprioception), environment perception & state estimation (SLAM), world models & neural scene representation
- **Learning & control (ch. 7-10)**: reinforcement learning, imitation learning, motion planning & low-level control, dexterous manipulation & contact
- **Embodied foundation models (ch. 11-14)**: vision-language models (VLM), vision-language-action models (VLA), embodied data engines, simulation & Sim-to-Real transfer
- **Systems & deployment (ch. 15-17)**: embodied training infrastructure, deployment & edge inference, safety, alignment & evaluation
- **Industry & outlook (ch. 18)**: industry landscape, humanoid robots, commercialization paths & open problems

---

## ✨ Key Features

- **Cross-vendor comparison** — Horizontally compare vendor implementations of the same problem (object storage consistency, managed K8s, Serverless cold starts...), distilling general architectural patterns
- **Principles first** — Deep dives into virtualization, distributed storage consistency, SDN, Kubernetes, service mesh, GPU microarchitecture, and LLM training/inference fundamentals
- **Code-level detail** — Code-level implementation details for principles, and the engineering trade-offs behind architecture decisions
- **Engineering practice** — Production-ready capabilities: performance engineering, FinOps cost governance, fault-tolerant training, observability, and Sim-to-Real transfer
- **Continuous evolution** — Tracking the latest in GPU microarchitecture, 10K-GPU clusters, inference optimization, quantization/compression, and VLA foundation models

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

## 🤝 Contributing

Welcome to submit corrections and improvement suggestions via [Issues](https://github.com/aizyhe/openwikis/issues), or contribute content via Pull Requests. A community contribution guide is on the way.

---

## 📄 License

**All rights reserved.** Learning and citation are welcome; please contact the author for republication or commercial use.

---

## 👤 Author

| | |
| --- | --- |
| Author | hezhiyong |
| Email | [aizyhe@126.com](mailto:aizyhe@126.com) |
| Version | v1.0.1 |
| Date | 2026-06-25 |
