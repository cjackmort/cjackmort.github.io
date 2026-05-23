# Scott Mortensen Fine Arts — Website Project

## Overview
This is the source code for **scottmortensenfinearts.com**, a personal fine arts website hosted on GitHub Pages. The site is owned by Scott Mortensen and managed by Jack Mortensen (cjackmort@gmail.com).

The site is live at:
- https://scottmortensenfinearts.com
- https://www.scottmortensenfinearts.com
- https://cjackmort.github.io

## Current State
The site is a single-page HTML website. It currently shows a basic project portfolio layout that needs to be redesigned into a proper fine arts showcase website.

## File Structure
```
cjackmort.github.io/
├── index.html        # Main page — all HTML, CSS, and content lives here
├── CNAME             # Tells GitHub Pages to use scottmortensenfinearts.com
├── CLAUDE.md         # This file — context for Claude Code
└── images/           # Folder containing all artwork/project images
    ├── project1.jpg
    ├── project2.jpg
    └── project3.jpg
```

## How to Make Changes
- All website changes go in index.html — it contains the HTML structure and CSS styles inline.
- Images are stored in the images/ folder and referenced as images/filename.jpg.
- After editing, commit and push to the main branch. GitHub Pages will automatically redeploy within a minute or two.

## Deployment
- Hosted on GitHub Pages (free, automatic)
- Custom domain configured via the CNAME file (scottmortensenfinearts.com)
- DNS is managed on GoDaddy, pointing to GitHub's servers (185.199.108-111.153)

## Design Goals
When redesigning this site, keep in mind:
- This is a fine arts website — it should feel elegant, clean, and gallery-like
- The focus should be on showcasing Scott Mortensen's artwork
- Navigation, typography, and image presentation should feel professional
- Mobile-friendly layout is important

## How to Run Locally
Since this is plain HTML with no build step, just open index.html in a browser. No server or npm install needed.
