# Welcome to the Markdown Repository for the ISWC Chair's Guide

**Author: Terry R. Payne (University of Liverpool)**

This is the home of the [ISWC Chairs Guide](https://iswc-guide.github.io/chair-guide/) to organising the International Semantic Web Conference, organised by the [Semantic Web Science Association](https://swsa.semanticweb.org).  The guide is written using markdown, hosted in Github, and utilises the [Millidocs](https://github.com/alexander-heimbuch/millidocs) Jekyll theme, written by Alexander Heimbuch (under the MIT License).  The configuration for Jekyll is given in the [_config.yml](_config.yml) file.

## Status

- Draft (in progress)
- Created: 8th Jan 2026
- Latest Update: 2nd Jun 2026

## Page Structure

The site structure consists of pages, each starting with the following [Jekyll front matter](https://jekyllrb.com/docs/front-matter/):

```
---
layout: page
title: My title
navigation: 2
---
```

where 

- *title*: this variable identifies the text that appears in the navigation bar (to the left of the page)
- *navigation*: this variable identifies the index of the page (i.e. order in which it appears in the navigation bar), where the home page (*index.md*) has the value 1
- *layout*: the theme only supports two layouts - `default` and `page` (the definition of both can be found in [the original millidocs theme definition](https://github.com/alexander-heimbuch/millidocs/tree/master/_layouts).  For the purposes of the guide, only `page` is used.
