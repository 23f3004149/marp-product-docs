---
marp: true
theme: custom-theme
paginate: true
_paginate: true
---

<style>
/* @theme custom-theme */

section {
  font-family: Arial, sans-serif;
  background: #0b1020;
  color: #ffffff;
  padding: 40px;
}

h1, h2, h3 {
  font-weight: bold;
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

# Why Marp?

- Write docs **as code**
- Version-control friendly  
- Export to:
  - PDF
  - PPTX
  - HTML  
- Great for engineering teams

---

## Documentation as Code

- Store slides in a **Git repo**  
- Review with **pull requests**  
- Automatically convert formats  
- Easy collaboration  

---

## Custom Theme Overview

Our custom theme defines:

- Dark background  
- Light text for contrast  
- System UI fonts  
- Utility classes:
  - `.lead`
  - `.small`
  - `.footer-note`

---

<!-- _backgroundImage: url("https://picsum.photos/1600/900?blur=3") -->
<!-- _class: lead -->

# Visual Design with Background Images

- Marp supports background images  
- Useful for hero sections  
- Helps brand your documentation  
- Clean & professional look  

---

## Page Numbers

Enabled via front-matter:

```yaml
paginate: true
_paginate: true
