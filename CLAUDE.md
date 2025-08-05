# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based iOS app landing page for "Apateu", a student marketplace app. The site is designed to be deployed on GitHub Pages and automatically pulls app information from the App Store using the iOS app ID.

## Development Commands

### Local Development
```bash
# Install dependencies
bundle install

# Serve locally (if Jekyll is installed)
bundle exec jekyll serve

# Build the site
bundle exec jekyll build
```

### GitHub Pages Deployment
The site automatically deploys via GitHub Pages when changes are pushed to the master branch. No build commands needed for deployment.

## Architecture

### Jekyll Structure
- `_config.yml` - Main configuration file containing app details, theme settings, and feature definitions
- `_layouts/` - HTML templates (default.html is the main layout)
- `_includes/` - Reusable HTML components (header, footer, features, timeline, etc.)
- `_pages/` - Markdown pages for Privacy Policy, Terms of Use, Support, and About
- `_sass/` - SCSS stylesheets
- `assets/` - Static assets (images, videos, app icons)

### Key Configuration Areas

#### App Information (_config.yml:5-16)
- `ios_app_id: 6745530032` - Automatically populates app name, icon, and App Store link
- App description, pricing, and store links are configured here

#### Features Section (_config.yml:38-77)
Features are defined as YAML arrays with:
- `title` - Feature name
- `description` - Feature description 
- `fontawesome_icon_name` - FontAwesome icon identifier

#### Theme Customization (_config.yml:80-109)
All visual styling (colors, transparency, device color) is controlled via configuration variables.

### Content Management

#### Adding Screenshots/Videos
- Screenshots: Upload to `assets/screenshot/` (supports .png/.jpg)
- Videos: Upload to `assets/videos/` (.webm/.ogg for Chrome/Firefox, .mp4/.mov for Safari)
- Required resolutions: 828x1792, 1125x2436, or 1242x2688

#### Page Management
- Privacy Policy: Edit `_pages/privacypolicy.md`
- Terms of Use: Edit `_pages/termsOfuse.md` 
- Support: Edit `_pages/support.md`
- About: Edit `_pages/about.md`

Set `include_in_header: true/false` in page front matter to control navigation visibility.

## Design Reference

**Primary Design Template: Cohere.com (https://cohere.com/)**
- Modern AI company design aesthetic
- Clean header with icon/name on left, centered navigation tabs
- Professional typography and spacing
- Use this as the design reference for all UI/UX decisions

## Important Notes

- This is a Jekyll site, not a Node.js project (no package.json)
- Uses Ruby/Bundler for dependency management (Gemfile)
- App Store integration requires valid iOS app ID
- All customization happens through `_config.yml` - no direct HTML/CSS editing needed
- Site builds automatically on GitHub Pages; `_site/` directory is generated output