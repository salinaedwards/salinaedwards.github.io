---
layout: page
permalink: /CV/
title: Curriculum Vitae
---

<div class="pdf-viewer">
  <embed src="/assets/Salina_Edwards_CV.pdf" type="application/pdf">
</div>

<p class="pdf-download">
  <a href="/assets/Salina_Edwards_CV.pdf" download>  Download CV ⬇️ (PDF)</a>
</p>

<style> 
.pdf-viewer {
  width: 100%;
  height: 90vh; /* use most of the viewport height */
}

.pdf-viewer embed {
  width: 100%;
  height: 100%;
  border: none;
}

/* On small screens, hide embed and show only the download link */
@media (max-width: 768px) {
  .pdf-viewer {
    display: none;
  }
  .pdf-download {
    text-align: center;
    font-size: 1.1em;
    margin-top: 2em;
  }
  .pdf-download a {
    background-color: white;
    color: #007acc;
    padding: 10px 16px;
    border-radius: 6px;
    text-decoration: none;
  }
  .pdf-download a:hover {
    background-color: #005fa3;
  }
}
</style>
