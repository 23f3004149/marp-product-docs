---
marp: true
title: Product Documentation Presentation
paginate: true
theme: custom-tech
---

<!-- theme: custom-tech -->
<!-- paginate: true -->

<style>
@import "https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github-dark.min.css";

section {
  font-family: Helvetica, Arial, sans-serif;
}

h1 {
  color: #1e90ff;
}

section::after {
  content: attr(data-marpit-pagination) "/" attr(data-marpit-pagination-total);
  position: absolute;
  bottom: 10px;
  right: 20px;
  font-size: 0.75em;
  color: #888;
}
</style>

# Product Documentation  
### Author: 23f3004149@ds.study.iitm.ac.in

---

![bg](https://images.unsplash.com/photo-1555066931-4365d14bab8c)

# Documentation Strategy

- Markdown-first workflow  
- Version-controlled documentation  
- Export to PDF/HTML/PPTX  
- Custom Marp theme  
- Portable & maintainable  

---

<!-- class: lead -->

# Why Marp?

- Markdown → Slides  
- Git-friendly  
- CI/CD automation  
- Supports:
  - Themes  
  - Backgrounds  
  - Directives  
  - Math  

---

# Algorithmic Complexity

\[
T(n)=2T\left(\frac{n}{2}\right) + O(n)
\]

\[
T(n)=O(n \log n)
\]

---

# Example Code

```python
def hello():
    return "Hello world"
