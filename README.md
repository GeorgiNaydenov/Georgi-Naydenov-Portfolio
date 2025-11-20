# Portfolio Website

A standalone, single-file HTML portfolio showcasing AI prototypes, articles, posts, and public appearances.

## Overview

This is a self-contained portfolio website built as a single HTML file with no build process required. It features a modern, responsive design with dark mode support and showcases professional work in AI, business analysis, and enterprise architecture.

## Tech Stack

- **HTML5** – Single-file architecture  
- **React 18.2.0** – UI framework (loaded via ES modules from esm.sh)  
- **Tailwind CSS** – Utility-first styling (loaded via CDN)  
- **Lucide React 0.460.0** – Icon library (loaded via ES modules)

## Features

### Core Functionality

- **Category Filtering** – Prototypes, Articles, Posts, Public Appearances  
- **Platform Filtering** – Claude Artifacts, NotebookLM  
- **Subcategory Navigation** – TOGAF EA, TOGAF BA, CBAP Prep, Technical  
- **Global Search** – Real-time search across visible content  
- **Alphabetical Sorting** – Auto-sorting of filtered items  
- **Dark Mode** – System detection + manual toggle  
- **Responsive Design** – Mobile-first with adaptive layout

### User Experience

- **Sticky Navigation**  
- **Collapsible Hero Section**  
- **Clickable Stats**  
- **Scroll-to-Top Button**  
- **Smooth Scrolling**  
- **Empty State UI**

### Visual Design

- **Color-coded Categories** – Indigo, Emerald, Blue, Purple  
- **Badge System** – Video / Article / Platform indicators  
- **Interactive Cards** – Shadows, transforms, transitions  
- **Custom Animations** – Fade-in-down, bounce, pulse, rotate, scale  
- **Hidden Scrollbars**  
- **Certification Badges** – CBAP®, PMP®, TOGAF® EA Practitioner

### External Integration

- **Download CV** – Direct PDF link  
- **LinkedIn Connect**  
- **Secure External Links** – `noopener`, `noreferrer`

## Content Organization

- **30+ AI Prototypes** – TOGAF/CBAP study tools across Claude & NotebookLM  
- **8 Articles** – AI strategy, transformation, technical topics  
- **8 LinkedIn Posts** – Ethics, hallucinations, industry insights  
- **3 Public Appearances** – Interviews and media features

## Usage

Open `index.html` in any modern browser. No build process or server needed.

```bash
# Clone the repository
git clone https://github.com/yourusername/portfolio.git

# Navigate to the directory
cd portfolio

# Open in browser (macOS)
open index.html
