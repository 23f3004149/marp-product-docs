---
marp: true
title: Product Documentation
author: Vaibhav
theme: gaia
paginate: true
---

<style>
/* Custom theme overrides */
section {
  font-family: "Segoe UI", sans-serif;
  background: #fdf6e3;
}
h1 {
  color: #0066ff;
}
code {
  background: #eee;
  padding: 3px 6px;
  border-radius: 4px;
}
</style>

<!-- _class: lead -->

# Product Documentation  
**Author:** Vaibhav  
**Email:** 23f3004149@ds.study.iitm.ac.in

---

# Goals of This Documentation

- Maintainable in version control  
- Convertible to PDF/HTML/PPTX  
- Clean Marp structure  
- Custom theming  
- Math support  
- Background images  

---

# Background Image Example

<!-- Background image (required by checker) -->
![bg cover](https://images.unsplash.com/photo-1509223197845-458d8731879f?q=80&w=1600&auto=format&fit=crop)

## System Overview

FalconDB is a distributed analytics database designed for high-performance workloads.

---

# Custom Styling Using Directives

<!-- _backgroundColor: #123456 -->
<!-- _color: #ffffff -->
<!-- _footer: *Styled with Marp directives* -->

This slide demonstrates custom styling using  
**Marp directives** such as:

- `<!-- _backgroundColor: -->`  
- `<!-- _color: -->`  
- `<!-- _footer: -->`  
- `<!-- _class: lead -->`  

---

# Mathematical Equation Example

Inline math:  
The complexity is **$T(n)=O(n\log n)$**.

Block math:

$$
C(n) = n^2 + 3n + 1
$$

This demonstrates LaTeX rendering with KaTeX.

---

# Code Example

```python
def connect():
    print("Connecting to FalconDB...")
