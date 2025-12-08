---
marp: true
paginate: true
theme: tech-theme
footer: "Email: 23f3004149@ds.study.iitm.ac.in"
---

<!--
This is the custom theme required by the question.
-->
<style>
/* @theme tech-theme */
section {
  font-family: "Segoe UI", sans-serif;
  padding: 40px;
  font-size: 28px;
}
h1, h2 {
  color: #0d47a1;
}
code {
  background: #f2f2f2;
  padding: 4px 8px;
  border-radius: 4px;
}
footer {
  font-size: 0.7rem;
}
</style>

# Product Documentation Overview  
**Technical Writer Presentation**  
Email: 23f3004149@ds.study.iitm.ac.in

---

## Goals
- Version-controlled docs (GitHub)
- Auto-convert Markdown → PDF/HTML/PPTX  
- Use Marp for consistency  
- Define custom theming

---

## Algorithmic Complexity Example

\[
T(n) = O(n \log n)
\]

This reflects indexing/processing operations in documentation build pipelines.

---

---
backgroundImage: "https://images.unsplash.com/photo-1518779578993-ec3579fee39f"
backgroundSize: cover
backgroundOpacity: 0.25
---

# Documentation Workflow (With Background Image)

- Git-based editing  
- Automated builds  
- CI/CD for exporting formats  
- Review loops inside version control  

---

## Build Command Example

```bash
marp slides.md --html --pdf --pptx
