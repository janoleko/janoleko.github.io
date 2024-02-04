---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Click [here]() to download a PDF version of my **CV**.

{% include base_path %}
# Education
* B.A. in Business Administration, Bielefeld University of Applied Sciences, 2017-2020
* B.S in Economics, Bielefeld University, 2020-2021 (intermediate studies)
* M.S. in Statistical Science, Bielefeld University, 2021-2023
* Ph.D in Statistics, Bielefeld University, 2023-today
<br>

# Work experience
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
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
