---
title: "Vijay Prabhas Kodamalla"
layout: single
author_profile: true
header:
  overlay_image: /assets/images/tech-background.jpg
  overlay_filter: 0.15
  actions:
    - label: "Download Resume"
      url: "/assets/docs/resume.pdf"
classes: wide
---

<style>
  .portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
  }
  
  .portfolio-card {
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    padding: 1.5rem;
    transition: transform 0.3s ease;
  }
  
  .portfolio-card:hover {
    transform: translateY(-5px);
  }
  
  .skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 1rem 0;
  }
  
  .skill-pill {
    background: #f2f2f2;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    font-size: 0.85rem;
  }
  
  .hero-section {
    text-align: center;
    padding: 2rem 0;
  }
  
  .social-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin: 1rem 0;
  }
</style>

<section class="hero-section">
  <h1>Vijay Prabhas Kodamalla</h1>
  <p class="lead">Graduate Researcher specializing in HPC & GPU Performance Engineering</p>
  
  <div class="social-links">
    <a href="/assets/docs/resume.pdf" class="btn btn--primary">Resume</a>
    <a href="https://linkedin.com/in/vijaykodamalla" class="btn btn--info">
      <i class="fab fa-linkedin"></i> LinkedIn
    </a>
    <a href="https://github.com/vkodamalla3" class="btn btn--dark">
      <i class="fab fa-github"></i> GitHub
    </a>
  </div>
</section>

<section>
  <h2>About Me</h2>
  <p>I accelerate large-scale solvers and deep learning models on modern NVIDIA GPUs through CUDA kernel tuning, communication optimizations, and multi-node scaling. Currently pursuing my Master's at Georgia Tech with a focus on computational science and engineering.</p>
</section>

<section>
  <h2>Featured Projects</h2>
  <div class="portfolio-grid">
    <div class="portfolio-card">
      <h3>SC25 Poster – GPU Acceleration of LESLIE</h3>
      <p>Achieved <strong>38× speedup</strong> on NVIDIA A100 vs 60-core Xeon CPU through multi-layer optimizations.</p>
      <p><span class="skill-pill">CUDA</span> <span class="skill-pill">HPC</span> <span class="skill-pill">Optimization</span></p>
    </div>
    
    <div class="portfolio-card">
      <h3>Multi-GPU Communication Benchmarks</h3>
      <p>Benchmarked MPI → CUDA-aware MPI → NCCL → UCX, reducing latency from 45ms to 1.267ms (18× faster).</p>
      <p><span class="skill-pill">MPI</span> <span class="skill-pill">NCCL</span> <span class="skill-pill">UCX</span></p>
    </div>
    
    <div class="portfolio-card">
      <h3>3D CNN + Non-Local Self-Attention</h3>
      <p>Extended CNN with attention achieving 0.8357 accuracy on UCF-101, with profiling on H100 GPUs.</p>
      <p><span class="skill-pill">PyTorch</span> <span class="skill-pill">CUDA</span> <span class="skill-pill">Deep Learning</span></p>
    </div>
  </div>
</section>

<section>
  <h2>Technical Skills</h2>
  <div class="skills-container">
    <span class="skill-pill">C/C++</span>
    <span class="skill-pill">Fortran (F90)</span>
    <span class="skill-pill">CUDA C++</span>
    <span class="skill-pill">CUDA Fortran</span>
    <span class="skill-pill">Python</span>
    <span class="skill-pill">MPI</span>
    <span class="skill-pill">CUDA-aware MPI</span>
    <span class="skill-pill">NCCL</span>
    <span class="skill-pill">UCX</span>
    <span class="skill-pill">OpenACC</span>
    <span class="skill-pill">PyTorch</span>
    <span class="skill-pill">TensorFlow</span>
    <span class="skill-pill">Nsight Systems</span>
    <span class="skill-pill">Nsight Compute</span>
    <span class="skill-pill">TensorBoard</span>
    <span class="skill-pill">Linux</span>
    <span class="skill-pill">Git</span>
    <span class="skill-pill">Slurm</span>
  </div>
</section>

<section>
  <h2>Education</h2>
  <div class="portfolio-card">
    <h3>Georgia Institute of Technology</h3>
    <p><strong>M.S. Computational Science & Engineering</strong> | 2024–2026</p>
  </div>
  <div class="portfolio-card">
    <h3>IIT Dharwad</h3>
    <p><strong>B.Tech. Mechanical, Materials & Aerospace Engineering</strong> | 2020–2024</p>
  </div>
</section>

<section>
  <h2>Publications & Conferences</h2>
  <div class="portfolio-card">
    <h3>Supercomputing 2025 (SC25, St. Louis)</h3>
    <p>Poster submission: <em>GPU Acceleration & Optimizations of LESLIE</em></p>
  </div>
  <div class="portfolio-card">
    <h3>Journal of Parallel Computing</h3>
    <p>Planned submission based on current research</p>
  </div>
</section>

<section>
  <h2>Contact</h2>
  <div class="notice">
    <p><i class="fas fa-map-marker-alt"></i> Atlanta, GA</p>
    <p><i class="fas fa-envelope"></i> <a href="mailto:vkodamalla3@gatech.edu">vkodamalla3@gatech.edu</a></p>
    <p><i class="fab fa-linkedin"></i> <a href="https://linkedin.com/in/vijaykodamalla">linkedin.com/in/vijaykodamalla</a></p>
    <p><i class="fab fa-github"></i> <a href="https://github.com/vkodamalla3">github.com/vkodamalla3</a></p>
  </div>
</section>

<hr>

<p style="text-align: center; font-size: 0.8em; color: gray;">
Last updated: {{ site.time | date: "%B %d, %Y" }}
</p>
