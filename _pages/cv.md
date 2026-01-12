---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Click [here](../files/CV.pdf) for the PDF version of my CV.
<br>

# Education
- **PhD in Statistics**, Bielefeld University, 2023-today
  * **Research stay**, University of British Columbia, March-April 2025
- **MSc in Statistical Science**, Bielefeld University, 2021-2023
- **BSc in Economics** (intermediate studies), Bielefeld University, 2020-2021
- **BA in Business Administration**, Bielefeld University of Applied Sciences, 2017-2020
  * **Semester abroad**, Budapest Business School, 2019/2020

<br>

# Employment
- **Research associate** Statistics and Data Analysis Group, Bielefeld University, 2023-today
- **Student assistant** Statistics and Data Analysis Group, Bielefeld University, 2022-2023
- **Working student** Pricing Intelligence, CLAAS KGaA mbH, 2021-2022
- **Intern** Market Intelligence, CLAAS KGaA mbH, 2020
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

# Teaching
{% capture teaching_content %}
  {% include_relative teaching.md %}
{% endcapture %}

{% assign content_array = teaching_content | split: "---" %}
{% assign content_without_frontmatter = content_array[2] %}

{{ content_without_frontmatter | markdownify }}

<br>

# Grants and Awards
- **German public-private scholarship**, funding years 2019/2020 and 2022/2023
- **Teaching award of the Department of Business Administration and Economics** for delivering one of the courses with the best evaluations across the department (for the course "Präsenzübung Mathematik I & II", jointly with J. Dyck)
- **Mobility grant of the Bielefeld Graduate School in Theoretical Sciences (BGTS)** <br>
€4,000
- **Teaching award of the Department of Business Administration and Economics** for delivering one of the courses with the best evaluations across the department (for the course "Präsenzübung Mathematik II", jointly with K. Ammann)

<br>

# Community involvement
**Reviewer**
- [Journal of Computational and Graphical Statistics](https://www.tandfonline.com/toc/ucgs20/current)
- [Journal of the Royal Statistical Society Series A](https://rss.org.uk/news-publication/publications/journals/series-a/)
- [Journal of the Royal Statistical Society Series C](https://rss.org.uk/news-publication/publications/journals/series-c/)
- [Computational Statistics and Data Analysis](https://www.sciencedirect.com/journal/computational-statistics-and-data-analysis)
- [Methods in Ecology and Evolution](https://besjournals.onlinelibrary.wiley.com/journal/2041210x)
- [Movement Ecology](https://movementecologyjournal.biomedcentral.com)
- [TEST](https://link.springer.com/journal/11749)

<br>

# Other skills
- **Programming**: R (including Rcpp), C++, Python
- **Tools**: LaTeX, git, SQL
- **Languages**: German, English

<br>

# Volunteering
- **Member of the student council** (Data Science & Statistical Science), Bielefeld University, 2021-2023
- **Representing the interests of student assistants** (SHK-Rat), Bielefeld University, 2022
- **Voluntary service**, AWO nursery school Werther, 2016-2017

<br>

# Talks and Presentations
{% capture talks_content %}
  {% include_relative talks.md %}
{% endcapture %}

{% assign content_array = talks_content | split: "---" %}
{% assign content_without_frontmatter = content_array[2] %}

{{ content_without_frontmatter | markdownify }}
