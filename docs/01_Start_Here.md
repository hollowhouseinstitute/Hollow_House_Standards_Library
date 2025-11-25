# 01_Start_Here — Welcome to the Hollow House Institute

> Hollow House Institute  
> *Relational Psychology • Human–AI Interaction • Affective Computing*

This is your official onboarding guide.

## Table of Contents
- About  
- Structure  
- Diagrams  
- Navigation  
- Ecosystem Repos  
- License  
- Contact

## About the Institute
Hollow House Institute develops relational psychology datasets, emotional signatures, human–AI interaction logs, and research documentation.

## Repository Structure


## Ecosystem Diagram
```mermaid
flowchart TD
    A[Hollow House Institute] --> B[Relational Psychology Dataset]
    A --> C[Nervous System Codex]
    A --> D[Temple Codex License]

mindmap
  root((Hollow House Institute))
    Relational Psychology
    AI Interaction
    Affective Computing
    Ethics


graph TD
    A[Hollow House Institute] --> B[Research Docs]
    A --> C[Datasets]
    A --> D[Ethics & Licensing]


---

# ✅ **WHAT THIS DOES**

This single script will:

✔ Build full documentation  
✔ Generate all required `.md` files  
✔ Create assets folders  
✔ Write clean, SEO-optimized content  
✔ Add diagrams + mermaid  
✔ Stage & commit everything

---

# Want even more?

I can generate automatically:

✅ `CITATION.cff`  
✅ GitHub Pages site (`site/index.md`)  
✅ Professional logo PNG/SVG  
✅ Auto-populate your sidebar navigation  
✅ Auto-create dataset repos with the correct structure  

Just tell me:  
**“Generate citation”**, **“Generate GitHub Pages”**, **“Generate logos”**, or **“Generate dataset repos”**.


cat > docs/01_Start_Here.md << 'EOF'
# 01_Start_Here — Welcome to the Hollow House Institute

> Hollow House Institute  
> *Relational Psychology • Human–AI Interaction • Affective Computing*

This is your official onboarding guide.

## Table of Contents
- About  
- Structure  
- Diagrams  
- Navigation  
- Ecosystem Repos  
- License  
- Contact

## About the Institute
Hollow House Institute develops relational psychology datasets, emotional signatures, human–AI interaction logs, and research documentation.

## Repository Structure


## Ecosystem Diagram
```mermaid
flowchart TD
    A[Hollow House Institute] --> B[Relational Psychology Dataset]
    A --> C[Nervous System Codex]
    A --> D[Temple Codex License]

mindmap
  root((Hollow House Institute))
    Relational Psychology
    AI Interaction
    Affective Computing
    Ethics


graph TD
    A[Hollow House Institute] --> B[Research Docs]
    A --> C[Datasets]
    A --> D[Ethics & Licensing]


---

# ✅ **WHAT THIS DOES**

This single script will:

✔ Build full documentation  
✔ Generate all required `.md` files  
✔ Create assets folders  
✔ Write clean, SEO-optimized content  
✔ Add diagrams + mermaid  
✔ Stage & commit everything

---

# Want even more?

I can generate automatically:

✅ `CITATION.cff`  
✅ GitHub Pages site (`site/index.md`)  
✅ Professional logo PNG/SVG  
✅ Auto-populate your sidebar navigation  
✅ Auto-create dataset repos with the correct structure  

Just tell me:  
**“Generate citation”**, **“Generate GitHub Pages”**, **“Generate logos”**, or **“Generate dataset repos”**.



#!/usr/bin/env bash

echo "=== Setting up Hollow House Institute Hybrid Documentation System ==="

# Create folders
mkdir -p docs
mkdir -p docs/_layouts
mkdir -p docs/_includes
mkdir -p docs/sidebar
mkdir -p assets/logos

echo "Folders created."

# ---------------------------------------------------------
# Create GitHub Pages Config
# ---------------------------------------------------------

cat > docs/_config.yml << 'EOF'
title: Hollow House Institute
description: Relational psychology, human–AI interaction, affective computing.
theme: jekyll-theme-minimal
markdown: GFM

# Enable sidebar nav
include:
  - sidebar

nav:
  - Start Here: "01_Start_Here.md"
  - Mission: "mission.md"
  - Methodology: "methodology.md"
  - Dataset Overview: "dataset_overview.md"
  - Ethics & Privacy: "ethics_and_privacy.md"
  - Institute Structure: "institute_structure.md"
