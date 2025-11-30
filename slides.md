---
marp: true
title: Product Documentation Presentation
paginate: true
math: mathjax
---

<!-- _class: lead -->

<style>
section { font-family: Arial, sans-serif; }
section::after {
  content: attr(data-marpit-pagination) "/" attr(data-marpit-pagination-total);
  position: absolute;
  bottom: 12px;
  right: 18px;
  font-size: 0.75em;
  color: #666;
}
h1 { color: #1e90ff; }
</style>

# Product Documentation
### Author: 23f3004149@ds.study.iitm.ac.in

---

<!-- _class: lead -->

![bg](https://images.unsplash.com/photo-1555066931-4365d14bab8c)

# Documentation Strategy

- Markdown-first workflow  
- Version-controlled docs  
- Multi-format export  
- Lightweight + portable  
- Easy to maintain  

---

<!-- _class: lead -->

# Why Marp?

- Markdown → Slides  
- Background images  
- Page numbers  
- CSS customization  
- Marp directives  
- **Math (via MathJax)**

---

# Algorithmic Complexity (LaTeX)

The merge-sort recurrence:

$$
T(n) = 2T\left(\frac{n}{2}\right) + O(n)
$$

Using the Master Theorem:

$$
T(n) = O(n \log n)
$$

---

# Example Code

```python
def merge_sort(arr):
    if len(arr) <= 1:
        return arr
    mid = len(arr) // 2
    left = merge_sort(arr[:mid])
    right = merge_sort(arr[mid:])
    return merge(left, right)
