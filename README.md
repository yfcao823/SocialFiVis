# SocialFiVis

> An academic project page for **SocialFiVis: A Visual Analytics Sandbox for LLM-Grounded Multi-Agent Simulation in Social Finance**.

SocialFiVis is an IAD-embedded visual analytics sandbox for exploring counterfactual governance in SocialFi communities. The project models the coupling between social capital and financial health, combines LLM-derived personas with a mechanism-guided Perception–Reasoning–Action (PRA) runtime, and helps users trace system-level outcomes back to individual agent rationales.


## Project page

- Paper: [`SocialFiVis_VIS26.pdf`](./SocialFiVis_VIS26.pdf)
- Source repository: [github.com/sqsssq/SocialFiVis](https://github.com/sqsssq/SocialFiVis)
- Local demo: run the project locally using the instructions below

## Highlights

- Counterfactual policy exploration grounded in the Institutional Analysis and Development (IAD) framework
- Dual-track digital commons modeling for social capital and financial health
- Heterogeneous, empirically grounded agent personas
- Mechanism-guided PRA simulation for context-aware agent behavior
- Hierarchical visual analytics connecting macro outcomes, persona cohorts, and micro-level reasoning
- Responsive academic project page with paper, demo video, citation, and custom favicon

## Run locally

The project is a static HTML page and does not require a build step or package installation.

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser. Run the command from the repository root.

## Project structure

```text
.
├── index.html                 # Academic project page
├── SocialFiVis_VIS26.pdf      # Paper PDF
├── teaser.jpg                 # Teaser image
├── walkthrough_mr.mp4         # Demo video
├── static/
│   ├── css/                   # Bulma, page styles, and component styles
│   ├── images/                # Favicon and visual assets
│   ├── js/                    # Carousel, slider, and page scripts
│   ├── pdfs/                  # Embedded PDF assets
│   └── videos/                # Template video assets
└── LICENSE
```

## Editing the page

Most content is defined directly in [`index.html`](./index.html). Update the following areas when preparing a new version:

- paper title, authors, affiliations, and publication information
- abstract and project description
- paper, supplementary, arXiv, code, and demo links
- teaser image and demo video paths
- BibTeX citation
- SEO metadata and social preview metadata in the `<head>`

Page-wide styling is in [`static/css/index.css`](./static/css/index.css). The page uses Google Fonts for Lato and EB Garamond, with local system fallbacks when the fonts are unavailable.

## Citation

```bibtex
@article{cao2026socialfivis,
  title   = {SocialFiVis: A Visual Analytics Sandbox for LLM-Grounded Multi-Agent Simulation in Social Finance},
  author  = {Cao, Yi-Fan and Shi, Qing and Wang, Liangwei and Lo, Leo Yu-Ho and Chen, Lin and Han, Yuzi and Wang, Yang and Chen, Kani},
  journal = {IEEE Transactions on Visualization and Computer Graphics},
  year    = {2026}
}
```

## Acknowledgments

The project page is based on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), which was adapted from the [Nerfies](https://nerfies.github.io/) project page.

## License

The project page is distributed under the [MIT License](./LICENSE). The adapted website template remains subject to the attribution and share-alike terms described in the page footer.
