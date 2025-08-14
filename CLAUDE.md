# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static blog website built with **Hexo 3.8.0** static site generator. The repository contains pre-generated HTML files for a personal blog focused on technical content including programming tutorials, computer science concepts, and technology insights.

## Architecture

### Generated Site Structure
- **Content**: Blog posts organized by year (2016-2020) in nested directories by date
- **Categories**: Technical topics including Angular, Node.js, blockchain, machine learning, computer science subjects
- **Assets**: 
  - `/css/` - Custom styles and syntax highlighting themes
  - `/js/` - Client-side JavaScript for site functionality
  - `/images/` - Blog post images and diagrams
- **Static files**: Generated HTML pages, sitemap, robots.txt, content.json

### Technology Stack
- **Static Site Generator**: Hexo 3.8.0
- **Theme**: Minos theme (based on HTML meta tags)
- **Styling**: Bulma CSS framework with custom styles
- **Typography**: Uses Korean fonts (Noto Sans KR, Nanum Gothic Coding)
- **Icons**: FontAwesome 5.0.8
- **Galleries**: LightGallery and JustifiedGallery for image displays

## Development Workflow

### Content Structure
This is a **static site repository** containing only generated output files. The source files (Markdown posts, theme files, Hexo configuration) are not present in this repository.

### Site Deployment
- The repository serves as the deployment target for GitHub Pages
- All files are pre-generated HTML/CSS/JS ready for static hosting
- No build process is required in this repository

### Content Management
- New blog posts would be added through the source Hexo project (not this repository)
- This repository only receives updates when the source site is rebuilt and deployed

## Important Notes

### Repository Purpose
- This is a **static hosting repository** for a Hexo blog
- Contains only generated/compiled output files
- No package.json, build scripts, or source files are present
- Direct editing of HTML files in this repository is not recommended

### Content Language
- Primary content is in Korean with some English technical posts
- Covers wide range of technical topics from web development to computer science theory

### Historical Context
- Active blogging period: 2016-2020
- Last significant update: 2020-01-05
- Contains educational content on programming languages, frameworks, and CS concepts