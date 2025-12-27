---
permalink: /
title: "Iqbal Putra"
show_head_title: false
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am a researcher working at the intersection of AI, geospatial intelligence, environmental systems, and sustainability. 

I hold a Bachelor of Science in Geography (Geographical Information Science) from the [University of Indonesia](https://geografi.ui.ac.id/en/) and a Bachelor of Science in Computer Science from [Universitas Siber Asia](https://unsia.ac.id/), followed by a Master of Science in Geospatial Intelligence from  [The University of Queensland](https://environment.uq.edu.au/), Australia.

During my undergraduate studies, I received full-funded scholarship, conducted research at the Applied Geography Research Center, and was awarded the PITTA-UI research grant under the supervision of [Prof. Supriatna](https://ppsml.sil.ui.ac.id/team-members/prof-dr-drs-supriatna-m-t-2/). Moreover, I completed my master degree with fully-funded Australia Awards Scholarship (AAS), supervised by [Prof. Stuart Phinn](https://environment.uq.edu.au/profile/13550/stuart-phinn). In parallel, I worked as a Research Associate at UQ Natural Gas lab under the supervision of [Prof. Andrew Garnett](https://gas-energy.centre.uq.edu.au/about/our-people/andrewgarnett).



Research Interest
======

My research interests lie in computational sustainability, at the intersection of artificial intelligence and environmental, biodiversity, climate, and urban systems. In particular, I am interested in:
  - GeoAI and remote sensing for environmental and biodiversity monitoring
  - Spatiotemporal modeling and forecasting using deep learning
  - Multi-agent and agentic AI systems for urban and environmental analytics
  - Foundation models and representation learning for Earth observation data
  - AI for nature and social good

My long-term goal is to develop trustworthy and scalable AI methods that support sustainable environmental decision-making.





Recent News
======
1. October 2025 - Poster Presentation at NeurIPS 2025 Multi-modal Foundation Models and Large Language Models for Life Sciences Workshop
2. September 2025 - Poster Presentation at ICCV 2025 Computer Vision for Ecology (CV4E) Workshop
3. June 2025 - Poster Presentation at ICLR 2025 Climate Change AI (CCAI) Workshop



Selected Publications
====== 
<section id="publications"></section>
{% for pub in site.publications %}
### {{ pub.title }}
- *{{ pub.venue }}*, {{ pub.date | date: "%Y" }}
{% endfor %}



Talks
====== 
<section id="talks"></section>
{% for pub in site.talks %}
### {{ pub.title }}
- *{{ pub.venue }}*, {{ pub.date | date: "%Y" }}
{% endfor %}




Teaching
====== 
<section id="teaching"></section>
{% for pub in site.teaching %}
### {{ pub.title }}
- *{{ pub.venue }}*, {{ pub.date | date: "%Y" }}
{% endfor %}