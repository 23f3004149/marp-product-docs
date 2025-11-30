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

- Git versioning  
- Markdown-first workflow  
- Custom styling  
- Export as HTML / PDF / PPTX  
- Custom theme support  

---

<!-- _class: lead -->

# Why Marp?

- Markdown → Slides  
- Background images  
- Themes  
- Marp directives  
- Math equations (LaTeX)  
- Declarative styling  

---

# Algorithmic Complexity (LaTeX Math)

The recurrence relation for merge sort is:

\[
T(n) = 2T\left(\frac{n}{2}\right) + O(n)
\]

Solving using the Master Theorem:

\[
T(n) = O(n \log n)
\]

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
