---
marp: true
paginate: true
theme: tech-theme
footer: "Email: 23f3004149@ds.study.iitm.ac.in"
---

<!-- Custom Marp Theme -->
<style>
/* @theme tech-theme */
section {
  font-family: "Segoe UI", sans-serif;
  padding: 40px;
}
h1, h2 {
  color: #0d47a1;
}
code {
  background: #f2f2f2;
  padding: 4px 6px;
  border-radius: 4px;
}
footer {
  font-size: 0.7rem;
}
</style>

# Product Documentation Overview
Email: **23f3004149@ds.study.iitm.ac.in**

---

## Documentation Goals
- Version-controlled  
- Multi-format export  
- Custom Marp theme  

---

## Algorithmic Complexity

\[
T(n) = O(n \log n)
\]

---

---
backgroundImage: "https://images.unsplash.com/photo-1518779578993-ec3579fee39f"
backgroundSize: cover
backgroundOpacity: 0.25
---

# Documentation Workflow  
*(Background image visible in Marp export)*

### And also visible in raw Markdown:

![Workflow Background](https://images.unsplash.com/photo-1518779578993-ec3579fee39f)

- Git-based workflow  
- CI/CD builds  
- Marp export  

---

## Build Command

```bash
marp slides.md --html --pdf --pptx
