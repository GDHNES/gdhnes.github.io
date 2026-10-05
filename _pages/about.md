---
permalink: /
title: ""
excerpt: "Huang Zhibai studies heterogeneous computing, virtualization, I/O, and performance."
author_profile: false
classes: wide
share: false
redirect_from:
  - /about/
  - /about.html
---

<div class="hz-home">

<section class="hz-hero" aria-labelledby="home-title">
  <div class="hz-hero__copy">
    <div class="hz-kicker"><span aria-hidden="true">👋</span> Huang Zhibai (黄知柏)</div>

    <h1 id="home-title" class="hz-hero__title">
      Hi, I'm Zhibai.
    </h1>

    <p class="hz-hero__tagline">
      I work on systems at the boundary between software and hardware.
    </p>

    <p class="hz-hero__meta">
      Doctoral candidate at Shanghai Jiao Tong University<br>
      Shanghai, China
    </p>

    <p class="hz-hero__intro">
      I like figuring out what a system really does when requests cross CPUs,
      devices, and virtual machines. I also study the moments when our
      measurements stop telling the full story. My work spans tracing, workload
      validation, and performance engineering. Before and alongside research,
      I've worked on cloud virtualization and embedded software.
    </p>

    <div class="hz-actions" aria-label="Profile links">
      <a class="hz-btn hz-btn--primary" href="/files/Huang_Zhibai_CV.pdf">CV</a>
      <a class="hz-btn" href="https://scholar.google.com/citations?hl=en&user=R2_n7FQAAAAJ">Google Scholar</a>
      <a class="hz-btn" href="https://github.com/GDHNES/">GitHub</a>
      <a class="hz-btn" href="mailto:paynqueller@sjtu.edu.cn">Email</a>
    </div>
  </div>

  <aside class="hz-hero__aside" aria-label="Profile">
    <div class="hz-photo-slot" role="img" aria-label="Profile photo placeholder">
      <span><span aria-hidden="true">📷</span> Portrait</span>
      <small>coming soon</small>
    </div>
    <div class="hz-currently">
      <span class="hz-currently__label"><span aria-hidden="true">📍</span> Currently</span>
      <strong>Doctoral candidate</strong>
      <span class="hz-currently__degree">D.Eng.</span>
      <p>School of Computer Science<br>Shanghai Jiao Tong University</p>
      <span class="hz-currently__detail">Graduating in June 2027</span>
    </div>
  </aside>
</section>

<section id="research" class="hz-section hz-anchor">
  <div class="hz-section__head">
    <div>
      <div class="hz-kicker"><span aria-hidden="true">🧭</span> Research</div>
      <h2>What I'm working on</h2>
    </div>
    <p>
      I work on recovering the work hidden across device stacks and understanding
      whether a workload tells us the truth about real hardware.
    </p>
  </div>

  <div class="hz-primary-grid">
    <article class="hz-research-card hz-research-card--primary">
      <h3>Cross Layer Observability and Diagnosis</h3>
      <p>
        Recover request semantics across CPUs, GPUs, NICs, storage, shared workers,
        batching, and asynchronous device execution.
      </p>
      <div class="hz-project-line">
        <span>DevTrace</span><span>GhostDriver</span><span>Cloud / HPC extension</span>
      </div>
      <div class="hz-evidence">
        <span><strong>8 KB</strong> trace buffer</span>
        <span><strong>0.6% to 2.6%</strong> CPU overhead</span>
        <span><strong>38.8%</strong> lower median short request latency</span>
      </div>
    </article>

    <article class="hz-research-card hz-research-card--primary">
      <h3>Hardware Grounded Workload Fidelity</h3>
      <p>
        Test whether synthetic traces and proxy workloads remain valid after real
        hardware and software feedback, and whether they preserve the decision that matters.
      </p>
      <div class="hz-project-line">
        <span>Phantom</span><span>MockingbirdBench</span><span>vIOForge</span>
      </div>
      <div class="hz-evidence">
        <span>Offline similarity disagrees with hardware response in
          <strong>25 / 30</strong> candidate sets</span>
        <span><strong>13% to 19%</strong> capacity error</span>
      </div>
    </article>
  </div>

  <div class="hz-secondary-grid">
    <article class="hz-research-card hz-research-card--secondary">
      <h3>Hardware Aware Model Adaptation</h3>
      <p>
        Memory efficient fine tuning and heterogeneous CPU/GPU execution for
        resource constrained AI systems.
      </p>
      <div class="hz-project-line"><span>SkiST</span><span>TWIST / SNN-4-All</span></div>
    </article>

    <article class="hz-research-card hz-research-card--secondary">
      <h3>Mixed Criticality Virtualization</h3>
      <p>
        Explicit authority, bounded cross domain service, and safety observation
        for partitioned robotic systems.
      </p>
      <div class="hz-project-line"><span>Jiao</span><span>TONG</span></div>
    </article>
  </div>
</section>

<section id="work" class="hz-section hz-anchor">
  <div class="hz-section__head hz-section__head--compact">
    <div>
      <div class="hz-kicker"><span aria-hidden="true">🛠️</span> Selected work</div>
      <h2>Projects and results</h2>
    </div>
    <a class="hz-text-link" href="/publications/">All publications →</a>
  </div>

  <div class="hz-work-list">
    <article class="hz-work">
      <div class="hz-work__venue hz-venue--review">Under review</div>
      <div class="hz-work__body">
        <h3>GhostDriver</h3>
        <p>
          End to end request ownership across shared workers, batching, and
          asynchronous heterogeneous execution.
        </p>
        <div class="hz-metrics">
          <span>8,616 backend objects</span>
          <span>38.8% lower median short request latency</span>
        </div>
      </div>
    </article>

    <article class="hz-work">
      <div class="hz-work__venue">MICRO ’26</div>
      <div class="hz-work__body">
        <h3>SNN-4-All / TWIST</h3>
        <p>
          Heterogeneous fine tuning that exploits temporal sparsity, low rank
          adaptation, mixed precision, and configurable CPU/GPU placement.
        </p>
        <div class="hz-metrics">
          <span>~75 GB → 14.8 GB accelerator memory at 1B scale</span>
          <span>~5.1× reduction</span>
        </div>
        <div class="hz-inline-links">
          <a href="https://github.com/GDHNES/SNN-4-ALL-AE-release">Artifact</a>
        </div>
      </div>
    </article>

    <article class="hz-work">
      <div class="hz-work__venue">DAC ’26</div>
      <div class="hz-work__body">
        <h3>The Phantom of PCIe</h3>
        <p>
          PCIe trace synthesis with calibration against real trace behavior,
          connecting generative models to practical peripheral workloads.
        </p>
        <div class="hz-metrics">
          <span>up to 1000× task specific metric improvement</span>
          <span>up to 2.19× FID improvement</span>
        </div>
      </div>
    </article>

    <article class="hz-work">
      <div class="hz-work__venue">TCAD ’26<br>ICCAD ’25</div>
      <div class="hz-work__body">
        <h3>DevTrace</h3>
        <p>
          Lightweight software semantic tracing at host/device boundaries across
          PCIe peripherals and heterogeneous operating environments.
        </p>
        <div class="hz-metrics">
          <span>8 KB lossless trace buffer</span>
          <span>0.6% to 2.6% CPU overhead</span>
        </div>
      </div>
    </article>
  </div>
</section>

<section id="opensource" class="hz-section hz-anchor">
  <div class="hz-section__head hz-section__head--compact">
    <div>
      <div class="hz-kicker"><span aria-hidden="true">🧪</span> Open source</div>
      <h2>Code you can explore</h2>
    </div>
  </div>

  <div class="hz-open-grid">
    <a class="hz-open-card" href="https://github.com/GDHNES/vIOForge">
      <div>
        <h3>vIOForge</h3>
        <p>Decision grounded qualification for virtualized I/O workloads.</p>
      </div>
      <span>GitHub ↗</span>
    </a>

    <a class="hz-open-card" href="https://github.com/GDHNES/SNN-4-ALL-AE-release">
      <div>
        <h3>SNN-4-All / TWIST Artifact</h3>
        <p>Reproducible heterogeneous fine tuning experiments and checkpoints.</p>
      </div>
      <span>GitHub ↗</span>
    </a>
  </div>
</section>

<section id="background" class="hz-section hz-anchor">
  <div class="hz-section__head hz-section__head--compact">
    <div>
      <div class="hz-kicker"><span aria-hidden="true">🧩</span> Background</div>
      <h2>Where I've worked</h2>
    </div>
  </div>

  <div class="hz-timeline">
    <div class="hz-timeline__item">
      <span class="hz-timeline__time">2023 to 2027</span>
      <div>
        <strong>Shanghai Jiao Tong University</strong>
        <p>D.Eng. candidate in Electronic and Information Engineering, Computer Science track.</p>
      </div>
    </div>
    <div class="hz-timeline__item">
      <span class="hz-timeline__time">2025 to 2026</span>
      <div>
        <strong>Huawei Technologies</strong>
        <p>Joint doctoral training on cloud virtualization and virtualized I/O validation.</p>
      </div>
    </div>
    <div class="hz-timeline__item">
      <span class="hz-timeline__time">2021 to 2023</span>
      <div>
        <strong>East China Institute of Computing Technology</strong>
        <p>Production embedded systems, RTOS diagnostics, tracing, and BMC software.</p>
      </div>
    </div>
  </div>
</section>

<section id="recent" class="hz-section hz-section--last hz-anchor">
  <div class="hz-section__head hz-section__head--compact">
    <div>
      <div class="hz-kicker"><span aria-hidden="true">✨</span> Recent</div>
      <h2>What's new</h2>
    </div>
  </div>

  <div class="hz-news">
    <div class="hz-news__item"><span>2026</span><p><strong>SNN-4-All</strong> accepted to MICRO ’26.</p></div>
    <div class="hz-news__item"><span>2026</span><p><strong>Phantom</strong> and <strong>SkiST</strong> accepted to DAC ’26.</p></div>
    <div class="hz-news__item"><span>2026</span><p>The extended <strong>DevTrace</strong> work appeared in IEEE TCAD.</p></div>
    <div class="hz-news__item"><span>2025</span><p><strong>DevTrace</strong> appeared at ICCAD ’25.</p></div>
  </div>
</section>

</div>
