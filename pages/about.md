---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi, I am **{{ site.author.name }}!:wave:**  
Welcome to my personal website! I'm a bioinformatics researcher passionate about exploring the molecular underpinnings of human diseases through computational biology. My work focuses on transcriptomics and genomics, with a strong interest in host-microbiome interactions, autoimmune disorders, and infectious diseases. 

---


<div class="row">
  <div class="col-12">
    <h2>💼 Skills</h2>
    {% include about/skills.html title="Skills" source=site.data.skills %}
  </div>
</div>

<div class="row">
  {% include about/timeline.html %}
</div>
