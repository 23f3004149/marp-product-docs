---
marp: true
theme: custom-theme
paginate: true
headingDivider: 2
title: "Product Documentation – Architecture Overview"
description: "Marp documentation demo by Vaibhav"
author: "Vaibhav (23f3004149@ds.study.iitm.ac.in)"
---

<!--
CUSTOM THEME
This block defines a custom Marp theme directly inside the Markdown.
-->
<style>
@theme custom-theme {
  /* Base styles */
  section {
    font-family: "Segoe UI", sans-serif;
    padding: 40px;
  }

  h1 {
    color: #1976D2;
    font-weight: 700;
  }

  h2 {
    color: #0D47A1;
    border-bottom: 2px solid #BBDEFB;
    padding-bottom: 6px;
  }

  p strong {
    color: #E91E63;
  }

  /* Page numbers */
  section::after {
    content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
    position: absolute;
    bottom: 20px;
    right: 40px;
    font-size: 0.8rem;
    color: #555;
  }
}
</style>

# Product Documentation  
### Architecture Overview  
**Author:** 23f3004149@ds.study.iitm.ac.in

---

# Agenda

- Product overview  
- System architecture  
- API workflow  
- Algorithmic complexity  
- Deployment pipeline  

---

# Product Overview

Our software provides:

- Modular components  
- Scalable REST APIs  
- Containerized deployment  
- Version-controlled documentation  

---

<!-- background image slide -->
<!-- Replace with your own image file -->
<!-- Tip: store images in /assets folder for clean version control -->
![bg](https://images.unsplash.com/photo-1518770660439-4636190af475)

# System Architecture

This slide uses a **background image**, rendered by Marp.

---

# API Workflow

```mermaid
sequenceDiagram
    Client->>API: Request
    API->>Service: Validate + Process
    Service->>DB: Query
    DB-->>Service: Results
    Service-->>Client: Response
