---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi, I am **{{ site.author.name }}!** :wave:,<br>
Welcome to my personal website! I'm a bioinformatics researcher passionate about exploring the molecular underpinnings of human diseases through computational biology. My work focuses on transcriptomics and genomics, with a strong interest in host-microbiome interactions, autoimmune disorders, and infectious diseases. Currently, I am developing end-to-end RNA-seq pipelines for bacterial transcriptomics, handling tasks from raw data preprocessing to differential gene expression and visualization. I enjoy bridging wet-lab questions with computational insights and often work as the bioinformatician in a fast-paced research lab environment.

My curiosity for biomedical data science has led me to projects involving pangenome analysis, precision medicine in autoimmune diseases like rheumatoid arthritis, and the study of ESKAPE pathogens. I’m particularly drawn to single-cell sequencing and machine learning for their transformative potential in healthcare. Long-term, I aspire to work at the intersection of life sciences and high-performance computing — applying cutting-edge tools to solve real-world problems in human health.

---


<div class="row">
  <div class="col-md-6">
    <h2>🧠 Programming Skills</h2>
    {% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
  </div>
  <div class="col-md-6">
    <h2>🔬 Domain Tools / Bioinformatics</h2>
    {% include about/skills.html title="Domain Tools & Libraries" source=site.data.other-skills %}
  </div>
</div>

<div class="row">
{% include about/timeline.html %}
</div>
