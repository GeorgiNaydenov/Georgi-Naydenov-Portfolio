# Portfolio Website

A standalone, single-file HTML portfolio that showcases AI artifacts, study guides, articles, posts, and public appearances.  
Hosted via GitHub Pages at:

- Live site: https://georginaydenov.github.io/Georgi-Naydenov-Portfolio/
- Repo:      https://github.com/georginaydenov/Georgi-Naydenov-Portfolio

## Overview

This portfolio is a fully self-contained, single-file HTML application built with React, Tailwind CSS, and Lucide Icons loaded via ES modules and CDNs. No build steps, bundlers, or tooling are required.

It delivers a modern, responsive interface with dark mode, interactive filtering, platform-based navigation, and real-time search across more than 50 AI resources and professional materials.
The site is deployed through **GitHub Pages** for fast, reliable, and maintenance-free hosting.

## Tech Stack

- **HTML5**:  Single-file architecture  
- **React 18.2.0**:  UI framework for component rendering (loaded via ES modules from esm.sh)  
- **Tailwind CSS** – Responsive utility-first styling (loaded via CDN)  
- **Lucide React 0.460.0** – Icon set for consistent visuals (loaded via ES modules)
- - **Vanilla JS** – Local state management and filtering logic; no external state libraries
- **No build system** – Everything runs natively in the browser

## Features

### Core Functionality

- **Category Filtering** — Switch between prototypes, articles, posts, and public appearances with refined logic for faster updates.  
- **Platform Filtering** — Includes Claude and NotebookLM filters with improved badge clarity and platform-specific styling.
- **Section Filter:** Switch between AI Prototypes, Study Guides, Proof of Concepts  
- **Subcategory Navigation** — Streamlined groups for TOGAF® EA, TOGAF® BA, CBAP, and technical resources with clearer hierarchy.  
- **Global Search** — Improved search responsiveness with real-time matching across all item metadata.  
- **Alphabetical Sorting** — More consistent ordering after filtering and search updates.  
- **Dark Mode** — Enhanced toggle behavior with visual refinements and smoother transitions.  
- **Responsive Design** — Rebalanced spacing, improved breakpoints, and better mobile card behavior.

### User Experience

- **Sticky Navigation** — Refined for better mobile and desktop handling.  
- **Collapsible Hero Section** — Smoother collapse animation and cleaner compact layout.  
- **Clickable Stats** — Updated to trigger more intuitive category transitions.  
- **Scroll-to-Top Button** — Improved show/hide timing and animation.  
- **Smooth Scrolling** — More consistent motion across the entire page.  
- **Empty State UI** — New wording and subtle icons for more precise feedback.

### Visual Design

- **Category-Based Card Styling**
  - Artifacts: Indigo / amber / rose tints (depending on section)
  - Articles: Emerald accents
  - Posts: LinkedIn-inspired blue accents
  - Appearances: Purple / media styling
- **Platform/Format Badges**
  - Claude / NotebookLM badges on AI prototypes
  - Google Docs / Slides / PDF hints for study guides and POCs
  - Video vs Article badges for public appearances
- **Interactive Cards**
  - Subtle transforms, shadows, and hover transitions
  - External-link icon hinting that every card opens in a new tab
- **Interactive Cards:**  
  - Hover transforms, shadows, and transitions  
  - External-link icons for clarity  
- **Animations:**  
  - Fade-ins, shimmering CTA buttons, and subtle motion effects
 
### Accessibility & Responsiveness

- **Responsive Grid:**  
  - 1 column (mobile), 2 (tablet), 3 (desktop)  
- **Hidden Scrollbars:** Horizontal topic navigation remains smooth  
- **Keyboard Navigation:** Focus styles and ARIA roles supported  
- **System Dark Mode:** Applied via Tailwind `dark:` variants  

### External Integration

- **Download CV:** Direct PDF link hosted externally  
- **LinkedIn Profile:** Accessible via hero and sticky header  
- **Secure External Links:** `target="_blank"` + `rel="noopener noreferrer"`  

## Content Organization

- **30+ AI Prototypes** – TOGAF/CBAP study tools across Claude & NotebookLM  
- **8 Articles** – AI strategy, transformation, technical topics  
- **8 LinkedIn Posts** – Ethics, hallucinations, industry insights  
- **3 Public Appearances** – Interviews and media features

## Usage

You can view the live site here:  
**https://georginaydenov.github.io/Georgi-Naydenov-Portfolio/**

Or run it locally:

```bash
# Clone the repository
git clone https://github.com/yourusername/portfolio.git

# Navigate to the directory
cd portfolio

# Open in browser (macOS)
open index.html
