---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /index.html
header:
  image: /assets/img/home-header.jpg
tagline: > # this means to ignore newlines until "repository:"
    Your home  for modern Django tutorials with cutting-edge frameworks and libraries such as Angular 4+, React and Vue etc.

excerpt: >
    Your home for modern Django tutorials with cutting-edge frameworks and libraries such as Angular 4+, React and Vue etc.

repository:
  is_project_page: false
  show_downloads: false
  repository_url: ""
  zip_url: ""
  tar_url: ""
ref: home
lang: en
---

Your home  for modern Django tutorials with cutting-edge frameworks and libraries such as Angular 4+, React and Vue etc.


{% include facebook-page-summary.html %}


<h2>Latest Articles</h2>

{% include list-category-posts.html lang=page.lang category="articles" %}




