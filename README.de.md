<div align="center">

# OpenWikis · Open-Source-Fachbuchreihe

## Vier maßgebliche Ratgeber: KI-Algorithmen · KI-Infrastruktur · Cloud Computing · Verkörperte Intelligenz

**Ein kostenloses Open-Source-System von Fachbüchern, das Foundation-Modelle (Transformer, MoE, RLHF), KI-Infrastruktur (GPU-Mikroarchitektur, verteiltes Training, Inferenzoptimierung, Modellquantisierung), Cloud Computing (Virtualisierung, Kubernetes, Cloud-nativ, FinOps) und verkörperte Intelligenz (SLAM, Reinforcement Learning, VLA) abdeckt — mit PDFs zum sofortigen Herunterladen.**

[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/aizyhe/openwikis?style=social)](https://github.com/aizyhe/openwikis)
![AI Algorithm](https://img.shields.io/badge/AI_Algorithm-18ch-EF4444)
![AI Infra](https://img.shields.io/badge/AI_Infra-18ch-7C3AED)
![Cloud Computing](https://img.shields.io/badge/Cloud_Computing-18ch-2563EB)
![Embodied AI](https://img.shields.io/badge/Embodied_AI-18ch-16A34A)

**Sprache**: [Deutsch](README.de.md) · [English](README.en.md) · [中文](README.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md)

</div>

---

OpenWikis ist ein kostenloses Open-Source-Repository für Fachbücher und hostet vier systematische Bände — **maßgeblicher Ratgeber für KI-Algorithmen**, **maßgeblicher Ratgeber für KI-Infrastruktur**, **maßgeblicher Ratgeber für Cloud Computing** und **maßgeblicher Ratgeber für verkörperte Intelligenz** (jeweils mit 18 Kapiteln + 4 Anhängen), verfügbar als **vollständige PDF-Downloads** und **Online-Kapitelnavigation**.

Die Reihe ist aus einer anbieterübergreifenden Vergleichsperspektive geschrieben und deckt **LLM-Algorithmen und Inferenz, GPU und verteiltes Training, Cloud-nativ und Kubernetes sowie Robotik und verkörperte Intelligenz** ab — von algorithmischen Prinzipien bis zur Ingenieurpraxis, von einer einzelnen Maschine bis zu 10.000-GPU-Clustern, von der Cloud bis zur physischen Welt. Sie dient KI-Ingenieuren, Cloud-Architekten, Forschern und Studierenden als umfassende technische Wissensbasis. Jedes Buch kann unabhängig oder als Querverweis gelesen werden.

---

## 📚 Buchkatalog

**Schlüsselwörter**: LLM · Transformer · Attention · MoE · RLHF · Verteiltes Training · GPU · CUDA · Inferenzoptimierung · Modellquantisierung · vLLM · Kubernetes · Cloud-nativ · Virtualisierung · FinOps · Verkörperte Intelligenz · Robotik · VLA · Reinforcement Learning

| Buch | TOC | Inhalt | PDF | Kapitel |
| --- | --- | --- | --- | --- |
| **Ratgeber für KI-Algorithmen** | [TOC.md](algo/TOC.md) | [Kapitelübersicht](algo/AI算法权威指南.md) | [📖 Herunterladen](algo/AI算法权威指南.pdf) | 18 Kap. + 4 Anhänge |
| **Ratgeber für KI-Infrastruktur** | [TOC.md](infra/TOC.md) | [Kapitelübersicht](infra/AI%20Infra权威指南.md) | [📖 Herunterladen](infra/AI%20Infra权威指南.pdf) | 18 Kap. + 4 Anhänge |
| **Ratgeber für Cloud Computing** | [TOC.md](cloud/TOC.md) | [Kapitelübersicht](cloud/云计算权威指南.md) | [📖 Herunterladen](cloud/云计算权威指南.pdf) | 18 Kap. + 4 Anhänge |
| **Ratgeber für verkörperte Intelligenz** | [TOC.md](embodied/TOC.md) | [Kapitelübersicht](embodied/具身智能权威指南.md) | [📖 Herunterladen](embodied/具身智能权威指南.pdf) | 18 Kap. + 4 Anhänge |

---

## 🧠 Ratgeber für KI-Algorithmen

Eine vollständige algorithmische Reise von Transformer bis zu Foundation-Modellen und intelligenten Systemen, die theoretische Ableitung mit Ingenieurpraxis verbindet und die neuesten Open-Source-Architekturen von 2026 verfolgt.

- **Architektur-Grundlagen (Kap. 1-4)**: Transformer-Prinzipien und Datenfluss, Tokenisierung und Positionskodierungen (RoPE, ALiBi) für Text/Bild/Sprache, Kernkomponenten (FFN, Normalisierung), autoregressive Generierung und Dekodierungsstrategien
- **Training und Skalierung (Kap. 5-9)**: Training und Optimierung, Vortraining und Daten (synthetische Daten, Skalierungsgesetze), Post-Training-Alignment (SFT/RLHF/DPO), moderne Architekturen (MoE, hybride und lineare Aufmerksamkeit), Fallbeispiele von Spitzenmodellen (DeepSeek-V4, Kimi K3, Qwen 3.8 Max, GLM 5.3)
- **Effiziente Inferenz und Generierung (Kap. 10-14)**: langer Kontext und KV-Cache, spekulative Dekodierung, Prinzipien des Reinforcement Learning, Reasoning-Erweiterung und Gedankenkette, generative Modelle (Diffusions-Sprachmodelle), Multimodalität (VLM/VLA)
- **Intelligente Systeme und Ingenieurwesen (Kap. 15-18)**: Agentensysteme und kognitive Architekturen, Weltmodelle, Sicherheit und Bewertung, GPU-effiziente Implementierung von FlashAttention

> Für LLM-Algorithmus-Ingenieure, NLP/multimodale Forscher und Praktiker, die Transformer-Interna und Inferenzoptimierung beherrschen möchten.

---

## ⚡ Ratgeber für KI-Infrastruktur

Eine End-to-End-Referenz für KI-Infrastruktur von der GPU-Mikroarchitektur bis zu 10.000-GPU-Clustern, basierend auf öffentlichen technischen Berichten und Open-Source-Systemen von NVIDIA, Google, Meta und Microsoft, mit Code-Level-Detail und Engineering-Abwägungen.

- **Hardware und Software (Kap. 1-5)**: KI-Infrastruktur-Überblick und Skalierungsgesetze, GPU-Mikroarchitektur (SIMT/SIMD, SM- und Warp-Scheduling, Speicherhierarchie, Tensor Core), Ökosystem der KI-Beschleuniger (AMD ROCm, Google TPU, kundenspezifisches Silizium), CUDA- und Triton-High-Performance-Kernel (FlashAttention, fusionierte Kernel), ML-Compiler (PyTorch 2.0, JAX/XLA, TensorRT)
- **Training und Inferenz (Kap. 6-11)**: verteiltes Training (DDP/FSDP, Tensor/Pipeline/Sequenz/Experten-Parallelität), NCCL-Kollektivkommunikation und Netzwerke (NVLink/NVSwitch, InfiniBand/RoCEv2), Engineering von Trainingssystemen (Fehlertoleranz, Checkpoints, gemischte Präzision), Inferenzoptimierung (vLLM, PagedAttention, Continuous Batching, KV-Cache), Modellquantisierung (GPTQ, AWQ, SmoothQuant) und Kompression
- **Daten und Plattformen (Kap. 12-15)**: RAG und Vektorsuche, KI-Speicher und Daten-Engineering, Cluster-Topologien und Scheduling (SLURM, GPU-Scheduling in K8s), Cloud-natives MLOps und KI-Plattformen
- **Messung und Praxis (Kap. 16-18)**: Leistungskennzahlen und MFU-Analyse, Handbuch zur theoretischen Berechnung der KI-Infrastruktur (FLOPs, Speicherplanung, Kommunikationsbandbreite, Kostenschätzung), Bau großer KI-Cluster

> Für KI-Infrastruktur-Ingenieure, Entwickler von Trainings-/Inferenzplattformen, Systemarchitekten und Praktiker verteilter Systeme.

---

## ☁️ Ratgeber für Cloud Computing

Umfassendes Cloud-Computing-Wissen von der Virtualisierung bis zur Multi-Cloud-Strategie, verankert an realen Produkten von AWS, Azure, GCP, Alibaba Cloud, Tencent Cloud und Huawei Cloud, mit Analyse architektonischer Prinzipien und Design-Abwägungen.

- **Grundlagen (Kap. 1-3)**: Cloud-Definitionen und -Ökonomie, Virtualisierung (CPU/Speicher/E/A, KVM und QEMU), Servicemodelle (IaaS/PaaS/Serverless/CaaS) und Auswahlrahmen
- **Ressourcendienste (Kap. 4-7)**: Rechendienste (Instanzfamilien, Auto-Scaling, Spot-Instanzen, Bare Metal), Cloud-Speicher (Block/Objekt/Datei, Konsistenzdesign, Backup und DR), Cloud-Netzwerke (VPC, Lastausgleich, CDN, DNS), Container (Namespace/Cgroups, Runtimes, CNI/CSI, Image-Verteilung)
- **Plattformen und Daten (Kap. 8-13)**: Cloud-native Designmuster, Kubernetes-Orchestrierung, Service Mesh und Microservices, Cloud-Datenbanken, Messaging und Event-getrieben, Big Data und KI
- **Governance und Betrieb (Kap. 14-18)**: Cloud-Sicherheit und Compliance, Observability, DevOps und Plattform-Engineering, FinOps-Kosten-Governance, Multi-Cloud-Architektur und Migration

> Für Cloud-Architekten, Backend-Ingenieure, SREs, DevOps-Ingenieure und technische Manager.

---

## 🦾 Ratgeber für verkörperte Intelligenz

Eine systematische, maßgebliche Referenz von der Starrkörperdynamik bis zu VLA-Foundation-Modellen und Robotik. Ausgehend von ersten Prinzipien verbindet sie klassische Methoden mit der Front, und führt jede Methode von der Formalisierung über die mathematische Ableitung bis zur technischen Implementierung.

- **Grundlagen und Überblick (Kap. 1-3)**: Definitionen und zentrale wissenschaftliche Fragen, Starrkörperbewegung und -dynamik (Posendarstellung, Lie-Gruppen, Kinematik und Dynamik, Kontakt und Reibung), Roboter-Hardware und Systemarchitektur
- **Wahrnehmung und Steuerung (Kap. 4-7)**: multimodale Wahrnehmung (Vision/Tastsinn/Kraft/Propriozeption), Zustandsschätzung und SLAM, neuronale Szenendarstellung, Bewegungsplanung und modellprädiktive Regelung, Greifen und geschickte Manipulation
- **Verkörperte Foundation-Modelle (Kap. 8-12)**: Weltmodelle, Reinforcement Learning, Imitationslernen (Diffusionspolitik, Aktions-Chunking), Vision-Language-Modelle (VLM), Vision-Language-Action-Modelle (VLA)
- **Systeme und Bereitstellung (Kap. 13-18)**: Daten-Engines und Sim-to-Real-Transfer, Trainingsinfrastruktur, Edge-Bereitstellung und Modellkompression, Sicherheit, Alignment und Bewertung, Industrielandschaft und Kommerzialisierung humanoider Roboter

> Für Ingenieure und Forscher in Robotik, autonomes Fahren und KI sowie für Produkt- und Investitionsprofis, die verkörperte Intelligenz verfolgen.

---

## ✨ Hauptmerkmale

- **Systematisch** — Vier Bücher, jedes mit 18 Kapiteln + 4 Anhängen, deckt vollständiges Wissen von Prinzipien bis Praxis ab; ideal als Lehrmaterial und Team-Training
- **Anbieter-/Modellübergreifender Vergleich** — Implementierungen desselben Problems horizontal vergleichen (Objekt-Speicher-Konsistenz, verwaltetes K8s, Serverless-Kaltstarts, GPUs und Beschleuniger...), allgemeine Muster destillieren
- **Prinzipien zuerst** — Tiefe Einblicke in Transformer-Aufmerksamkeit, GPU-Mikroarchitektur, Parallelitätsstrategien für verteiltes Training, Virtualisierung und Kubernetes-Scheduling — nicht nur Nutzung
- **Code-Level-Detail** — Code-/Kernel-Level-Implementierungsdetails und die Engineering-Abwägungen hinter Architekturentscheidungen
- **Ingenieurpraxis** — Produktionsreife Fähigkeiten: Performance-Engineering, FinOps-Kosten-Governance, fehlertolerantes Training, Inferenzoptimierung, Observability und Sim-to-Real-Transfer
- **Kontinuierliche Weiterentwicklung** — Verfolgt die neuesten Open-Source-Modelle (DeepSeek-V4, Kimi K3, Qwen, GLM), GPU-Mikroarchitektur, 10.000-GPU-Cluster und VLA-Foundation-Modelle

---

## 🗺️ Leseleitfaden

| Zielgruppe | Empfohlener Pfad |
| --- | --- |
| KI-Algorithmus-Ingenieure / LLM-Praktiker | Ratgeber für KI-Algorithmen: Architektur-Grundlagen → Training und Skalierung → effiziente Inferenz |
| KI-Infrastruktur-Ingenieure / Praktiker verteilter Systeme | Ratgeber für KI-Infrastruktur GPU-Mikroarchitektur (Kap. 2) → verteiltes Training |
| Cloud-Architekten / SRE / Backend-Ingenieure | Ratgeber für Cloud Computing Grundlagen (Kap. 1-3) → Ressourcendienste |
| Ingenieure und Forscher für Robotik / verkörperte Intelligenz | Ratgeber für verkörperte Intelligenz: Wahrnehmung → Lernen und Steuerung → VLA-Foundation-Modelle |
| Technische Manager | Cloud FinOps (Kap. 17), KI-Leistung und -Kosten (Kap. 16), verkörperte KI-Industrie und -Kommerzialisierung (Kap. 18) |

> Jedes Buch enthält ein vollständiges Inhaltsverzeichnis (TOC) und einen Terminologie-Anhang für gezieltes Lesen.

---

## 📥 So lesen Sie

Jedes Buch ist sowohl als **vollständiger PDF-Download** als auch über **Online-Kapitelnavigation** verfügbar:

| Methode | Beschreibung |
| --- | --- |
| **PDF herunterladen** | Klicken Sie im Buchkatalog oben auf den Link "📖 Herunterladen" für ein schön formatiertes PDF mit vollem Text |
| **Online lesen** | Klicken Sie auf "Kapitelübersicht", um die TOC-Seite jedes Buches zu öffnen und gezielt zu jedem Kapitel zu springen |
| **Vollständiges TOC** | Das `TOC.md` jedes Buches bietet einen vollständigen Kapitelindex, um interessante Themen schnell zu finden |

---

## 📖 Zitieren

Beim Zitieren dieser Bücher in Artikeln, Dokumenten oder internen Berichten empfehlen wir:

> hezhiyong. *Ratgeber für KI-Algorithmen / KI-Infrastruktur / Cloud Computing / Verkörperte Intelligenz*[M]. OpenWikis, v1.0.1, 2026. https://github.com/aizyhe/openwikis

---

## 🤝 Mitwirken

Wir freuen uns über Korrekturen und Verbesserungsvorschläge über [Issues](https://github.com/aizyhe/openwikis/issues) sowie über Inhaltsbeiträge per Pull Request. Ein Leitfaden zur Community-Beteiligung folgt in Kürze.

---

## 📄 Lizenz

Lizenziert unter **CC BY-NC 4.0 (Namensnennung-Nicht kommerziell)**. Sie dürfen dieses Werk teilen und abgeleitete Werke erstellen, müssen jedoch den Urheber nennen und dürfen es nicht kommerziell nutzen. Details finden Sie in [LICENSE](LICENSE).

---

## 👤 Autor

| | |
| --- | --- |
| Autor | hezhiyong |
| E-Mail | [aizyhe@126.com](mailto:aizyhe@126.com) |
| Version | v1.0.1 |
| Datum | 2026-06-25 |
