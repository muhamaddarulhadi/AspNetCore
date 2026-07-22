# ASP.NET Core Developer Learning Guide

A single-page, self-contained training reference for junior ASP.NET Core developers — no build step, no dependencies to install, just one HTML file you can open in a browser or host anywhere as a static site.

**🔗 Live demo:** [https://muhamaddarulhadi.github.io/AspNetCore](https://muhamaddarulhadi.github.io/AspNetCore)

---

## What's in the guide

The guide is a single `index.html` file styled after Microsoft Learn documentation — sidebar navigation, a sticky table of contents, light/dark mode, a reading-progress bar, and inline syntax-highlighted C# examples. It covers:

| # | Section |
|---|---|
| 01 | What is .NET? |
| 02 | .NET Framework vs .NET Core (Modern .NET) |
| 03 | Razor Pages |
| 04 | ASP.NET Core Identity |
| 05 | Role-Based Authorization & Dependency Injection |
| 06 | Entity Framework Core |
| 07 | ADO.NET (including all 10 stored-procedure execution patterns) |
| 08 | When to Use Entity Framework vs ADO.NET |
| 09 | Best Practices |
| 10 | Essential CLI Commands (`dotnet clean`, `dotnet build`, `dotnet publish`) |
| 11 | EF Core Migrations to SQL Server |

## Features

- 📱 Fully responsive, with a collapsible mobile sidebar
- 🌓 Light/dark mode toggle (also respects your OS preference on first visit)
- 🔍 Simple in-page search that jumps to the matching heading
- 📊 Comparison tables, callout boxes, and CSS-only architecture diagrams
- 💻 C# code samples with a built-in, dependency-free syntax highlighter and a one-click copy button
- 🧩 Expandable accordion for the 10 ADO.NET stored-procedure patterns
- ⚡ Zero build tools, zero npm install — just HTML, CSS, and vanilla JavaScript (plus the Tailwind CDN for a few utility classes)

## Tech stack

- Plain HTML5 + CSS (custom properties for theming)
- Vanilla JavaScript (no framework)
- [Tailwind CSS](https://tailwindcss.com) via CDN (footer only)
- Inline SVG icons (no external icon fonts)

---

## Running it locally

No server or build step required — just open the file directly:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

Or, for a more realistic local-server experience (recommended if you add more pages later):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## License

Feel free to use, adapt, and share this guide for learning or teaching purposes.
