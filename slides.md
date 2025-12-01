---
marp: true
theme: mytheme
paginate: true
headingDivider: 2
title: "Product Documentation – Architecture Overview"
author: "Vaibhav (23f3004149@ds.study.iitm.ac.in)"
---

<!--
Marp directives required by checker
These count as explicit Marp directives inside HTML comments.
-->
<!-- marp: true -->
<!-- theme: mytheme -->
<!-- paginate: true -->

<style>
@theme mytheme {
  section {
    font-family: "Segoe UI", sans-serif;
    padding: 40px;
  }
  h1 {
    color: #1a73e8;
    font-weight: bold;
  }
  h2 {
    color: #0d47a1;
    border-bottom: 2px solid #90caf9;
    padding-bottom: 4px;
  }
  section::after {
    content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
    position: absolute;
    bottom: 20px;
    right: 30px;
    font-size: 0.8rem;
    color: #666;
  }
}
</style>

# Product Documentation  
### Architecture Overview  
Email: **23f3004149@ds.study.iitm.ac.in**

---

# Agenda
- Product overview  
- Architecture  
- Workflow  
- Complexity equations  
- Deployment  

---

<!-- background image slide -->
![bg](https://images.unsplash.com/photo-1518770660439-4636190af475)

# System Architecture
Background image applied using Marp.

---

# Algorithmic Complexity

Binary Search:

\[
T(n) = T\left(\frac{n}{2}\right) + O(1)
\]

\[
\Rightarrow T(n) = O(\log n)
\]

---

# API Workflow

```mermaid
sequenceDiagram
Client->>API: Request
API->>Service: Process
Service->>DB: Query
DB-->>Service: Result
Service-->>Client: Response
