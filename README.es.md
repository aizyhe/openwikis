<div align="center">

# OpenWikis · Colección de Libros Técnicos de Código Abierto

## Cuatro Guías Autorizadas: Algoritmos de IA · Infraestructura de IA · Computación en la Nube · Inteligencia Encarnada

**Un sistema gratuito y de código abierto de libros técnicos que cubre modelos fundacionales (Transformer, MoE, RLHF), infraestructura de IA (microarquitectura de GPU, entrenamiento distribuido, optimización de inferencia, cuantización de modelos), computación en la nube (virtualización, Kubernetes, nativo de nube, FinOps) e inteligencia encarnada (SLAM, aprendizaje por refuerzo, VLA), con PDF listos para descargar.**

[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/aizyhe/openwikis?style=social)](https://github.com/aizyhe/openwikis)
![AI Algorithm](https://img.shields.io/badge/AI_Algorithm-18ch-EF4444)
![AI Infra](https://img.shields.io/badge/AI_Infra-18ch-7C3AED)
![Cloud Computing](https://img.shields.io/badge/Cloud_Computing-18ch-2563EB)
![Embodied AI](https://img.shields.io/badge/Embodied_AI-18ch-16A34A)

**Idioma**: [Español](README.es.md) · [English](README.en.md) · [中文](README.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md)

</div>

---

OpenWikis es un repositorio gratuito y de código abierto de libros técnicos que aloja cuatro volúmenes sistemáticos — **Guía Autorizada de Algoritmos de IA**, **Guía Autorizada de Infraestructura de IA**, **Guía Autorizada de Computación en la Nube** y **Guía Autorizada de Inteligencia Encarnada** (cada uno con 18 capítulos + 4 apéndices), disponibles como **descargas PDF completas** y **navegación de capítulos en línea**.

Escrita desde una perspectiva de comparación entre proveedores, la serie cubre **algoritmos e inferencia de LLM, GPU y entrenamiento distribuido, nativo de nube y Kubernetes, y robótica e inteligencia encarnada** — desde los principios algorítmicos hasta la práctica de ingeniería, desde una sola máquina hasta clústeres de 10.000 GPU, desde la nube hasta el mundo físico. Sirve como base de conocimiento técnico integral para ingenieros de IA, arquitectos de nube, investigadores y estudiantes. Cada libro puede leerse de forma independiente o como referencia cruzada.

---

## 📚 Catálogo de Libros

**Palabras clave**: LLM · Transformer · Attention · MoE · RLHF · Entrenamiento Distribuido · GPU · CUDA · Optimización de Inferencia · Cuantización de Modelos · vLLM · Kubernetes · Nativo de Nube · Virtualización · FinOps · Inteligencia Encarnada · Robótica · VLA · Aprendizaje por Refuerzo

| Libro | TOC | Contenido | PDF | Capítulos |
| --- | --- | --- | --- | --- |
| **Guía Autorizada de Algoritmos de IA** | [TOC.md](algo/TOC.md) | [Índice de capítulos](algo/AI算法权威指南.md) | [📖 Descargar](algo/AI算法权威指南.pdf) | 18 cap. + 4 apéndices |
| **Guía Autorizada de Infraestructura de IA** | [TOC.md](infra/TOC.md) | [Índice de capítulos](infra/AI%20Infra权威指南.md) | [📖 Descargar](infra/AI%20Infra权威指南.pdf) | 18 cap. + 4 apéndices |
| **Guía Autorizada de Computación en la Nube** | [TOC.md](cloud/TOC.md) | [Índice de capítulos](cloud/云计算权威指南.md) | [📖 Descargar](cloud/云计算权威指南.pdf) | 18 cap. + 4 apéndices |
| **Guía Autorizada de Inteligencia Encarnada** | [TOC.md](embodied/TOC.md) | [Índice de capítulos](embodied/具身智能权威指南.md) | [📖 Descargar](embodied/具身智能权威指南.pdf) | 18 cap. + 4 apéndices |

---

## 🧠 Guía Autorizada de Algoritmos de IA

Un recorrido algorítmico completo desde Transformer hasta modelos fundacionales y sistemas inteligentes, equilibrando la derivación teórica con la práctica de ingeniería y siguiendo las arquitecturas de código abierto más recientes de 2026.

- **Fundamentos de arquitectura (cap. 1-4)**: principios de Transformer y flujo de datos, tokenización y codificaciones posicionales (RoPE, ALiBi) para texto/imagen/voz, componentes centrales (FFN, normalización), generación autorregresiva y estrategias de decodificación
- **Entrenamiento y escalado (cap. 5-9)**: entrenamiento y optimización, preentrenamiento y datos (datos sintéticos, leyes de escalado), alineación post-entrenamiento (SFT/RLHF/DPO), arquitecturas modernas (MoE, atención híbrida y lineal), casos de modelos de frontera (DeepSeek-V4, Kimi K3, Qwen 3.8 Max, GLM 5.3)
- **Inferencia y generación eficientes (cap. 10-14)**: contexto largo y KV Cache, decodificación especulativa, principios de aprendizaje por refuerzo, aumento de razonamiento y cadena de pensamiento, modelos generativos (LMs de difusión), multimodalidad (VLM/VLA)
- **Sistemas inteligentes e ingeniería (cap. 15-18)**: sistemas de agentes y arquitecturas cognitivas, modelos del mundo, seguridad y evaluación, implementación eficiente a nivel de GPU de FlashAttention

> Para ingenieros de algoritmos de LLM, investigadores de NLP/multimodal y profesionales que desean dominar los internos de Transformer y la optimización de inferencia.

---

## ⚡ Guía Autorizada de Infraestructura de IA

Una referencia de extremo a extremo para la infraestructura de IA desde la microarquitectura de GPU hasta clústeres de 10.000 GPU, fundamentada en informes técnicos públicos y sistemas de código abierto de NVIDIA, Google, Meta y Microsoft, con detalle a nivel de código y compensaciones de ingeniería.

- **Hardware y software (cap. 1-5)**: visión general de la infraestructura de IA y leyes de escalado, microarquitectura de GPU (SIMT/SIMD, programación de SM y Warp, jerarquía de memoria, Tensor Core), ecosistema de aceleradores de IA (AMD ROCm, Google TPU, silicio personalizado), kernels de alto rendimiento CUDA y Triton (FlashAttention, kernels fusionados), compiladores ML (PyTorch 2.0, JAX/XLA, TensorRT)
- **Entrenamiento e inferencia (cap. 6-11)**: entrenamiento distribuido (DDP/FSDP, paralelismo de tensor/pipeline/secuencia/experto), comunicación colectiva NCCL y redes (NVLink/NVSwitch, InfiniBand/RoCEv2), ingeniería de sistemas de entrenamiento (tolerancia a fallos, puntos de control, precisión mixta), optimización de inferencia (vLLM, PagedAttention, Continuous Batching, KV Cache), cuantización de modelos (GPTQ, AWQ, SmoothQuant) y compresión
- **Datos y plataformas (cap. 12-15)**: RAG y búsqueda vectorial, almacenamiento de IA e ingeniería de datos, topologías de clúster y programación (SLURM, programación de GPU en K8s), MLOps nativo de nube y plataformas de IA
- **Medición y práctica (cap. 16-18)**: métricas de rendimiento y análisis de MFU, manual de cálculo teórico de infraestructura de IA (FLOPs, planificación de memoria, ancho de banda de comunicación, estimación de costos), construcción de clústeres de IA a gran escala

> Para ingenieros de infraestructura de IA, desarrolladores de plataformas de entrenamiento/inferencia, arquitectos de sistemas y profesionales de sistemas distribuidos.

---

## ☁️ Guía Autorizada de Computación en la Nube

Conocimiento integral de computación en la nube desde la virtualización hasta la estrategia multinube, anclado en productos reales de AWS, Azure, GCP, Alibaba Cloud, Tencent Cloud y Huawei Cloud, examinando principios arquitectónicos y compensaciones de diseño.

- **Fundamentos (cap. 1-3)**: definiciones y economía de la nube, virtualización (CPU/memoria/E/S, KVM y QEMU), modelos de servicio (IaaS/PaaS/Serverless/CaaS) y marco de selección
- **Servicios de recursos (cap. 4-7)**: servicios de cómputo (familias de instancias, autoescalado, instancias puntuales, bare metal), almacenamiento en la nube (bloque/objeto/archivo, diseño de consistencia, respaldo y DR), redes en la nube (VPC, balanceo de carga, CDN, DNS), contenedores (Namespace/Cgroups, runtimes, CNI/CSI, distribución de imágenes)
- **Plataformas y datos (cap. 8-13)**: patrones de diseño nativo de nube, orquestación de Kubernetes, malla de servicios y microservicios, bases de datos en la nube, mensajería y eventos, big data e IA
- **Gobernanza y operaciones (cap. 14-18)**: seguridad y cumplimiento en la nube, observabilidad, DevOps e ingeniería de plataformas, gobernanza de costos FinOps, arquitectura multinube y migración

> Para arquitectos de nube, ingenieros de backend, SREs, ingenieros DevOps y gerentes técnicos.

---

## 🦾 Guía Autorizada de Inteligencia Encarnada

Una referencia autorizada y sistemática desde la dinámica de cuerpos rígidos hasta los modelos fundacionales VLA y la robótica. Construida desde primeros principios, conecta los métodos clásicos con la frontera, recorriendo cada método desde la formalización y la derivación matemática hasta la implementación en ingeniería.

- **Fundamentos y visión general (cap. 1-3)**: definiciones y preguntas científicas centrales, movimiento y dinámica de cuerpos rígidos (representación de pose, grupos de Lie, cinemática y dinámica, contacto y fricción), arquitectura de hardware y sistemas robóticos
- **Percepción y control (cap. 4-7)**: percepción multimodal (visión/tacto/fuerza/propiocepción), estimación de estado y SLAM, representación de escenas neuronales, planificación de movimiento y control predictivo de modelos, agarre y manipulación diestra
- **Modelos fundacionales encarnados (cap. 8-12)**: modelos del mundo, aprendizaje por refuerzo, aprendizaje por imitación (política de difusión, fragmentación de acciones), modelos de visión-lenguaje (VLM), modelos de visión-lenguaje-acción (VLA)
- **Sistemas y despliegue (cap. 13-18)**: motores de datos y transferencia Sim-to-Real, infraestructura de entrenamiento, despliegue en el borde y compresión de modelos, seguridad, alineación y evaluación, panorama industrial y comercialización de robots humanoides

> Para ingenieros e investigadores en robótica, conducción autónoma e IA, así como profesionales de producto e inversión que siguen la inteligencia encarnada.

---

## ✨ Características Clave

- **Sistemático** — Cuatro libros, cada uno con 18 capítulos + 4 apéndices, cubriendo conocimiento completo desde los principios hasta la práctica; ideal como referencia docente y material de formación de equipos
- **Comparación entre proveedores/modelos** — Comparar horizontalmente implementaciones del mismo problema (consistencia de almacenamiento de objetos, K8s administrado, arranques en frío de Serverless, GPUs y aceleradores...), destilando patrones generales
- **Primero los principios** — Profundiza en la atención de Transformer, la microarquitectura de GPU, las estrategias de paralelismo de entrenamiento distribuido, la virtualización y la programación de Kubernetes — no solo el uso
- **Detalle a nivel de código** — Detalles de implementación a nivel de código/Kernel y las compensaciones de ingeniería detrás de las decisiones de arquitectura
- **Práctica de ingeniería** — Capacidades listas para producción: ingeniería de rendimiento, gobernanza de costos FinOps, entrenamiento tolerante a fallos, optimización de inferencia, observabilidad y transferencia Sim-to-Real
- **Evolución continua** — Siguiendo los modelos de código abierto más recientes (DeepSeek-V4, Kimi K3, Qwen, GLM), la microarquitectura de GPU, los clústeres de 10.000 GPU y los modelos fundacionales VLA

---

## 🗺️ Guía de Lectura

| Público | Ruta Recomendada |
| --- | --- |
| Ingenieros de algoritmos de IA / profesionales de LLM | Guía de Algoritmos de IA: fundamentos de arquitectura → entrenamiento y escalado → inferencia eficiente |
| Ingenieros de infraestructura de IA / profesionales de sistemas distribuidos | Guía de Infraestructura de IA microarquitectura de GPU (cap. 2) → entrenamiento distribuido |
| Arquitectos de nube / SRE / ingenieros de backend | Guía de Computación en la Nube fundamentos (cap. 1-3) → servicios de recursos |
| Ingenieros e investigadores de robótica / inteligencia encarnada | Guía de Inteligencia Encarnada: percepción → aprendizaje y control → modelos fundacionales VLA |
| Gerentes técnicos | FinOps en la nube (cap. 17), rendimiento y costo de IA (cap. 16), industria y comercialización de IA encarnada (cap. 18) |

> Cada libro incluye un TOC completo y un apéndice de terminología para lectura bajo demanda.

---

## 📥 Cómo Leer

Cada libro está disponible como **descarga PDF completa** y **navegación de capítulos en línea**:

| Método | Descripción |
| --- | --- |
| **Descargar PDF** | Haga clic en el enlace "📖 Descargar" en el catálogo de libros anterior para obtener un PDF de texto completo con formato profesional |
| **Leer en línea** | Haga clic en "Índice de capítulos" para abrir la página TOC de cada libro y saltar a cualquier capítulo bajo demanda |
| **TOC completo** | El `TOC.md` de cada libro proporciona un índice completo de capítulos para localizar rápidamente temas de interés |

---

## 📖 Citación

Al citar estos libros en artículos, documentos o informes internos, sugerimos:

> hezhiyong. *Guía Autorizada de Algoritmos de IA / Infraestructura de IA / Computación en la Nube / Inteligencia Encarnada*[M]. OpenWikis, v1.0.1, 2026. https://github.com/aizyhe/openwikis

---

## 🤝 Contribución

Bienvenido a enviar correcciones y sugerencias de mejora a través de [Issues](https://github.com/aizyhe/openwikis/issues), o contribuir contenido mediante Pull Requests. Una guía de contribución comunitaria está en camino.

---

## 📄 Licencia

Licenciado bajo **CC BY-NC 4.0 (Atribución-NoComercial)**. Puede compartir este contenido y crear obras derivadas, pero debe dar crédito y no puede usarlo con fines comerciales. Ver [LICENSE](LICENSE) para más detalles.

---

## 👤 Autor

| | |
| --- | --- |
| Autor | hezhiyong |
| Correo | [aizyhe@126.com](mailto:aizyhe@126.com) |
| Versión | v1.0.1 |
| Fecha | 2026-06-25 |
