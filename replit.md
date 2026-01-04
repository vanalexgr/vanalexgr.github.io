# Vascularized.gr - Academic CV Website

## Overview
This is a Hugo static site using the Hugo Blox Academic CV template. It's a professional portfolio website for Ευάγγελος Αλεξίου (Evangelos Alexiou), a vascular surgeon.

## Tech Stack
- **Static Site Generator**: Hugo (extended version)
- **Theme**: Hugo Blox (blox-tailwind module)
- **CSS**: Tailwind CSS v4
- **Package Manager**: pnpm
- **Language**: Go modules for Hugo dependencies

## Project Structure
- `config/_default/` - Hugo configuration files
- `content/` - Markdown content files (publications, blog, courses, etc.)
- `assets/` - Media files and icons
- `layouts/` - Custom Hugo templates and partials
- `static/` - Static assets served as-is

## Development
Run the dev server with:
```bash
hugo server --bind 0.0.0.0 --port 5000 --baseURL / --disableFastRender --appendPort=false
```

## Build for Production
```bash
hugo --minify
```
Output will be in the `public/` directory.

## Custom Overrides
- `layouts/partials/functions/get_icon.html` - **Fixed icon handler** that corrects a bug in the theme's SVG loading. Custom icons now work site-wide using `custom/icon-name` format.
- `layouts/partials/hbx/blocks/resume-skills/block.html` - Custom override for skills block with custom icon support

## Custom Icons
Custom SVG icons are stored in `assets/media/icons/custom/`. To use them in skills, set `icon_pack: custom` in the YAML frontmatter.

## Recent Changes
- 2026-01-04: Configured for Replit environment
  - Changed baseURL to `/` for development
  - Set up Hugo dev server workflow on port 5000
- 2026-01-04: Added custom icon support for skills section
  - Created custom resume-skills block override
  - Changed experience.md to use `resume-skills` block
  - Updated admin/_index.md to use `skills:` with `icon_pack: custom`
