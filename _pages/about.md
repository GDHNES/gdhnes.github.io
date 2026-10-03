---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Doctoral Candidate (D.Eng.) in the School of Computer Science at
Shanghai Jiao Tong University, advised by Prof. Zhengwei Qi.

My research focuses on the hardware-software boundary of heterogeneous and
virtualized systems. I study how to recover request-level execution across
CPUs, GPUs, NICs, and storage, how to determine whether synthetic or proxy
workloads remain faithful after real hardware and software feedback, and how
to redesign systems or workloads when existing abstractions limit performance.

My work spans heterogeneous systems, virtualization, I/O and device systems,
performance observability and diagnosis, workload validation, and
hardware-aware model adaptation.

## Research

### Cross-Layer Observability and Diagnosis

I build low-overhead mechanisms for recovering request context across
heterogeneous device stacks.

**DevTrace** provides software-semantic tracing of host-device interactions
across PCIe peripherals and heterogeneous operating environments.
Its extended design achieves lossless tracing with an 8 KB buffer and
0.6–2.6% CPU overhead.

**GhostDriver** extends this direction to request ownership across shared
workers, batching, and asynchronous device execution. It validates exact
ownership across 8,616 backend objects and enables ownership-guided scheduling
that reduces median short-request latency by 38.8% in an on-device RAG
pipeline.

### Hardware-Grounded Workload Fidelity

I study when synthetic traces and proxy workloads remain valid after interacting
with real hardware and whether they preserve the system decision that matters.

**Phantom** combines generative trace synthesis with calibration, improving
task-specific PCIe trace metrics by up to 1000× and FID by up to 2.19×.

**MockingbirdBench** shows that offline similarity often fails to identify the
trace that best matches real hardware response, and can lead to 13–19% capacity
errors and false-safe decisions.

**vIOForge** extends this question to virtualized cloud platforms, showing that
even replaying the exact I/O request sequence does not necessarily preserve a
live database's SLO verdict after the platform changes.

## Additional Research

**Hardware-Aware Model Adaptation.**
SkiST and TWIST explore memory-efficient fine tuning and heterogeneous CPU/GPU
execution for resource-constrained AI systems.

**Mixed-Criticality Virtualization.**
Jiao and TONG study explicit authority, bounded cross-domain service, and safety
observation for partitioned robotic systems.

## Open Source

- [vIOForge](https://github.com/GDHNES/vIOForge)
- [SNN-4-All / TWIST Artifact](https://github.com/GDHNES/SNN-4-ALL-AE-release)

## Contact

Email: [paynqueller@sjtu.edu.cn](mailto:paynqueller@sjtu.edu.cn)

[Google Scholar](https://scholar.google.com/citations?hl=en&user=R2_n7FQAAAAJ) ·
[GitHub](https://github.com/GDHNES/)
