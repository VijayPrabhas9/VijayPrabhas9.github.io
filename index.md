---
title: "Vijay Prabhas Kodamalla - HPC & GPU Performance Engineer"
layout: single
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/compute-banner.jpg
excerpt: "Specializing in CUDA optimization, multi-GPU scaling, and high-performance computing"
classes: wide
---

<style>
.performance-metrics {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
    margin: 2rem 0;
}
.metric-card {
    background: #fff;
    border: 1px solid #eaeaea;
    border-radius: 4px;
    padding: 1.5rem;
    text-align: center;
}
.metric-value {
    font-size: 2rem;
    font-weight: bold;
    color: #0077cc;
    display: block;
    margin-bottom: 0.5rem;
}
.tech-tag {
    display: inline-block;
    background: #f5f5f5;
    padding: 0.3rem 0.8rem;
    border-radius: 3px;
    font-size: 0.85rem;
    margin: 0.3rem;
    font-family: 'SF Mono', Monaco, monospace;
}
.project-highlight {
    border-left: 3px solid #0077cc;
    padding: 1rem 1.5rem;
    margin: 1.5rem 0;
    background: #fafafa;
}
</style>

## Performance Engineering Focus

I optimize computational workloads on NVIDIA GPUs through systematic analysis and targeted optimizations across kernel, instruction, and communication layers.

<div class="performance-metrics">
    <div class="metric-card">
        <span class="metric-value">38×</span>
        <span>Speedup achieved</span>
    </div>
    <div class="metric-card">
        <span class="metric-value">57%</span>
        <span>FP64 utilization</span>
    </div>
    <div class="metric-card">
        <span class="metric-value">18×</span>
        <span>Faster comms</span>
    </div>
    <div class="metric-card">
        <span class="metric-value">93%</span>
        <span>Stall reduction</span>
    </div>
</div>

## Technical Expertise

<div class="tech-tag">CUDA C++</div>
<div class="tech-tag">CUDA Fortran</div>
<div class="tech-tag">MPI</div>
<div class="tech-tag">NCCL</div>
<div class="tech-tag">UCX</div>
<div class="tech-tag">OpenACC</div>
<div class="tech-tag">Nsight Systems</div>
<div class="tech-tag">Nsight Compute</div>

## Recent Project Highlight

<div class="project-highlight">
### LESLIE Solver Optimization (SC25 Poster)
**Challenge:** Accelerate legacy Fortran/MPI CFD code on NVIDIA A100 GPUs

**Approach:** 
- Kernel-level: Loop fusion, register optimization
- Instruction-level: DFMA instructions, branchless MERGE operations  
- Communication-level: CUDA-aware MPI with NCCL/UCX backend

**Results:** 38× speedup vs 60-core Xeon, 57% FP64 utilization on ConsToPrim kernel
</div>

[View detailed projects](/projects/) | [Download resume](/assets/docs/resume.pdf)
