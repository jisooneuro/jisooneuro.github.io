---
layout: archive
title: "About"
permalink: /
author_profile: true
---

I am a PhD candidate in Neuroscience at the University of Cambridge, working in the Selective Vision Lab under the supervision of Jasper Poort.

My research focuses on understanding how the brain processes visual information and transforms sensory signals into behavior. In particular, I study the functional roles of two major visual pathways, the primary visual cortex (V1) and the superior colliculus (SC), using electrophysiology and optogenetic manipulation in freely moving mice.

My long-term goal is to develop computational models of visual circuits that bridge neural activity and behavior. Using electrophysiological recordings from V1 and SC, I aim to build computational neural circuit models that capture their functional properties.

---

# Research Interests

- Blindsight  
- Visual neuroscience  
- Superior colliculus and Visual cortex  
- Computational Neuroscience  
- NeuroAI  

---

# Links

- [CV](/files/CV_jisooKim.pdf)
- [Google Scholar](https://scholar.google.com/citations?user=lSgjJyQAAAAJ&hl=en&oi=sra)

---

# Selected Publications

{% include base_path %}

{% for post in site.publications reversed %}
{% if post.category == "selected" %}

<div style="display:flex; align-items:flex-start; gap:25px; margin-bottom:40px;">

<div style="flex:0 0 320px;">
{{ post.content }}
</div>

<div style="flex:1;">

<p style="margin-top:0;">
<a href="{{ post.paperurl }}" style="font-weight:600; font-size:1.1em;">
{{ post.title }}
</a>
</p>

<p>
{{ post.citation | markdownify }}
</p>

</div>

</div>

{% endif %}
{% endfor %}

---

# All Publications

{% for post in site.publications reversed %}

<div style="margin-bottom:18px;">

<a href="{{ post.paperurl }}" style="font-weight:600;">
{{ post.title }}
</a>

<br>

{{ post.citation | markdownify }}

</div>

{% endfor %}

---

# CV

## Education

**PhD in Neuroscience**  
University of Cambridge, UK  
Oct 2021 – Present

**MSc in Brain and Cognitive Engineering**  
Korea University, Korea  
Sep 2018 – Aug 2020

**BSc in Bio-system Medical Science**  
Korea University, Korea  
Mar 2014 – Aug 2018

Exchange Student  
University of Copenhagen, Denmark  
Dec 2016 – Jul 2017

---

## Work Experience

**Maaind – R&D Intern**  
Neuro-adaptive AI startup  
Jun 2024 – Aug 2024  

- Decoded emotion from human EEG using unsupervised and supervised learning

<p align="center">
<img src="/images/neuroai.png" width="450">
</p>

**Korea Institute of Science and Technology (KIST)**  
Graduate Researcher  
Dec 2017 – Aug 2020

---

## Research Experience

### University of Cambridge — PhD Student  
Oct 2021 – Present

**Behavioral Training: Visual Detection Task in Freely Moving Mice**

- Developed a closed-loop system with DeepLabCut-live for controlling visual stimulus presentation.

**Electrophysiology: Primary Visual Cortex (V1) and Superior Colliculus (SC)**

- Performed simultaneous single-unit recordings in V1 and SC in freely moving mice.
- Classified cell types (putative PV, pyramidal neurons) using optogenetic tagging.

**Optogenetics: Modulation of V1 and SC During Visual Detection**

- Applied optogenetic inhibition to V1 and SC to assess causal roles in visual detection.

---

### Korea Institute of Science and Technology (KIST) — Graduate Researcher  
Dec 2017 – Aug 2020

**Effect of group condition on amygdala brain oscillations under robot-induced threat**

- Designed a Robot-Induced Escape paradigm and discovered a new behavioral phenomenon.

**Wireless neural recording system development**

- Validated the wireless recording system using hippocampal theta oscillations.

---

## Teaching Experience

**University of Cambridge — Demonstrator**

IB Natural Sciences Tripos (2nd Year)  
*Neurobiology: Function of the Eye*

Nov–Dec 2024  
Nov–Dec 2025

---

## Funding & Awards

**Wolfson College PDN Studentship**  
University of Cambridge  
Fully funded PhD (£25,000/year)

**School of Biological Sciences Doctoral Training Program Award**  
Overseas student fee reduction (£23,500/year)

**Best Oral Presentation — 2nd Prize**  
KIST Brain Science Institute Symposium

---

## Skills

### Computational

- MATLAB (6+ years)  
- Python (2+ years)

Analysis methods:

- Signal processing  
- LFP and spike analysis  
- Power spectrogram  
- Spike sorting (Kilosort)

Machine learning:

- PyTorch  
- CNN  
- DeepLabCut  

Software:

- Photoshop  
- Illustrator  
- Word  
- Excel  
- PowerPoint  

---

### Biological

- Stereotaxic rodent surgeries  
- Viral injection  
- Optogenetic stimulation  
- Perfusion  

Behavioral assays:

- Fear conditioning  
- Tube test  
- Robot-Induced Escape paradigm  
- Visual detection tasks  

- 3D printing

---

## Leadership & Volunteering

**Committee Member — PDN Symposium**  
University of Cambridge  
Dec 2021 – Apr 2022

- Organized scientific and social programs for the symposium.

**Vice President — Neuroscience Society (New-Learn)**  
Korea University  
Mar 2015 – Dec 2016

- Led a human psychology research project and presented findings at a conference.
