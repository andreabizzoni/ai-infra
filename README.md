*Author: Andrea Bizzoni*

# AI infrastructure proposal

This repository contains a comprehensive proposal for building state-of-the-art AI infrastructure. The plan addresses four key areas:

## Documents

1.  **[Rapid Evaluation & Deployment Pipeline](task_1.md)**
    *   *Goal:* Evaluate and deploy new LLM models within 24 hours of publication.
    *   *Key Tech:* vLLM, LiteLLM, Automated Gauntlet Evals.

2.  **[RAG & Fine-Tuning Infrastructure](task_2.md)**
    *   *Goal:* Infrastructure for fine-tuning and building RAG workflows.
    *   *Key Tech:* Qdrant, Hybrid Search, Axolotl, LoRA Adapters.

3.  **[Specialized Model Deployment](task_3.md)**
    *   *Goal:* Deployment of specialized models.
    *   *Key Tech:* Triton Inference Server, ONNX/TensorRT, KServe.

4.  **[The Agent SDK](task_4.md)**
    *   *Goal:* Ergonomic abstractions for creating agentic workflows.
    *   *Key Tech:* LangGraph, Pydantic, Model Context Protocol (MCP).
