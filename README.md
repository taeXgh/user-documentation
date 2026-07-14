# Squarespace User Documentation Portal

## Overview
This repository hosts a production-ready, full-featured user documentation portal built explicitly for guiding team members or clients through operating Squarespace dashboard instances, managing website navigation, and conducting standard application reviews. 

The site is built leveraging **Next.js**, **React**, and **Nextra** (a powerful, Markdown-focused documentation framework), supporting fully typed custom modules (`.mdx`) and interactive interface features.

---

## Technical Stack & Frameworks
* **Core Framework**: [Next.js](https://nextjs.org/) (v14+)
* **Documentation Theme**: [Nextra Theme Docs](https://nextra.site/) (v2.x)
* **Styling & CSS**: CSS Modules (`.module.css`) & CSS Variables
* **Programming Language**: TypeScript (`.ts`, `.tsx`)
* **Package Manager**: `pnpm` / `npm`

---

## Project Structure
```text
├── components/
│   ├── counters.module.css          # Scoped modular styles for template features
│   └── counters.tsx                 # Interactive React placeholder counters
├── pages/
│   ├── _meta.json                   # Root navigation sorting structure
│   ├── index.mdx                    # Site Landing and introduction
│   ├── Module1/                     # Squarespace Dashboards documentation
│   │   ├── 1accountdash.mdx         # Account Management guidelines
│   │   ├── 2websitedash.mdx         # Custom Website Overview panels
│   │   ├── 3settingsmenu.mdx        # Core Settings adjustment steps
│   │   ├── 4squarespacehelp.mdx     # Support documentation links
│   │   └── _meta.json               # Module 1 Sidebar indexing config
│   ├── Module2/                     # Site Navigation layout
│   │   ├── WebsiteNavigation.mdx    # Menu structure documentation
│   │   └── _meta.json               # Module 2 indexing config
│   └── Module3/                     # Applications processing module
│       ├── ApplicationReview.mdx    # Evaluation portal documentation
│       └── _meta.json               # Module 3 indexing config
├── theme.config.tsx                 # Nextra Layout configuration (Header, Footer, Logo)
├── next.config.js                   # Next.js bundler routing overrides
└── tsconfig.json                    # Structural TypeScript rules configuration
