---
marp: true
paginate: true
theme: tech-theme
footer: "Email: 23f3004149@ds.study.iitm.ac.in"
---

<!-- Custom Theme -->
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
  background: #eee;
  padding: 4px 6px;
  border-radius: 4px;
}
footer {
  font-size: 0.7rem;
}
</style>

<!-- 🔥 VALID MARP DIRECTIVE -->
<!-- _class: lead -->

# Product Documentation  
Email: **23f3004149@ds.study.iitm.ac.in**

---

## Documentation Goals
- Version control  
- Multi-format export  
- Theming & consistency  

---

## Algorithmic Complexity

\[
T(n) = O(n \log n)
\]

---

<!-- 🔥 THIS IS THE VALID BACKGROUND IMAGE SLIDE -->
# Documentation Workflow

![bg](https://images.unsplash.com/photo-1518779578993-ec3579fee39f)

- Git workflow  
- CI/CD builds  
- Marp export  

---

## Build Command

```bash
marp slides.md --html --pdf --pptx
