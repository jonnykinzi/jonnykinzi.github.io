---
layout: page
permalink: /cv/
title: cv
nav: true
# redirect_to: /assets/pdf/jkinzi-cv.pdf
---
{% assign rootpath = '/' | relative_url %}
In case the inline PDF does not appear, you may download the PDF file [here]({{ jkinzi-cv.pdf | prepend: pathprefix | /assets/pdf/ }}).
{% pdf jkinzi-cv.pdf | page.title | rootpath %}