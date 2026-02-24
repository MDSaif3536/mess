# Job Notification App — Design System Foundation

This repo is a **design system foundation** for a premium B2C SaaS-style Job Notification App.  
It intentionally contains **no product features**—only tokens, layout structure, and core UI primitives.

## What’s included

- **Design tokens**: color, spacing, typography, radius, motion
- **Global layout skeleton**:
  - **Top Bar** → **Context Header** → **Primary Workspace (70%) + Secondary Panel (30%)** → **Proof Footer**
- **Core components**:
  - Buttons (primary / secondary / ghost)
  - Badges (neutral / accent / success / warning)
  - Inputs (text, select, textarea) with clear focus
  - Cards (subtle borders, no shadows)
  - Error / warning / empty / success callouts (clear, non-blaming language)
  - Proof footer checklist

## Files

- `index.html`: design system showcase page (static)
- `design-system.css`: tokens + component styles

## Design constraints (non-negotiable)

- **No gradients**
- **No glassmorphism**
- **No neon**
- **No heavy shadows**
- **Transitions**: 150–200ms, **ease-in-out**, no bounce/parallax
- **Max text width**: **720px** for reading comfort
- **Spacing scale**: **8 / 16 / 24 / 40 / 64** (used via CSS variables)
- **Same border radius everywhere**

## Color system

Base colors (only these are defined as primary tokens):

- **Background**: `#F7F6F3`
- **Primary text**: `#111111`
- **Accent**: `#8B0000`
- **Success**: muted green

**Warning (muted amber)** is **derived** by mixing the accent and success tokens so the UI stays restrained without adding extra base colors.

## Typography

- **Headings**: serif stack (`--font-serif`), confident sizing, generous spacing
- **Body**: clean sans stack (`--font-sans`) at **16px** with **~1.7** line-height
- **No decorative fonts**
- **No arbitrary type sizes** (type scale lives in `:root`)

## How to view

Open `index.html` in a browser. It’s a static page meant to act as the foundation and reference for future UI work.

