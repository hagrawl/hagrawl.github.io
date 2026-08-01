---
layout: page
title: Systolic GEMM Accelerator
description: Output-Stationary Pipelined Systolic GEMM Accelerator & Dataflow Controller
img: assets/img/12.jpg
importance: 1
category: hardware
---

### Overview
Parametrized pipelined Processing Element (PE) architecture with Stage-0 input capture and Stage-1 multiply-accumulate.

### Key Highlights
- **Dataflow Controller:** Designed to sample streaming data before PE elements.
- **Ping-Pong Buffer:** Reorganizes HOST/CPU streams into structured matrix format.
- **Streaming Output Collector:** Captures accumulator values and routes tile data back.
- **EDA Synthesis & Validation:** Synthesized and timing-validated on **AMD Vivado**.
