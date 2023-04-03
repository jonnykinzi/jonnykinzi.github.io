---
layout: page
permalink: /cv
title: cv
nav: true
# redirect_to: /assets/pdf/jkinzi-cv.pdf
---
{% assign rootpath = '/' | relative_url %}
In case the inline PDF does not appear, you may download the PDF file [here]({{ site.cv.pdf | prepend: pathprefix | relative_url }}).
{% pdf site.cv.pdf | page.title | rootpath %}