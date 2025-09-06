---
title: "Technical Projects"
layout: single
author_profile: true
permalink: /projects/
classes: wide
---

## GPU Performance Engineering Projects

### SC25 Poster: GPU Acceleration of LESLIE Solver
**Technologies:** CUDA Fortran, MPI, NCCL, UCX, Nsight Systems/Compute

**Objective:** Accelerate legacy computational fluid dynamics code on NVIDIA A100 GPUs

**Technical Approach:**
- **Kernel optimization:** Loop fusion, register pressure reduction, shared memory utilization
- **Instruction optimization:** DFMA utilization, branchless MERGE operations, instruction scheduling
- **Communication optimization:** CUDA-aware MPI with NCCL and UCX backends

**Performance Results:**
- 38× speedup vs dual-socket Xeon Platinum 8360Y (60 cores)
- ConsToPrim kernel achieved 57% of FP64 peak utilization
- 93% reduction in warp execution stalls

**Key Insight:** Roofline analysis revealed memory-bound characteristics, guiding optimization strategy toward memory access pattern improvements.

---

### Multi-GPU Communication Framework Analysis  
**Technologies:** MPI, CUDA-aware MPI, NCCL, UCX, Nsight Systems

**Objective:** Benchmark and optimize communication patterns for multi-GPU applications

**Methodology:**
- Developed AXPY benchmark covering MPI → CUDA-aware MPI → NCCL → UCX
- Profiled transport layer selection (NVLink, PCIe, InfiniBand)
- Analyzed latency/throughput tradeoffs for different message sizes

**Results:**
- Reduced communication latency from 45 ms to 1.267 ms (18× improvement)
- Identified optimal communication backend for various message size regimes
- Documented performance characteristics for different interconnect technologies

---

### 3D CNN with Non-Local Attention for Video Recognition
**Technologies:** PyTorch, TensorFlow, CUDA, NVIDIA H100

**Objective:** Extend 3D CNN architecture with self-attention mechanisms

**Approach:**
- Implemented non-local attention blocks for spatiotemporal feature capture
- Profiled performance on NVIDIA H100 GPUs
- Identified optimization opportunities through systematic profiling

**Results:**
- 0.8357 accuracy on UCF-101 16-class subset
- Identified 65% Host→Device communication bottleneck
- Planned optimization: Fused CUDA operator for attention computation

[Return to homepage](/)
