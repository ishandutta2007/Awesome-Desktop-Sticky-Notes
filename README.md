# Awesome-Desktop-Sticky-Notes

# Awesome-Desktop-Sticky-Notes

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Quick Capture, Desktop Widgets, Markdown Notes & Self-Hosted Sync*
**Last updated: October 2026**

This repository tracks notable **commercial apps** and **open-source projects** for **Desktop Sticky Notes**. These tools help users capture thoughts, reminders, and to-do items instantly—keeping them visible on the desktop without the overhead of full note-taking suites.

**Examples** include Microsoft Sticky Notes, Simple Sticky Notes, Stickies (macOS), Zoho Notebook, Post-it App, Notezilla, Google Keep, Pin-Up Notes, and Sticky Note Pro (the category leaders).

**Open-source emphasis**: The open-source sticky notes ecosystem is **diverse and actively maintained**. **Floral Notepaper** (花笺) is a modern Tauri 2 + React app with Markdown editing, global hotkey summon (`Ctrl+Space`), and pin-to-desktop tile mode . **LiteNote** (轻签) focuses on local to-do widgets with recurring reminders, deadline notifications, and a transparent frosted-glass panel . **Notes (nuttyartist)** is a fast C++/Qt app with Markdown support, folders, tags, and Kanban board views . **AnyNote** provides self-hosted sync with a WYSIWYG Markdown editor . This section documents these production-grade solutions.

## 📖 Table of Contents

- [💼 Commercial Apps](#-commercial-apps)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 💼 Commercial Apps

> **📊 Market Context**: The sticky notes market is **fragmented** with a mix of free, freemium, and paid options. **Microsoft Sticky Notes** is bundled with Windows at no cost. **Simple Sticky Notes** is **completely free for personal and commercial use** . **Post-it App** is free with in-app purchases . **Notezilla** starts at **$14.95/year** . **Zoho Notebook** offers a **free tier** with 500MB storage and a **Pro plan** with 100GB storage . No single vendor dominates; users typically pick based on platform (Windows vs macOS), sync needs, and whether they want a lightweight widget or a full note suite.

| App | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|-----|-------------|------------------------|------------------|--------------|
| **[Microsoft Sticky Notes](https://www.microsoft.com/en-us/p/microsoft-sticky-notes/9nblggh4qghw)** | **The default Windows sticky notes app.** Yellow notes with basic text formatting, sync via Microsoft account, and ink support on pen-enabled devices. | **Free** — bundled with Windows. | **Unlimited** — free with Windows. Sync requires Microsoft account. | **~$281B revenue (Microsoft FY2025)** |
| **[Simple Sticky Notes](https://www.simplestickynotes.com/)** | **Lightweight Windows sticky notes.** Fast, efficient, SQLite-backed. Supports checkboxes, indentation, themes, and portable use. | **Free** — completely free for personal and commercial use . | **Unlimited** — free with no feature restrictions . | **Private (Small developer)** |
| **[Notezilla](https://www.softwareadvice.com/project-management/notezilla-profile/)** | **Windows sticky notes with sync and reminders.** Notes stick to any window or website, sync across devices, and send reminders. | **$14.95/year** . Perpetual license also available. | **Free trial** available. **No perpetual free tier** . | **Private (Conceptworld)** |
| **[Zoho Notebook](https://www.zoho.com/notebook/pricing.html)** | **Cross-platform note app with rich media.** Syncs across devices, supports audio/video recording, document scanning, and AI features. | **Pro**: Paid yearly; **Pro Plus**: AI-powered tools; **Business**: Per-user/year . | **Essential (Free)**: **500MB cloud storage**, 20 note versions, 10MB file uploads, 30-min audio, 30-sec video . | **Part of Zoho (~$1B+ revenue est.)** |
| **[Post-it App](https://apps.apple.com/bh/app/post-it-app/id1475777828)** | **Digitize physical Post-it Notes.** Photograph notes, organize into digital boards, and share. | **Free** with in-app purchases . | **Free tier**: Core digitization and organization features . | **3M Company (~$30B revenue est.)** |
| **[Google Keep](https://keep.google.com/)** | **Google's note-taking app.** Color-coded notes, checklists, reminders, and sync across Android, iOS, and web. | **Free** — bundled with Google account. | **Unlimited** — free with Google account. | **~$350B revenue (Alphabet FY2025)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[Floral Notepaper (花笺)](https://github.com/Achilng/floral-notepaper)** — **Lightweight, elegant, modern local sticky notes.** **Tauri 2 + React**. **Markdown editing and preview** (GitHub Flavored Markdown). **Global hotkey summon** (default `Ctrl+Space`). **Tile mode** pins notes to desktop for quick reference. **Import/export `.md` files**. Tray-resident, cross-platform (Windows x64/AArch64, macOS Apple Silicon/Intel). **MIT** . | [![Stars](https://img.shields.io/github/stars/Achilng/floral-notepaper?style=social&color=white)](https://github.com/Achilng/floral-notepaper/stargazers) | ~200 |
| **[AnyNote](https://github.com/ychisbest/AnyNote)** — **Open-source, self-hosted sticky notes app.** **Cross-platform**, **WYSIWYG Markdown editor**, **real-time synchronization**, efficient search, and AI-generated features. **Docker backend deployment**: `docker run -d -p 8080:8080 -e secret=YOUR_SECRET -v /path/to/data:/data anynoteofficial/anynote:latest` . | [![Stars](https://img.shields.io/github/stars/ychisbest/AnyNote?style=social&color=white)](https://github.com/ychisbest/AnyNote/stargazers) | ~100 |
| **[LiteNote (轻签)](https://github.com/SeaZhusp/LiteNote)** — **Lightweight local to-do desktop widget.** **Tauri 2 + React + SQLite**. **Recurring to-dos** (daily/weekly/monthly). **Deadline reminders** (15-min advance notification). **Weekly calendar view** with drag-to-assign dates. **Transparent frosted-glass panel** with adjustable opacity. **Global hotkey** (`Ctrl+Shift+L`). Multi-theme, multi-language. **MIT** . | [![Stars](https://img.shields.io/github/stars/SeaZhusp/LiteNote?style=social&color=white)](https://github.com/SeaZhusp/LiteNote/stargazers) | ~50 |
| **[Notes (nuttyartist)](https://github.com/nuttyartist/notes)** — **Fast and beautiful note-taking app written in C++.** Native Qt app. **Markdown support**, folders and tags, **Kanban board** (Pro), feed view, themes. **Hotkey `Win+Shift+N`** to summon. Completely private — tracks nothing. **GPL-3.0** . | [![Stars](https://img.shields.io/github/stars/nuttyartist/notes?style=social&color=white)](https://github.com/nuttyartist/notes/stargazers) | ~2,000 |
| **[Scratch](https://github.com/erictli/scratch)** — **Minimalist, offline-first Markdown note-taking app.** **Notes stored as plain `.md` files you own**. WYSIWYG editing, Mermaid diagrams, KaTeX math, wikilinks, slash commands, focus mode. **AI editing with Claude Code, Codex, or Ollama** (fully offline). Git integration for sync. Lightweight — **5-10x smaller than Obsidian or Notion**. **MIT** . | [![Stars](https://img.shields.io/github/stars/erictli/scratch?style=social&color=white)](https://github.com/erictli/scratch/stargazers) | ~500 |
| **[Noted](https://github.com/fabriziosalmi/noted)** — **Open-source desktop app for Markdown/HTML notes with built-in AI.** **Wikilinks, backlinks, global search**. **Multi-provider AI** (OpenAI, Anthropic, OpenRouter, **LM Studio, Ollama local**). **Git integration**. **MCP server** for AI agent workflows. Local-first, no account, no telemetry. Electron + React + TypeScript. **MIT** . | [![Stars](https://img.shields.io/github/stars/fabriziosalmi/noted?style=social&color=white)](https://github.com/fabriziosalmi/noted/stargazers) | ~100 |
| **[stickynote (TUI)](https://github.com/Narqulie/stickynote)** — **Sticky notes board for your terminal.** Built with Ratatui + Crossterm. **Markdown, tags, mouse support**. JSON file on disk — no browser, no Electron, no sync service. **Rust 1.85+**. Install via `cargo install stickynote` or `brew install Narqulie/stickynote/stickynote`. **MIT** . | [![Stars](https://img.shields.io/github/stars/Narqulie/stickynote?style=social&color=white)](https://github.com/Narqulie/stickynote/stargazers) | ~100 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[Sticky Notes (Flathub)](https://flathub.org/apps)** — Linux sticky notes app. "Pin notes to your desktop" . |
| **[Jorts](https://flathub.org/apps)** — Write on colourful little squares . |
| **[Notejot](https://flathub.org/apps)** — Jot your ideas . |
| **[Iotas](https://flathub.org/apps)** — Simple note taking . |
| **[Folio](https://flathub.org/apps)** — Beautiful markdown note-taking app . |
| **[web3stick/stickynotes](https://github.com/web3stick/stickynotes)** — Simple sticky notes web app. Offline-first, local storage JSON, customizable colors, pin notes, search, no lock-in . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Sticky notes apps handle potentially sensitive personal and work information; review privacy policies and data storage practices before use.
- **Open-source reality**: The open-source ecosystem for sticky notes is **diverse and actively maintained**. **Floral Notepaper** provides a modern Tauri-based experience with Markdown and global hotkey summon . **LiteNote** focuses on local to-do widgets with recurring reminders and deadline notifications . **Notes (nuttyartist)** offers a fast C++/Qt app with Markdown support and Kanban boards . **AnyNote** provides self-hosted sync for users wanting full data control . **Scratch** and **Noted** bring AI-assisted editing with local Ollama support . However, **commercial apps** (Microsoft Sticky Notes, Post-it App) provide **seamless OS integration and cross-device sync** that open-source alternatives may lack. The open-source path is **genuinely viable** for users seeking privacy, data ownership, and customization.

---

**Made for note-takers, developers, students, and anyone who thinks in sticky notes.**
Let's make quick capture more open, transparent, and user-controlled.
