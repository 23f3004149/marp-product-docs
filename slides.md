---
marp: true
theme: gaia
paginate: true
title: Product Documentation
author: Vaibhav
---

# Product Documentation  
**Email:** 23f3004149@ds.study.iitm.ac.in

---

# Contact Information
**Email:** 23f3004149@ds.study.iitm.ac.in

<style>
section {
  font-family: "Segoe UI", sans-serif;
}
h1, h2 {
  color: #0066ff;
}
</style>

---

# Product Documentation Overview  
This presentation demonstrates Marp: background images, custom styling, math, and documentation structure.

---

![bg cover](https://images.unsplash.com/photo-1509223197845-4588d7b8179f?q=80&w=1600&auto=format&fit=crop)

# System Overview  
FalconDB is a high-performance distributed database designed for real-time analytics.

<!-- _class: lead -->

---

# Features (Fragments)

- <span class="fragment">High-throughput ingestion</span>  
- <span class="fragment">Low-latency queries</span>  
- <span class="fragment">Adaptive sharding & replication</span>

---

# Algorithmic Complexity (Math Included)

Inline Math Example:  
The time complexity is **$T(n)=O(n \log n)$**.

Block Math Example:

$$
C(n) = n^2 + 3n + 2
$$

---

# Build Command

```bash
marp slides.md --html --pdf --pptx
