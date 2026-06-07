# SCW18 Squid Workshop

Public repository for the SPRFMO SC Third Squid Workshop (SCW18): Stock Assessment and Simulated Assessment of Jumbo Flying Squid.

The rendered website is published at:

https://sprfmo.github.io/scw18-squid3-workshop/

## Repository structure

```text
scw18-squid3-workshop/
├── doc/      # Quarto source files
└── docs/     # Rendered website files for GitHub Pages
```

The Quarto project is located in `doc/` and renders to `docs/`.

## Render the website

From the repository root:

```bash
quarto render doc
```

To preview locally:

```bash
quarto preview doc
```

## Data and assessment files

This public repository contains workshop documents and public-facing outputs only.

Assessment data, model inputs, scripts, diagnostics, intermediate results and confidential working files are maintained separately in the private repository:

```text
sprfmo-jumbo-squid-assessment
```

Only agreed public outputs should be transferred from the private assessment repository to this public repository.
