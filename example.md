---
title: An example paper
authors:
  - name: Wang Hailin
    affiliations:
      - Department of Geotechnical Engineering, Tongji University, Shanghai, China
      - Department of Civil and Environmental Engineering, The Hong Kong Polytechnic University, Hong Kong, China
    orcid: 0000-0001-5759-2455
    email: hailin.wang@connect.polyu.hk
keywords: Example, Paper, Markdown
exports:
  - format: tex
    template: elsarticle
    output: outputs/elsarticle-example.zip
  - format: pdf
    template: elsarticle
    output: outputs/elsarticle-example.pdf
  - format: tex
    template: ascelike-new
    output: outputs/ascelike-new-example.zip
  - format: pdf
    template: ascelike-new
    output: outputs/ascelike-new-example.pdf
---

+++ {"part": "abstract"}

This is an example abstract.

+++

# Introduction

This is an example introduction. See [myst](https://myst-tools.org/docs/mystjs) for more details on how to write papers
in markdown. Front matter options, parts are defined in the templates and an example is shown in the `example`
directory within the template.
