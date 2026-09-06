# mini-vllm

An educational, bare-metal LLM inference and serving engine built from scratch.

This project implements the systems engineering principles behind production inference engines like vLLM, TGI, and SGLang. It is developed as part of **Track 1 (LLM Inference & Serving Systems)** defined in the master learning curriculum.

---

## Roadmap & Milestones

All master milestones, chapters, study notes, and completion checklists are tracked in the single source of truth:

👉 **[Master Curriculum & Checklist in `learning/README.md`](../learning/README.md)**

---

## High-Level Progression

1. **Chapter 0**: Physical Grounding & Raw Model Artifacts (Safetensors, BPE Tokenizers, bare-metal forward pass).
2. **Chapter 1**: The Inference Lifecycle & KV-Cache Bottleneck.
3. **Chapter 2**: Memory Management & PagedAttention.
4. **Chapter 3**: Continuous Batching & Request Scheduling.
5. **Chapter 4**: Transport Protocols & Low-Latency Streaming (SSE / gRPC).
6. **Chapter 5**: Quantization & Model Compression (INT8).
7. **Chapter 6**: Dynamic Adapters & Multi-Tenancy (LoRA Serving).

