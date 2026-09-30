---
title: "Why your video pipeline is leaving 10× on the table"
description: "Week 2: CPU software encoders vs NVENC hardware encoding — first benchmarks"
date: 2026-10-13
draft: true
tags: ["video", "nvenc", "ffmpeg", "gpu"]
---

Week 2 of learning GPU/perf in public. Baseline question: same content, same
codec (H.264), same quality target — how far apart are `libx264` (CPU) and
`h264_nvenc` (GPU) on speed, and what does each cost you in quality?

Test setup: rented L4, Big Buck Bunny + Tears of Steel clips, VMAF for quality.
Numbers land here when the benchmark run is done.

<!-- TODO(benchmark): fill tables from run output; do not publish without numbers -->
