---
layout: page
permalink: /CV/
title: Curriculum Vitae
---

---

<div class="pdf-viewer">
  <embed src="/assets/Salina_Edwards_CV.pdf" type="application/pdf">
</div>

<p class="pdf-download">
  <a href="/assets/Salina_Edwards_CV.pdf" download>Download CV (PDF)</a>
</p>

<style> 
/* ---------- Desktop defaults ---------- */
.pdf-viewer {
  width: 100%;
  height: 90vh; /* use most of the viewport height */
}

.pdf-viewer embed {
  width: 100%;
  height: 100%;
  border: none;
}

/* Hide the download link on desktop */
.pdf-download {
  display: none;
}

/* ---------- Mobile overrides ---------- */
@media (max-width: 768px) {
  .pdf-viewer {
    display: none;
  }
  .pdf-download {
    display: block;
    text-align: center;
    font-size: 1.1em;
    margin-top: 2em;
  }
  .pdf-download a {
    background-color: #007acc;
    color: white;
    padding: 10px 16px;
    border-radius: 6px;
    text-decoration: none;
  }
  .pdf-download a:hover {
    background-color: #005fa3;
  }
}
</style>
