# Agentic AI News Radar - AI News Archive 2026

> **Agentic AI News Radar is a static web archive for browsing daily reports about agentic AI, general AI developments, and Thai AI news. It combines generated HTML pages with Markdown source files and supports publication through GitHub Pages.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/alexxiyclewis9457/agentic-news-radar-archive?style=flat-square)](https://github.com/alexxiyclewis9457/agentic-news-radar-archive)

---

<p align="center">
  <a href="https://alexxiyclewis9457.github.io/agentic-news-radar-archive/">
    <img src="https://img.shields.io/badge/Download-Agentic%20AI%20News%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download Agentic AI News Radar">
  </a>
</p>

> **[Open Agentic AI News Radar](https://alexxiyclewis9457.github.io/agentic-news-radar-archive/)**

---

[Download Latest Build](https://alexxiyclewis9457.github.io/agentic-news-radar-archive/)

---

## What Is Agentic AI News Radar?

Agentic AI News Radar provides a browser-friendly archive of news covering agentic AI, the wider AI field, and Thai news. Because the dashboard is generated as static HTML, readers can explore daily pages without a server-side application.

Each published page is supported by its corresponding Markdown report, preserving the underlying source content for inspection and future rebuilds. The included PowerShell dashboard script and GitHub Pages workflow establish a repeatable path from report updates to a published archive.

---

## Highlights

- Browse news through a static HTML dashboard
- Generate new archive pages for daily updates
- Retain Markdown reports alongside the rendered pages
- Track agentic AI and broader AI developments
- Organize Thai news coverage
- Rebuild the dashboard with the included PowerShell script
- Publish the archive using GitHub Pages
- Use a lightweight archive layout designed for static web hosting

---

## Installation

First, clone the repository and enter its directory:

```bash
git clone https://github.com/alexxiyclewis9457/agentic-news-radar-archive.git
cd REPO
```

To inspect the archive locally, open the generated HTML dashboard in a web browser.

When the dashboard needs to be regenerated, execute the included PowerShell rebuild script:

```powershell
.\<dashboard-rebuild-script>.ps1
```

Substitute `<dashboard-rebuild-script>.ps1` with the actual script name present in your checkout.

---

## Updating and Publishing

Use the following sequence for a normal archive update:

1. Create or revise the Markdown news reports.
2. Execute the PowerShell dashboard rebuild script.
3. Check the newly generated static HTML pages in a local browser.
4. Commit the changed reports and dashboard output.
5. Publish the repository through the GitHub Pages workflow.
6. Visit the deployed archive at [Download Latest Build](https://alexxiyclewis9457.github.io/agentic-news-radar-archive/).

For read-only access, either open the dashboard locally with a modern browser or use the hosted GitHub Pages address.

---

## Project Configuration

The project separates its source reports, generated dashboard pages, and deployment workflow. To change the content or generation behavior, inspect the repository's Markdown files and the PowerShell rebuild script.

The static HTML output does not need server-side settings. Hosting behavior is controlled by the repository configuration and its GitHub Pages workflow.

---

## Requirements

- A modern web browser to view the dashboard
- Git to clone and maintain the repository
- PowerShell to execute the dashboard rebuild script
- A GitHub repository for the Pages publishing process
- GitHub Pages enabled for the hosted archive
- Enough storage for the Markdown reports and generated HTML pages

---

## Frequently Asked Questions

### How do I access the archive?

When GitHub Pages is enabled, open the hosted [latest build](https://alexxiyclewis9457.github.io/agentic-news-radar-archive/). You can also view the generated HTML dashboard directly on your local machine.

### What is the process for generating additional news pages?

Modify the Markdown source reports, then run the included PowerShell dashboard rebuild script. This produces the static HTML pages that can be reviewed locally and published.

### Is a web server needed?

No server-side application is required for local viewing because the dashboard consists of static HTML. GitHub Pages can be used when a hosted version is desired.

### How does deployment work?

Commit the updated reports and generated dashboard files, then let the GitHub Pages publishing workflow deploy the repository.

### What can cause the dashboard to show old content?

Check that the Markdown reports contain the latest changes, run the rebuild script again, and confirm that the generated HTML files were committed before deployment.

### Where do I change generation or deployment settings?

Review the rebuild script, the Markdown source reports, and the GitHub Pages workflow to find the settings related to content generation and publication.

---

## Roadmap

- Grow the daily archive of AI news
- Make navigation between generated pages more convenient
- Continue improving the static dashboard layout
- Expand the publishing workflow as the collection increases

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
