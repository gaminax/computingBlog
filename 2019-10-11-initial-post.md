---
layout: default
title: The Initial Post
date: 2019-10-11
---


[Home/](../index.html)
[ComputingBlog/](index.html)
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
