<a href="https://ibb.co/QrPc0n8"><img src="https://i.ibb.co/r4xt9Mb/near-logo.png" alt="near-logo" border="0" /></a>

# NEAR Ecosystem

This repository is the data source for the NEAR Ecosystem page, located at [near.org/ecosystem](https://near.org/ecosystem).

# Contributing Guidelines

A project is composed of two files: a Markdown file with headers, and an .svg image. To add a new project to the ecosystem page, create both a new Markdown file in the `projects` directory and add a new .svg image in the `img` directory.

### Markdown Headers

```
---
slug: "anchor"
date: "2020-04-03"
title: "Anchor"
logline: "Anchor is a savings protocol that aims to produce a simple and convenient savings product with broad appeal to everyday users."
cta: "https://anchorprotocol.com/"
logo: /img/anchor.svg
category: defi, tools
status: building
oa: "1000"
maa: "500"
---
```

Example Markdown headers are above. Below are guidelines for each field:

- `slug`: The page URL that follows after near.org/ecosystem/
- `date`: The date of project addition
- `title`: The title of the project
- `logline`: The one line summary of the project and its integration to NEAR
- `cta`: A URL to direct users to the page
- `logo`: A relative path to the corresponding SVG image
- `category`: A comma separated list of categories describing the project
- `status`: The status of the project: `live`, `building`, or `closed`
- `oa`: Onboarded accounts:
- `maa`: Monthly active accounts:

### Categories

Available classifications for projects:

```
amm
app
defi
dex
exchange
explorer
infra
oracle
spl
stablecoin
tools
wallet
metaplex
```

### Image Guidelines

All .svg files must be 100x100px. Do not embed any excessive raster image files: svg filesizes over 500kb will be rejected.
