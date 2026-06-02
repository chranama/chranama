# Christopher Anaya

Early-career software engineer building reliable AI systems, evaluation tooling, and backend workflows.

My current work is public, non-client open-source engineering focused on AI evaluation, backend runtime systems, and proof-oriented verification.

## Academic Background

- Master's degree in Data Science, University of Lisbon (Portugal), 2025
- Master's degree in Mathematics, University of Valencia (Spain), 2016
- Bachelor's of Arts in Astronomy, University of Colorado Boulder, 2013

## Skills

- Python AI backends and evaluation tooling
- Contract-driven validation, schema enforcement, and runtime policy gates
- Backend API design, async job workflows, and service-boundary architecture
- Operational observability, trace inspection, and reproducible proof artifacts
- LLM robustness evaluation and model-failure analysis, including biomedical QA
- Open-source systems engineering with CI, documentation, and reviewer-ready evidence

## Flagship Project

### LLM Extraction Platform

Open-source platform for model-backed workflows to extract structured data from natural language. Currently trained and evaluated on receipts corpus (https://huggingface.co/datasets/Voxel51/scanned_receipts). Implements schema contracts, capability-gated checks, PASS/FAIL proof artifacts, and inspectable runtime behavior.

- FastAPI `/generate` and `/extract` services
- Capability gating and deterministic PASS/FAIL evidence
- Async workflow boundaries and worker/runtime separation
- Prometheus-backed observability and operational inspection

Repository:
https://github.com/chranama/llm-extraction-platform

## Supporting Projects

### BioLLM-Finetune

Experiment-first biomedical QA infrastructure for robustness evaluation, controlled comparison, and model-failure analysis.  Created to evaluate model fine-tuning for QA tasks.

Repository:
https://github.com/chranama/biollm-finetune


### Inference Serving Gateway

Production-style inference gateway in Go focused on health/readiness semantics, request limits, forwarding, timeouts, and observability for model-serving backends. Provides a runtime boundary between product APIs and upstream inference services.

Repository:
https://github.com/chranama/inference-serving-gateway


### California-Portugal Climate Pipeline

End-to-end data and ML pipeline with layered dbt transforms, Prefect orchestration, tested anomaly features, and reproducible outputs.  Compares the climates of California and Portugal.

Repository:
https://github.com/chranama/california-portugal-climate


## Links

Portfolio home: https://chranama.github.io
LinkedIn: https://www.linkedin.com/in/chris-anaya-ai/
