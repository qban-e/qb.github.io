# Site settings
title: 程相洪博客
email: 程相洪@126.com
description: > # this means to ignore newlines until "baseurl:"
 qb 程的博客
baseurl: "" # the subpath of your site, e.g. /blog/
url: qb.github.io/ # the base hostname & protocol for your site
rss_url: /pages/feed.xml
author: Su Yan

# Sidebar filter
# Choose 'tag' or 'category' as filter in sidebar.
filter: 'category'
recent_num: 20


# avatar and Favicon
avatar: http://7u2ho6.com1.z0.glb.clouddn.com/site-avatar.png
favicon: http://7u2ho6.com1.z0.glb.clouddn.com/site-favicon.ico

# disqus config
disqus:
  shortname: suyan-zh

# Build settings
permalink: /:year/:month/:day/:title.html
markdown: kramdown
highlighter: rouge
mathjax: disabled
sass:
  style: compressed

# Jekyll Plugin
# https://help.github.com/articles/adding-jekyll-plugins-to-a-github-pages-site/
gems:
  - jekyll-sitemap
  - jekyll-seo-tag
  - jekyll-feed
