---
title: "Home"
layout: single
author_profile: true
---

# Hi, I’m Vijay Prabhas👋

Graduate Research Assistant @ Georgia Tech, specializing in **GPU Acceleration & HPC Performance Optimization**.  
Focused on CUDA kernel tuning, communication runtimes (MPI, NCCL, UCX), and scaling scientific solvers on modern NVIDIA GPUs.  

🔗 [Resume](/assets/docs/Resume_draft.pdf) · [LinkedIn](https://linkedin.com/in/vijaykodamalla) · [GitHub](https://github.com/vkodamalla3)

---
title: "Education"
layout: single
author_profile: true
permalink: /education/
---


- **Georgia Institute of Technology** (Aug 2024 – May 2026)
M.S. Computational Science & Engineering, Atlanta, GA


- **Indian Institute of Technology, Dharwad** (Aug 2020 – May 2024)
B.Tech. Mechanical, Materials & Aerospace Engineering, Dharwad, India


---

---
title: "Skills"
layout: single
author_profile: true
permalink: /skills/
---


### Programming
- C/C++, Fortran (F90), CUDA C++, CUDA Fortran, Python


### Parallel & Runtime
- MPI (OpenMPI, HPC-X), CUDA-aware MPI, NCCL, UCX, OpenACC


### Deep Learning
- PyTorch, TensorFlow


### Profiling & Debugging
- NVIDIA Nsight Systems, NVIDIA Nsight Compute, TensorBoard


### Systems Tools
- Linux, Git, Slurm


---
---
title: "Projects"
layout: single
author_profile: true
permalink: /projects/
---


## 🚀 SC25 Poster – GPU Acceleration & Optimizations of LESLIE
- Achieved **38× speedup** on NVIDIA A100 vs 60-core Xeon CPU.
- Optimizations at kernel-level (loop fusion, register reuse), instruction-level (DFMA, branchless MERGE), and communication-level (CUDA-aware MPI, NCCL, UCX).
- Profiling with Nsight Systems/Compute and roofline analysis guided optimization strategy.
- **Result**: ConsToPrim kernel hit **57% FP64 peak utilization**.


---


## 🔬 Graduate Research Assistant – LESLIE Solver Optimization
- Ported legacy Fortran90 + MPI CFD solver with OpenACC/NVHPC.
- Improved **SM busy >54%**, reduced warp stalls by **93%**, and increased compute throughput by **+413%**.
- Multi-node scaling across NVLink, PCIe, and InfiniBand interconnects.
- Submitted as research poster for **SC25 (St. Louis)**.


---


## ⚡ Multi-GPU Communication Benchmarks (AXPY)
- Developed benchmarks with MPI → CUDA-aware MPI → CUDA Streams → NCCL → UCX.
- Reduced communication latency from **45 ms → 1.267 ms (18× faster)** using CUDA-IPC and custom reductions.
- Benchmarked UCX transport selection (NVLink, PCIe, InfiniBand) with Nsight Systems.


---


## 🎥 3D CNN + Non-Local Self-Attention (UCF-101)
- Built 3D CNN baseline + late-stage attention block → **0.8357 accuracy** on 16-class subset.
- Profiling on NVIDIA H100 identified **65% Host-to-Device bottleneck**.
- Next step: implement fused TensorFlow CUDA op for attention.


---




