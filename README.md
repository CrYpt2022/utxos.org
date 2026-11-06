# utxos.org

A Hugo-powered informational website for BIP-119 / OP_CHECKTEMPLATEVERIFY (CTV), focused on Bitcoin scripting, covenant design, vaults, scaling, and related ecosystem discussions.

This repository contains the public site content for `utxos.org`, including landing pages, essays, analyses, use cases, resource listings, and workshop materials for the broader Bitcoin research and development community.

## Overview

`utxos.org` presents information around the Bitcoin proposal to enable more expressive, safer smart contracts and transaction patterns using OP_CHECKTEMPLATEVERIFY. The site is structured around:

- BIP-119 materials and related references
- Design alternatives and deployment discussions
- Applications and ecosystem impact
- Resource indexes and workshop notes
- Educational material for developers and researchers

## Site structure

```text
.
├── .github/                  # GitHub-related configuration
├── archetypes/              # Hugo archetype templates
├── content/                 # Main site content, pages, and markdown articles
│   ├── analysis/            # Deep-dive analysis content
│   ├── uses/                # Application and use-case pages
│   ├── _index.md            # Homepage content
│   ├── alternatives.md
│   ├── deployment.md
│   ├── resources.md
│   ├── signals.md
│   ├── sponsors.md
│   ├── workshops.md
│   └── ...
├── data/                    # Hugo data files
├── layouts/                 # Custom page templates and layouts
├── static/                  # Static assets, images, and uploaded files
│   └── sapio/               # Git submodule for Sapio resources
├── themes/                  # Hugo theme files
├── .gitignore               # Git ignores
├── .gitmodules              # Git submodules
├── config.toml              # Hugo site configuration
└── README.md                # Project documentation
