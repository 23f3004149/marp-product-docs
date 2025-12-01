---
marp: true
theme: mytheme
title: "Product Documentation – Architecture Overview"
paginate: true
author: "Vaibhav (23f3004149@ds.study.iitm.ac.in)"
---

<!-- _paginate: true -->
<!-- _theme: mytheme -->

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
    color: #888;
  }
}
</style>

# Product Documentation  
### Architecture Overview  
Email: **23f3004149@ds.study.iitm.ac.in**

---

# Agenda
<!-- _class: lead -->
- Product overview  
- Architecture  
- Workflow  
- Complexity equations  
- Deployment  

---

<!-- _backgroundImage: "https://images.unsplash.com/photo-1518770660439-4636190af475" -->
<!-- _backgroundSize: cover -->

# System Architecture
This slide uses a background image via Marp directive.

---

# Algorithmic Complexity

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
