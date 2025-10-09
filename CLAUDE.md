# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Jekyll-based personal blog and portfolio website for Solito Reyes III (solrey3), hosted on GitHub Pages. The site focuses on music reviews, album recommendations, and personal content.

## Architecture & Structure

- **Jekyll Static Site**: Uses the Minima theme with custom dark mode styling
- **GitHub Pages Deployment**: Configured for automatic deployment via GitHub Pages
- **Content Structure**:
  - `_posts/`: Blog posts in Markdown format (music reviews, album lists)
  - `_config.yml`: Jekyll configuration with site metadata and social links
  - `assets/main.scss`: Custom dark theme CSS overrides
  - `about.md`: Personal profile and technical skills
  - `index.md`: Home page layout

## Development Commands

Since this is a Jekyll site, the typical development workflow uses:

```bash
# Install dependencies (requires Ruby and Bundler)
bundle install

# Start local development server
bundle exec jekyll serve

# Build the site
bundle exec jekyll build
```

**Note**: Bundle/Jekyll may not be installed in the current environment. If working with Jekyll commands, ensure Ruby and Bundler are available.

## Site Configuration

- **Theme**: Minima (~> 2.5.1) with custom dark mode styling
- **Plugins**: jekyll-feed for RSS
- **Deployment**: GitHub Pages (~> 232)
- **Analytics**: Google Analytics (UA-30383864-1)
- **Social Links**: Configured for Twitter, GitHub, Instagram, LinkedIn, YouTube

## Content Guidelines

- Posts follow Jekyll naming convention: `YYYY-MM-DD-title.md`
- Front matter includes layout, title, and date
- Content focuses on music reviews and personal recommendations
- Images stored in `/images/` directory

## Styling

Custom dark theme implemented in `assets/main.scss`:
- Dark background (#121212)
- Light text (#e0e0e0) 
- Blue accent links (#8ab4f8)
- Imports and extends Minima base theme