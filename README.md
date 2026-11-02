# Evan Liu - Physical AI & Robotics

[English](README.md) | [简体中文](README.zh-CN.md)

This repository contains the personal portfolio website of Evan Liu, a full-stack engineer working across physical AI, robotics, hardware, embedded systems, and software.

## Overview

The site is a lightweight static website with the following sections:

- **Hero** — Introduces the site's focus on physical AI and robotics.
- **Projects** — Highlights work involving custom hardware, embedded systems, and intelligent physical systems.
- **About** — Describes Evan's engineering background and current interests.
- **Archive** — Preserves earlier work, including the history of 320kbps.com.
- **Now** — Summarizes current areas of exploration.

## Project Structure

```text
.
├── index.html   # Page structure and content
├── style.css    # Layout, typography, responsive behavior, and visual styles
└── README.md    # Project documentation
```

## Run Locally

Because this is a static website, no build step or package installation is required.

### Option 1: Open the file directly

Open `index.html` in a browser.

### Option 2: Use a local HTTP server

From the project directory, run:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000> in a browser.

## Customization

- Update page content and navigation links in `index.html`.
- Adjust layout, colors, typography, and responsive rules in `style.css`.
- Replace placeholder project links (`href="#"`) with project URLs when they are available.

## Deployment

This is a static website that requires no dependency installation or build command, and can be deployed to any static hosting provider. Both GitHub Pages and Cloudflare Pages can publish the repository's root directory and serve `index.html` as the entry page.

### GitHub Pages

Set the repository's root directory as the site source. No additional build configuration is required.

### Cloudflare Pages

Create a Pages project in the Cloudflare dashboard and connect this Git repository. Use the following build settings:

| Setting | Value |
| --- | --- |
| Framework preset | None |
| Root directory | Repository root (default) |
| Build command | Leave blank |
| Build output directory | `.` |

No environment variables are required. After saving the settings, Cloudflare Pages will publish the repository root. Pushes to the production branch will trigger deployments automatically, and Pull Requests can generate preview deployments.

To use a custom domain, add it under **Custom domains** in the Pages project and complete the DNS setup. The repository's `CNAME` file does not configure a custom domain for Cloudflare Pages automatically.

## External Links

- [GitHub](https://github.com/liuwenlonghub)
- [Twitter / X](https://x.com/liuwenlong)
- [wonderful.today](http://wonderful.today)