---
layout: post
title: The Initial Post
date: 2019-10-11
---

[Home/](/index.html)
[ComputingBlog/]( {{ site.baseurl }}/index.html)
2019-10-11 Initial Post

The issue is figuring out how to organize this website.


## Project Organization
The computingBlog project is layered on top of the root Github Pages project, gaminax.github.io.

## Generating AsciiDoc Content
The Github Jekyll website generator is limited to Github Flavored Markdown.
One can use another markdown format, but one then has to generate the HTML by some other means.

The AsciiDoctor/Jekyll-AsciiDoc-Quick-Start project shows how to generate asciidoc content via another website, https://travis-ci.org/, and have that website post the html to Github.

If one generates the html oneself, it can be done a file at a time. or a project at a time.
Generating the html a file at a time has some advantages: one can use multiple source formats, and simply add the generated html file to the source. Large web pages with multiple subheadings are quite usable.

## Fonts
The necessary fonts need to be requested in the stylesheets via Google Fonts, or stored on github.

## Addendum 2019 11 17

### Simple ways to organize website
-  Plugins can be loaded from \_config.yml, without a version number. There is no need for Ruby Gems. So no need for Gemfile or messing with bundler. The Jekyll website ought to emphasize this more.
- Deriving a dark theme from minima: One can override the minima CSS coloring by adding CSS coloring to assets/css/style.scss. I initially tried copying and editing all the CSS files, but overriding is simpler. A dark theme derived from minima would be good; one would not need to add to style.scss.
- Build /texts and /computing offline to docs when using asciidoc plugin.
- Use IBM Plex fonts from fonts.google.com. These are a good and unified font set.

