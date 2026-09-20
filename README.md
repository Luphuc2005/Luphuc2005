<div align="center">

# Lu Hong Phuc

### AI · Computer Vision · Machine Learning

Building research-oriented machine learning systems and turning ideas into working prototypes.

[![GitHub](https://img.shields.io/badge/GitHub-Luphuc2005-181717?style=flat-square&logo=github)](https://github.com/Luphuc2005)
[![Email](https://img.shields.io/badge/Email-phucga150625%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:phucga150625@gmail.com)

</div>

---

## About Me

I'm a Computer Science student focusing on **Artificial Intelligence, Computer Vision, and Machine Learning systems**.

My interests lie at the intersection of research and engineering: designing machine learning architectures, running reproducible experiments, analyzing model behavior, and turning research ideas into practical AI systems.

My current areas of interest include:

- Computer Vision
- Facial Expression Recognition
- Graph Neural Networks
- Vision Transformers
- Vision-Language Modeling
- Multimodal Learning
- Medical AI
- AI Engineering & Model Deployment
- Distributed and Resource-Efficient Training

---

## Featured Projects

### [AMGSA FER Framework](https://github.com/Luphuc2005/AMGSA_FER_Framework)

A research-oriented framework for **Facial Expression Recognition (FER)** designed to support systematic experimentation across model architectures, training strategies, and evaluation pipelines.

The project focuses on studying facial representations and improving expression recognition through reproducible experiments, detailed model evaluation, and architecture-level analysis rather than treating FER as a simple classification task.

`Python` `Computer Vision` `Facial Expression Recognition` `Deep Learning` `Model Evaluation`

---

### [SwinCMN](https://github.com/Luphuc2005/SwinCMN)

A **vision-language framework for automatic chest X-ray report generation**, combining visual representation learning with cross-modal clinical knowledge.

SwinCMN extends the R2GenCMN architecture by integrating a **ResNet-101 visual backbone, Cross-modal Memory Network, Swin Transformer encoder, and Transformer decoder**.

Window-based and shifted-window self-attention are used to capture fine-grained spatial relationships between anatomical regions, while the cross-modal memory mechanism enhances interaction between visual features and clinical language context.

The model was evaluated on the **IU X-Ray dataset** and achieved improvements over the R2Gen-CMN baseline across multiple report-generation metrics, including BLEU and METEOR.

`Python` `PyTorch` `Medical AI` `Vision-Language Modeling` `Swin Transformer` `Cross-modal Learning`

---

### [AI for Agriculture 2026](https://github.com/doduyquy/AI-for-Agriculture-2026)

A multimodal deep-learning system developed for the **ICPR 2026 Beyond Visible Spectrum: AI for Agriculture challenge**, targeting wheat rust disease classification from UAV imagery.

The framework jointly exploits three complementary imaging modalities:

- RGB imagery
- Multispectral imagery
- Hyperspectral imagery

Each modality is processed through an independent **ResNet18 feature extraction branch**.

For hyperspectral data, a **Hard Concrete gating mechanism** is used to learn the importance of spectral bands and retain the most informative wavelengths.

Predictions from RGB, multispectral, and hyperspectral branches are then combined through **weighted late fusion**.

The proposed multimodal configuration achieved:

**Accuracy:** 76.72%  
**F1-score:** 77.14%

demonstrating the benefit of combining visual appearance with spectral information for crop disease recognition.

`Python` `PyTorch` `Multimodal Learning` `Hyperspectral Imaging` `Band Selection` `Late Fusion`

---

### [HeteroViT Train](https://github.com/Luphuc2005/HeteroViT-Train)

An experimental training and benchmarking framework for studying **vision-model performance across heterogeneous computing environments**.

The project investigates how deep-learning workloads behave under different hardware configurations, including CPU and GPU execution, with emphasis on training throughput, resource utilization, scalability, and computational efficiency.

It also explores distributed execution and practical optimization strategies for running machine-learning experiments on heterogeneous and resource-constrained systems.

`Python` `Deep Learning` `Distributed Training` `CPU/GPU Benchmarking` `Performance Engineering`

---

### [TwoTierGovQA](https://github.com/Luphuc2005/TwoTierGovQA)

A research-oriented **question-answering system** built around a two-tier information retrieval and reasoning workflow.

The project explores how separating evidence discovery from downstream answer generation can improve the organization of a QA pipeline, allowing relevant information to be retrieved first and then processed into focused responses.

The system is designed as an experiment in structured retrieval, information access, and multi-stage question answering.

`Python` `NLP` `Information Retrieval` `Question Answering` `Retrieval Pipeline`

---

### [Smart School Bus Tracking System](https://github.com/Irthn1311/Smart_School_Bus_Tracking_System)

A full-stack **real-time school transportation management platform** designed around GPS-based vehicle tracking and multi-role operational workflows.

The system integrates:

- Real-time GPS tracking
- Trip-state management
- Interactive maps
- Live notifications
- Multi-role user workflows
- Backend data management

Real-time communication is handled through **Socket.IO**, while the system combines frontend, backend, database, and mapping components into an end-to-end transportation platform.

`Next.js` `React` `Node.js` `Express` `Socket.IO` `MySQL`

---

## Research Interests

```text
Computer Vision
├── Facial Expression Recognition
├── Vision Transformers
├── Graph-based Vision
├── Medical Imaging
└── Vision-Language Modeling

Graph Learning
├── Graph Neural Networks
├── Pixel-level Graph Representation
├── Learned Graph Clustering
├── Graph Attention
└── Relational Modeling

Multimodal AI
├── Vision + Language
├── RGB / Multispectral / Hyperspectral Fusion
├── Cross-modal Representation Learning
└── Multimodal Retrieval

AI Engineering
├── Model Training & Evaluation
├── AI Service Integration
├── FastAPI / REST APIs
├── Distributed Training
├── GPU / CPU Optimization
└── Model Deployment
