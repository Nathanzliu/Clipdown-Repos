# Clipdown Repos

<a href="#english-version">English</a> | <a href="#chinese-version">中文说明</a>

---

<div id="english-version"></div>

## English Version

<p align="center">
  <img src="logo.png" width="320" alt="Clipdown Logo">
  <h3 align="center">Clipdown Repos</h3>
  <p align="center">
    A lightweight, local-first, subpixel-optimized Chrome extension built for Gemini. Capture context flawlessly, bypass session lag, and bridge your clips to Obsidian & Notion with front-matter YAML alignment.
  </p>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/clipdown-repos-context-cl/hnofabebkcclhdelobojjghbjfcobpco?hl=en"><img src="https://img.shields.io/badge/Chrome_Web_Store-v1.1.0-blue?logo=google-chrome&logoColor=white&style=flat-square" alt="Chrome Web Store"></a>
  <img src="https://img.shields.io/badge/Manifest-V3-green?style=flat-square" alt="Manifest V3">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=flat-square" alt="License GPL-3.0"></a>
  <img src="https://img.shields.io/badge/Privacy-100%25_Offline-blueviolet?style=flat-square" alt="Privacy First">
</p>

---

### 💡 Why Clipdown?

Are you tired of constantly copying and pasting across dozens of open tabs? Worried that a sudden proxy lag or page refresh will wipe out your long, highly-tuned Gemini conversations? 

**Clipdown redefines your AI workflow.** It allows you to instantly capture, highlight, and preserve snippet contexts via local-first architecture. Even if the network drops or the tab crashes, your assets are securely saved locally—ready to be streamed into your personal knowledge base.

---

### 📦 Key Features

*   **⚡ Two-Click Instant Capture**: Highlight any text or code in the Gemini interface, click the native pop-up bubble, and store it instantly. No flow disruption.
*   **📂 Markdown Knowledge Bridging (New in v1.1.0)**: Stream and export your clips into beautifully formatted `.md` files equipped with Front Matter YAML wrappers. Seamless integration for Obsidian, Notion, and Logseq.
*   **🔒 100% Privacy & Pure Offline**: No accounts. No tracking. No telemetry. All assets are locked within your browser's secure local sandbox (`chrome.storage.local`). It works 100% offline.
*   **🎨 Material 3 Aesthetic**: Tailored perfectly to match the Google Material 3 Expressive spec, rendering a native, fluid UI that supports adaptive dark/light system synch.
*   **🔍 Subpixel-Engine Highlighting**: Full Markdown parsing for precise code block, inline snippet, and hierarchical list structural retention. Includes lightning-fast fuzzy search.

---

### 🖼️ Showcase

> *[Placeholder: Insert your fluid workflow snippet GIF here to hit peak user conversion]*

---

### 📝 Markdown Export Architecture (Sample)

When you trigger the **"Export Markdown"** pipeline, Clipdown spits out clean, structural files using chronological incremental tags:

```yaml
---
source: "Building Extension V3 Framework"
clipped_at: 2026-06-11
url: "[https://gemini.google.com/app/](https://gemini.google.com/app/)..."
tags: [gemini-clip, clipdown-archive]
---

# Building Extension V3 Framework - Archive Node #1

### 💡 Prompt / Context
> How to correctly route clicks inside an asynchronous Chrome extension bubble popup without breaking scope?

### 📦 Output
```javascript
// Native M3 clickstream isolated barrier
settingsBtn.addEventListener('click', (e) => {
  e.stopPropagation();
  moreMenuBubble.classList.toggle('show');
});

---

### 👤 User Testimonials

> 🎓 **The Academic Researcher:**
> *"Writing my lit review and Gemini keeps generating perfect summary tables, but missing references when the chat lag hits is brutal. Clipdown saves my prompts and generated text locally with one click—it’s a total life-saver for academic research."*

> 💻 **The Local-First Purist:**
> *"Finally, a Gemini workspace that doesn't rely on cloud servers for storage. It works entirely offline through local storage, meaning zero sync lag and zero data leak risks. Perfect for saving long Gemini responses when my network is acting up."*

---

### 🛠️ Installation

1. Head over to the [Chrome Web Store](https://chromewebstore.google.com/detail/clipdown-repos-context-cl/hnofabebkcclhdelobojjghbjfcobpco?hl=en).
2. Click **Add to Chrome**.
3. Open Gemini, highlight a block of code, and watch the magic happen.
