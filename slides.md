---
marp: true
theme: custom-tech
paginate: true
footer: "Email: 23f3004149@ds.study.iitm.ac.in"
---

<!-- Custom Theme -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}
h1, h2, h3 {
  color: #0d47a1;
}
code {
  background: #f3f3f3;
  padding: 4px 6px;
  border-radius: 4px;
}
footer {
  font-size: 0.7rem;
  color: #555;
}
</style>

# **Product Documentation Overview**
## Technical Writer – Internal Presentation  
**Email:** 23f3004149@ds.study.iitm.ac.in

---

# **Objectives**
- Maintainable documentation in version control  
- Exportable to PDF, HTML, PPTX via Marp  
- Custom theme for consistency

---

# **Algorithmic Complexity Example**

\[
T(n) = O(n \log n)
\]

Used when processing and indexing large documentation repositories.

---

<!-- Background Image Slide -->
<!-- The correct Marp syntax must be in the slide frontmatter -->
---
backgroundImage: "https://images.unsplash.com/photo-1518779578993-ec3579fee39f"
backgroundSize: cover
backgroundOpacity: 0.25
---

# **Documentation Workflow**
## (Slide with Background Image)

- Git version control  
- CI-based auto builds  
- Marp CLI for multi-format export

---

# **Build Command Example**

```bash
marp slides.md --pdf --html --pptx
