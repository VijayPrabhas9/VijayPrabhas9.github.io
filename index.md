---
title: "Vijay Prabhas Kodamalla"
layout: single
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/tech-banner.jpg
  actions:
    - label: "View My Projects"
      url: "/projects/"
    - label: "Download Resume"
      url: "/assets/docs/Resume_draft.pdf"
excerpt: "Graduate Researcher specializing in HPC & GPU Performance Engineering"
classes: wide
---

<style>
  .feature-box {
    background: #f8f8f8;
    border-radius: 8px;
    padding: 25px;
    margin-bottom: 25px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
  }
  
  .feature-box:hover {
    transform: translateY(-5px);
  }
  
  .nav-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin: 40px 0;
  }
  
  .nav-card {
    background: white;
    border-radius: 8px;
    padding: 25px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
  }
  
  .nav-card:hover {
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    transform: translateY(-5px);
  }
  
  .nav-card i {
    font-size: 2.5rem;
    margin-bottom: 15px;
    color: #0077cc;
  }
  
  .about-section {
    margin: 40px 0;
    padding: 30px;
    background: #f8f8f8;
    border-radius: 8px;
  }
  
  .skill-pill {
    display: inline-block;
    background: #e9ecef;
    padding: 5px 12px;
    border-radius: 20px;
    margin: 5px;
    font-size: 0.85rem;
  }
  
  .stats-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 15px;
    margin: 30px 0;
    text-align: center;
  }
  
  .stat-item {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  
  .stat-number {
    font-size: 2rem;
    font-weight: bold;
    color: #0077cc;
    display: block;
  }
</style>

<section class="about-section">
  <h2>About Me</h2>
  <p>I'm a Graduate Research Assistant at Georgia Tech specializing in High Performance Computing and GPU acceleration. My work focuses on optimizing large-scale computational solvers and deep learning models through CUDA kernel tuning, communication optimizations, and multi-node scaling on modern NVIDIA GPUs.</p>
  
  <p>With expertise spanning from low-level CUDA programming to distributed computing with MPI and NCCL, I bridge the gap between theoretical algorithms and practical high-performance implementations.</p>
  
  <div class="stats-grid">
    <div class="stat-item">
      <span class="stat-number">38×</span>
      <span>Speedup Achieved</span>
    </div>
    <div class="stat-item">
      <span class="stat-number">57%</span>
      <span>FP64 Utilization</span>
    </div>
    <div class="stat-item">
      <span class="stat-number">18×</span>
      <span>Faster Communication</span>
    </div>
    <div class="stat-item">
      <span class="stat-number">93%</span>
      <span>Reduced Warp Stalls</span>
    </div>
  </div>
</section>

<div class="nav-grid">
  <div class="nav-card">
    <i class="fas fa-project-diagram"></i>
    <h3>Projects</h3>
    <p>Explore my research projects in GPU acceleration and HPC optimization</p>
    <a href="/projects/" class="btn btn--primary">View Projects</a>
  </div>
  
  <div class="nav-card">
    <i class="fas fa-tools"></i>
    <h3>Skills</h3>
    <p>Detailed overview of my technical skills and proficiencies</p>
    <a href="/skills/" class="btn btn--primary">View Skills</a>
  </div>
  
  <div class="nav-card">
    <i class="fas fa-graduation-cap"></i>
    <h3>Education</h3>
    <p>My academic background and qualifications</p>
    <a href="/education/" class="btn btn--primary">View Education</a>
  </div>
  
  <div class="nav-card">
    <i class="fas fa-book"></i>
    <h3>Publications</h3>
    <p>My research publications and conference presentations</p>
    <a href="/publications/" class="btn btn--primary">View Publications</a>
  </div>
</div>

<section>
  <h2>Featured Work</h2>
  
  <div class="feature-box">
    <h3>SC25 Poster – GPU Acceleration & Optimizations of LESLIE</h3>
    <p>Achieved <strong>38× speedup</strong> on NVIDIA A100 vs 60-core Xeon CPU through multi-layer optimizations at kernel, instruction, and communication levels.</p>
    <p><strong>Key Result:</strong> ConsToPrim kernel reached <strong>57% FP64 utilization</strong> on A100 GPU.</p>
    <a href="/projects/" class="btn btn--info">Read More</a>
  </div>
  
  <div class="feature-box">
    <h3>Multi-GPU Communication Benchmarks</h3>
    <p>Benchmarked MPI → CUDA-aware MPI → NCCL → UCX, reducing communication latency from <strong>45 ms to 1.267 ms</strong> (18× faster).</p>
    <p>Profiled intra-node vs inter-node transport trade-offs on modern HPC systems.</p>
    <a href="/projects/" class="btn btn--info">Read More</a>
  </div>
</section>

<section style="text-align: center; margin: 50px 0;">
  <h2>Let's Connect</h2>
  <p>I'm always interested in discussing new research opportunities and collaborations.</p>
  <a href="/contact/" class="btn btn--success">Get In Touch</a>
</section>
