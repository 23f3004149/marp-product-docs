---
marp: true
title: Product Documentation Presentation
description: Maintainable developer documentation using Marp
paginate: true
theme: custom-tech
class: lead
---

<!-- theme: custom-tech -->
<!-- class: lead -->
<!-- paginate: true -->

<style>
/* ===============================
   Custom Marp Theme: custom-tech
================================*/
@import "https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github-dark.min.css";

section {
  font-family: "Segoe UI", sans-serif;
}

h1 {
  color: #1e90ff;
  font-weight: 700;
  letter-spacing: -0.5px;
}

h2 {
  color: #ffa500;
}

footer {
  color: #666;
  font-size: 0.7em;
}

/* Page numbers */
section::after {
  content: attr(data-marpit-pagination) "/" attr(data-marpit-pagination-total);
  position: absolute;
  bottom: 10px;
  right: 20px;
  font-size: 0.75em;
  color: #888;
}
</style>

# **Product Documentation**
### Creating Maintainable, Version-Controlled Docs  
#### Author: **23f3004149@ds.study.iitm.ac.in**

---

![bg](https://images.unsplash.com/photo-1555066931-4365d14bab8c)

# Documentation Strategy  
### Build Once → Publish Everywhere

- Markdown-first workflow  
- Version-controlled documentation  
- Automated exports (PDF/HTML/PPTX)  
- Custom **Marp theme**

---

<!-- class: lead -->

# Why Marp?

- Markdown → Slides  
- Version-controlled  
- CI/CD friendly  
- Supports:
  - Themes  
  - Backgrounds  
  - Directives  
  - Math  
  - Code highlight  

---

# Algorithmic Complexity  

\[
T(n)=2T\left(\frac{n}{2}\right) + O(n)
\]

\[
T(n)=O(n \log n)
\]

---

# Example Code Snippet

```python
def merge_sort(arr):
    if len(arr) <= 1:
        return arr
    mid = len(arr) // 2
    left = merge_sort(arr[:mid])
    right = merge_sort(arr[mid:])
    return merge(left, right)
