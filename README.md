# Lakshay Saini Portfolio

A minimalist portfolio built with Astro, focusing on high performance and a clean monospace aesthetic. This site serves as a central hub for my research in machine learning robustness and various engineering projects.

## Project Goals

* Showcase research in model robustness, adversarial ML, and multimodal alignment.
* Maintain a brutalist, high-contrast design with zero dependencies on CSS frameworks.
* Optimize for static delivery and instant load times.

## Core Technologies

* Astro 6.1.8
* Vanilla CSS (Custom tokens and components)
* IBM Plex Mono
* GitHub Actions for automated CI/CD

## Development

### Setup

Clone the repository and install the project dependencies:

```bash
npm install
```

### Commands

* `npm run dev` - Starts a local development server at localhost:4321
* `npm run build` - Generates the static production site in the dist/ folder
* `npm run preview` - Previews the production build locally

## Deployment

The site is automatically built and deployed to GitHub Pages via the workflow defined in `.github/workflows/deploy.yml` on every push to the main branch.
