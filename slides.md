---
marp: true
title: Product Documentation Presentation
paginate: true
theme: custom-tech
---

<!-- _class: lead -->

<style>
section { font-family: Arial, sans-serif; }
h1 { color: #1e90ff; }
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

- Markdown-first  
- Git-friendly  
- Custom styles  
- Theme support  
- Automated exports  

---

<!-- _class: lead -->

# Why Marp?

- Markdown → slides  
- Supports:
  - Backgrounds  
  - Themes  
  - Directives  
  - Math  

---

# Algorithmic Complexity

\[
T(n)=2T(n/2) + O(n)
\]

\[
T(n)=O(n\log n)
\]

---

# Example Code

```python
def hello():
    return "Hello World"
