---
marp: true
theme: custom-theme
paginate: true
_paginate: true
---

<style>
/* @theme custom-theme */

section {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  background-color: #0b1020;
  color: #f5f5f5;
  padding: 40px;
}

h1, h2, h3 {
  font-weight: 700;
}

.lead {
  text-align: center;
}

.small {
  font-size: 0.8em;
  opacity: 0.85;
}

.footer-note {
  position: absolute;
  bottom: 10px;
  left: 40px;
  font-size: 0.7em;
  opacity: 0.7;
}
</style>

<!-- _class: lead -->

# Product Documentation with Marp

### Maintainable, Versioned, Multi-format Docs

**Author:** Vaibhav  
**Email:** 23f3004149@ds.study.iitm.ac.in

---

<!-- _class: lead -->

# Why Marp for Product Docs?

- Treat slides as **code** (Markdown + Git)
- Easy collaboration via **pull requests**
- Export to:
  - PDF
  - HTML
  - PPTX
- Reviewable, diffable documentation

---

## Documentation as Code

- Store docs in a **Git repo**  
- Use **branches** and **PR reviews**
- Changes are:
  - traceable  
  - revertible  
  - auditable  

`slides.md` lives alongside the product’s codebase.

---

## Custom Theme (Spec Preview)

Our custom theme (`custom-theme`) defines:

- Default font family
- Dark background: `#0b1020`
- Light text: `#f5f5f5`
- Slide padding for readability
- Utility classes:
  - `.lead` for centered layouts
  - `.small` for fine print
  - `.footer-note` for slide footers

---

<!--
_backgroundImage: url("https://picsum.photos/1600/900?blur=3")
_class: lead
-->

# Visual Design & Branding
---
marp: true
theme: custom-theme
paginate: true
_paginate: true
---

<style>
/* @theme custom-theme */

section {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  background-color: #0b1020;
  color: #f5f5f5;
  padding: 40px;
}

h1, h2, h3 {
  font-weight: 700;
}

.lead {
  text-align: center;
}

.small {
  font-size: 0.8em;
  opacity: 0.85;
}

.footer-note {
  position: absolute;
  bottom: 10px;
  left: 40px;
  font-size: 0.7em;
  opacity: 0.7;
}
</style>

<!-- _class: lead -->

# Product Documentation with Marp

### Maintainable, Versioned, Multi-format Docs

**Author:** Vaibhav  
**Email:** 23f3004149@ds.study.iitm.ac.in

---

<!-- _class: lead -->

# Why Marp for Product Docs?

- Treat slides as **code** (Markdown + Git)
- Easy collaboration via **pull requests**
- Export to:
  - PDF
  - HTML
  - PPTX
- Reviewable, diffable documentation

---

## Documentation as Code

- Store docs in a **Git repo**  
- Use **branches** and **PR reviews**
- Changes are:
  - traceable  
  - revertible  
  - auditable  

`slides.md` lives alongside the product’s codebase.

---

## Custom Theme (Spec Preview)

Our custom theme (`custom-theme`) defines:

- Default font family
- Dark background: `#0b1020`
- Light text: `#f5f5f5`
- Slide padding for readability
- Utility classes:
  - `.lead` for centered layouts
  - `.small` for fine print
  - `.footer-note` for slide footers

---

<!--
_backgroundImage: url("https://picsum.photos/1600/900?blur=3")
_class: lead
-->

# Visual Design & Branding

_Using a background image_

- Marp supports **background images** per slide
- Great for:
  - product hero shots  
  - architecture diagrams  
  - marketing-style intro slides  

---

## Page Numbers with Marp

We enabled page numbers via:

```yaml
---
marp: true
theme: custom-theme
paginate: true
_paginate: true
---

_Using a background image_

- Marp supports **background images** per slide
- Great for:
  - product hero shots  
  - architecture diagrams  
  - marketing-style intro slides  

---

## Page Numbers with Marp

We enabled page numbers via:

```yaml
---
marp: true
theme: custom-theme
paginate: true
_paginate: true
---
