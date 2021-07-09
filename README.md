<a href="https://ibb.co/QrPc0n8"><img src="https://i.ibb.co/r4xt9Mb/near-logo.png" alt="near-logo" border="0" /></a>

# NEAR Ecosystem

This repository is the data source for the NEAR Ecosystem page, located at [near.org/ecosystem](https://near.org/ecosystem).

# Contributing Guidelines

All integrations in the NEAR Ecosystem are composed of two files: a Markdown file with headers, and an .svg or .png image. To add a new project to the ecosystem page, create both a new Markdown file in the `projects` or `guilds` directory and add a new .svg or .png image in the `img` directory.

### Markdown Headers

```
---
slug: "reffinance"
date: "2020-04-03"
title: "Ref Finance"
logline: "Ref Finance is a multi-purpose Decentralized Finance (DeFi) platform built on NEAR Protocol."
website: "https://ref.finance/"
app: "https://app.ref.finance/"
twitter: "https://twitter.com/finance_ref"
telegram: "https://t.me/ref_finance"
discord: "https://discord.gg/KKjQwCRvbV"
token: 
dao:
logo: /img/reffinancelogo.png
integration: project
category: defi, app
status: live
updates: 
contract: "https://github.com/ref-finance/ref-contracts"
---
```

Example Markdown headers are above (only input what is applicatble to the integration you are adding). Below are guidelines for each field:

- `slug`: The page URL that follows after near.org/ecosystem/
- `date`: The date of project addition
- `title`: The title of the project
- `logline`: The one line summary of the project and its integration to NEAR
- `website`: A URL to direct users to the page
- `app`: A URL directly to the app
- `token`: 
- `dao`:
- `logo`: A relative path to the corresponding SVG/PNG image
- `integration`: How it ties into the NEAR Ecosystem (see below)
- `category`: A comma separated list of categories describing the project
- `status`: The status of the integration: `live`, `building`, `closed`
- `updates`: URL to recent updates
- `contract`: URL to contract

### Categories

Available classifications for integrations:

```
project
guild
dao
company
fund
accelerator
```


Available classifications for project categories:

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

All .svg/.png files must be 100x100px. Do not embed any excessive raster image files: svg filesizes over 500kb will be rejected.
