---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Click [here]() to download a PDF version of my **CV**.
<br>

# Education
- Ph.D in Statistics, Bielefeld University, 2023-today
- M.S. in Statistical Science, Bielefeld University, 2021-2023
- B.S in Economics, Bielefeld University, 2020-2021 (intermediate studies)
- B.A. in Business Administration, Bielefeld University of Applied Sciences, 2017-2020
<br>

# Work experience
- **Research associate** Statistics and Data Analysis Group, Bielefeld University, 2023-today
- **Research assistant** Statistics and Data Analysis Group, Bielefeld University, 2022-2023
- **Working student** Pricing Intelligence, CLAAS KGaA mbH, 2021-2022
- **Tutor** in Mathematics and Statistics, Bielefeld University of Applied Sciences, 2018-2020



<br>

# Publications
{% capture publications_content %}
  {% include_relative publications.md %}
{% endcapture %}

{% assign content_array = publications_content | split: "---" %}
{% assign content_without_frontmatter = content_array[2] %}

{{ content_without_frontmatter | markdownify }}
<br>

# Talks
{% capture talks_content %}
  {% include_relative talks.md %}
{% endcapture %}

{% assign content_array = talks_content | split: "---" %}
{% assign content_without_frontmatter = content_array[2] %}

{{ content_without_frontmatter | markdownify }}
<br>

# Teaching
{% capture teaching_content %}
  {% include_relative teaching.md %}
{% endcapture %}

{% assign content_array = teaching_content | split: "---" %}
{% assign content_without_frontmatter = content_array[2] %}

{{ content_without_frontmatter | markdownify }}
<br>

# Skills
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
  
Service and leadership
======
* Currently signed in to 43 different slack teams
