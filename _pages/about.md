---
permalink: /
title: "Susanta's Details"
author_profile: true
classes: wide
redirect_from: 
  - /about/
  - /about.html
---

Hello, I am **Susanta Khamrui**, a final-year M.Tech CSE student at **IIITDM Jabalpur**. Under the supervision of **Dr. Ayan Seal**, I am working on my thesis in **Computer Vision** with an emphasis on **polyp segmentation**. Additionally, I assist with studies on **salient object detection**. Following my M.Tech, I intend to pursue a **PhD** because I have a strong interest in **medical imaging** and developing dependable computer vision systems.

---

## 🎯 Research Interests
- Computer Vision
- Salient Object Detection
- Medical Imaging

## 🎓 Education
- **M.Tech in Computer Science & Engineering**, IIITDM Jabalpur — *Final Year*

## 🧪 Experience
- **Research Assistant**, IIITDM Jabalpur — *Present*
  - Worked on salient object detection.
- **M.Tech Thesis**, IIITDM Jabalpur — *Present*
  - Polyp segmentation for medical imaging.

## 🏆 Highlights
- GATE qualified (2024)

## 📬 Contact
- Email: susanta@iiitdmj.ac.in
- Location: Jabalpur, India

---

{% include base_path %}

<h2 id="publications">📚 Publications</h2>

- TAP-FuseNet: Task-Aware Progressive Fusion Network for Small Polyp Segmentation  
  Susanta Khamrui, Ayan Seal. IEEE Transactions on Instrumentation and Measurement (Under review)

<hr />

<h2 id="projects">🧩 Projects</h2>

{% if site.portfolio %}
  {% for post in site.portfolio limit: 5 %}
    {% include archive-single.html %}
  {% endfor %}
  <p><a href="{{ base_path }}/portfolio/">View all projects</a></p>
{% else %}
No projects yet.
{% endif %}

<hr />

<h2 id="teaching">🧑‍🏫 Teaching</h2>

- Data Structure in C — Fall 2024, IIITDM Jabalpur  
- Design and Analysis of Algorithms — Spring 2025, IIITDM Jabalpur  
- OOPs in Java — Fall 2025, IIITDM Jabalpur  
- Data Clustering — Spring 2026, IIITDM Jabalpur

<hr />

<h2 id="talks">🎤 Talks</h2>

{% if site.talks %}
  {% for post in site.talks reversed limit: 5 %}
    {% include archive-single-talk.html %}
  {% endfor %}
  <p><a href="{{ base_path }}/talks/">View all talks</a></p>
{% else %}
No talks yet.
{% endif %}

<hr />

<h2 id="blog">✍️ Blog Posts</h2>

{% if site.posts %}
  {% for post in site.posts limit: 5 %}
    {% include archive-single.html %}
  {% endfor %}
  <p><a href="{{ base_path }}/year-archive/">View all posts</a></p>
{% else %}
No blog posts yet.
{% endif %}
