# yt-ad-skipper-macos (Youtube Ads Skipper - MacOS)
A macOS app &amp; browser extension that brings YouTube's "Skip Ad" button directly to your Touch Bar, complete with live countdown timers and global hotkey triggers. Features optional auto-skipping.   

🔒 STRICT COPYRIGHT NOTICE ⚠️:

`This project is proprietary. All rights reserved. Code is available for educational viewing only.`

## About - Introduction

A lightweight macOS utility designed to automatically or manually bypass YouTube advertisements directly from your system background or Touch Bar. 

##  Key Features

* **Auto-Skip:** Automatically triggers the YouTube "Skip Ad" button the exact millisecond it becomes interactive.
* **Global Hotkey:** Skip ads using a customizable keyboard shortcut without needing to click your mouse.
* **Touch Bar Integration:** Displays a native "Skip" button on your Mac's Touch Bar during ad playback.
* **Live Ad Timer:** Streams the remaining ad countdown and overall duration directly onto your Touch Bar.

## ? How It Works

The project is split into two components to bypass macOS sandboxing limitations:
1. **macOS App (Swift/SwiftUI):** Handles system-wide global hotkeys, background processes, and native Touch Bar UI rendering.
2. **Browser Extension (JavaScript):** Safely interacts with the YouTube DOM to monitor video players, track countdown elements, and click the skip button.

Both components communicate instantly in the background using Native Messaging.

---

## 🔒 Legal & Licensing (Strict Protection Notice)⚠️ 

**Copyright (c) 2026 Ghulam Sarwar Khan. All rights reserved.**

This project is **not** open-source software. By viewing this repository, you acknowledge and agree to the following strict terms:

* **No Reproduction:** You may not copy, duplicate, or replicate any portion of this source code for any reason.
* **No Distribution:** You may not redistribute, publish, or host this code or compiled binaries anywhere else.
* **No Commercial Use:** You are strictly forbidden from selling, licensing, or otherwise monetizing this software, its concepts, or its code.
* **Educational Viewing Only:** This repository is public strictly for portfolio presentation, architectural review, and public auditing. 

⚠️ *`Any unauthorized use, cloning, or distribution of this intellectual property will be subject to legal action.`*

---

##  Contribution Guidelines

Thank you for your interest in improving this project! Because this is a proprietary, strictly protected project, contributions are managed under specific guidelines:

1. **Pull Requests Only:** If you would like to contribute a bug fix or feature optimization, please open a formal Pull Request (PR) on GitHub.
2. **Transfer of Rights:** By submitting a Pull Request to this repository, you explicitly grant the repository owner (Ghulam Sarwar Khan) an irrevocable, perpetual, worldwide, and royalty-free license to use, modify, merge, and distribute your contributed code as part of this project.
3. **No Ownership Claims:** Contributors retain no intellectual property or commercial rights over the final compiled application or the repository code.

### ? How to Contribute:
1. **Fork** the repository (permitted strictly via GitHub's standard Terms of Service for evaluation purposes).
2. Create a new feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes safely (`git commit -m 'Add some AmazingFeature'`).
4. **Push** to the branch (`git push origin feature/AmazingFeature`).
5. Open a **Pull Request** detailing exactly what your code fixes or improves.
