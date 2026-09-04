# Nanoparticle-Assisted Solar Still Study Map

**Interactive research map and dataset for the global literature on nanoparticle-assisted solar still desalination.**

[Launch the interactive map](https://aryakia.github.io/solar-still-nanoparticle-map/index.html) · [Dataset DOI](https://doi.org/10.5281/zenodo.20109066)

**Project type:** Research infrastructure · Data visualization · Evidence mapping  
**Role:** Creator, researcher, data curator, and visualization developer  
**Status:** Public research tool · Version 1.0.0 · Released 2026

---

## Project overview

Research on nanoparticle-assisted solar stills is distributed across many publications, locations, still configurations, and nanoparticle applications. This project converts that literature into a geographic and searchable research resource.

The platform maps reviewed experimental studies by their reported study location and connects each location to information about nanoparticle application, solar still configuration, reported performance, and the underlying reference.

Rather than presenting the review only as a conventional table, the project provides an interactive interface for exploring **where research has been conducted, what technologies have been tested, and how the evidence is distributed geographically**.

## What I built

I designed and developed an interactive world map that integrates the literature dataset with geographic visualization, filtering, search, references, and downloadable research outputs.

### Key capabilities

- Interactive global map of reviewed experimental studies
- Study markers linked to reported experimental locations
- Search by country, location, nanoparticle, reference, and solar still type
- Filtering by nanoparticle application category, including:
  - Basin nanofluid
  - External-circuit nanofluid
  - Nano-coating
  - Nano-enhanced phase-change material (PCM)
- Direct reference links for individual studies
- Downloadable Excel research dataset
- Downloadable static SVG research map
- GitHub Pages deployment for open access

## Research design

The mapping approach prioritizes the **reported experimental location** of each study rather than the authors' institutional affiliations. Where a publication reports only the country and not a specific experimental location, country-level coordinates are used.

Reference records link to DOI pages when available and otherwise provide a route to locate the publication through scholarly search.

## Why this matters

Evidence reviews often describe technologies in tables but make the spatial structure of the literature difficult to see. Geographic evidence mapping can reveal concentrations and gaps in experimentation, differences in technology adoption across locations, and areas where additional research may be useful.

This project was developed as a research companion to work reviewing nanoparticle applications in solar still desalination and is designed to make the underlying evidence easier to inspect, reuse, and communicate.

## Repository contents

| File | Purpose |
| --- | --- |
| `index.html` | Interactive web application and map |
| `solar-still-nano-enhanced-data.xlsx` | Curated research dataset |
| `solar-still-nano-enhanced-map.svg` | Static publication-ready map |
| `CITATION.cff` | Machine-readable citation metadata |
| `README.md` | Project case study and documentation |

## Citation

If you use the dataset or interactive visualization, please cite:

> Kia, A. (2026). *Location Mapping Dataset and Interactive Visualization of Nanoparticle-Assisted Solar Still Studies* (Version 1.0.0). https://doi.org/10.5281/zenodo.20109066

Citation metadata is also available in [`CITATION.cff`](./CITATION.cff).

## Author

**Arya Kia**  
Researcher in energy systems, system dynamics, and applied research visualization.

---

### Live research tool

**[Open the interactive map →](https://aryakia.github.io/solar-still-nanoparticle-map/index.html)**
