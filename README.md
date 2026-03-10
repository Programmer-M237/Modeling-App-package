# Modeling App — MVP Beta
### by Enumera

> ⚠️ **This is a pre-release MVP for evaluation and feedback purposes only.**
> All rights reserved. Redistribution or commercial use is strictly prohibited.

---

## 👋 Welcome

Thank you for visiting this repository. This is the official distribution point for the **Modeling App MVP Beta** — the first public showcase of technology built by **Enumera**.

Enumera is an emerging solutions company with a mission to **analyze every possibility and deliver the best** — across both technology and non-technology domains. This app is not a final product; it is a demonstration of what we are capable of building, and a first step toward establishing our market presence.

We are sharing this with the world to collect real feedback, spark conversations, and connect with people who share our vision.

---

## 🧠 What is the Modeling App?

The **Modeling App** is a **combinatorial state-space modeling and analysis tool** — a desktop application that lets you define entities by their properties and possible values, automatically generates every possible state combination, and provides powerful tools to filter, simulate, and mathematically analyze variation and similarity across those states.

### Core Concepts

**Objects** are the fundamental units of the app. Each object has a set of **properties**, and each property has a set of **forms** (possible values). The app automatically enumerates every possible combination of those forms, creating a complete **state space** for that object.

**Functional Objects** extend this further with computed **dynamic properties** — columns whose values are automatically derived from a formula evaluated per state row.

### Key Features

🗂️ **Modeling Canvas** — a zoomable, infinite canvas where objects are placed as interactive table widgets. Objects can be nested inside each other, linking sub-objects to specific property-value pairs.

🔍 **Filters** — a multi-layered filtering system with three scopes: global, multi-object, and single-object. Filters include or exclude rows by property value, or isolate rows differing by exactly N properties (N-step variation filters). Applied on demand via an Execute button.

⚡ **Event Simulation (GEL)** — a real-time simulation engine running at 10 ticks/second. Events have a database, triggers (time-based, random, or state-dependent), and transition protocols. The engine evaluates all triggers simultaneously and fires events accordingly, animating state changes live on screen.

📐 **Variations & Similarities** — given any state row, find all N-step variations (states differing by exactly N properties) and property similarities (states sharing a specific form value). A full **Similarity Lab** offers pair analysis, reference ranking, full similarity matrices, and a weighted **Global Variation / Global Similarity** metric.

💾 **Project Management** — full save/load in `.maproj` format, recent files, autosave, undo/redo, and export to CSV or XLSX.

---

### 🛠️ Built With
- 🐍 **Python** — core application logic
- 🎨 **Qt Designer + PySide6** — modern cross-platform GUI
- 📦 **PyInstaller** — packaged as a standalone installer for all major platforms

---

## 💻 Download & Install

Choose the installer for your operating system:

| Platform | File | Status |
|----------|------|--------|
| 🪟 Windows | `ModelingApp-win.exe` | ✅ Available |
| 🍎 macOS | `ModelingApp-mac.dmg` | ❌ Available |
| 🐧 Linux | `ModelingApp-linux.tar.gz` | ❌ Available |

> No installation of Python or any dependencies is required. The app runs standalone on your machine.

### Installation Steps

**Windows:**
1. Download `ModelingApp-win.exe`
2. Double-click to run the installer
3. Follow the on-screen prompts

**macOS:**
1. Download `ModelingApp-mac.dmg`
2. Open the `.dmg` and drag the app to your Applications folder
3. On first launch, right-click → Open if you see a security warning

**Linux:**
1. Download `ModelingApp-linux.tar.gz`
2. Extract: `tar -xzf ModelingApp-linux.tar.gz`
3. Run: `./ModelingApp`

---

## 💬 We Want Your Feedback

This MVP exists **because of testers like you.** Your input directly shapes the future of this product and the direction of Enumera.

Please take a few minutes after testing to share your thoughts:

## 👉Open a **GitHub Issue** in this repository with the label `feedback`.

**We'd love to know:**
- 🖥️ How was the installation experience?
- 🧭 Is the interface intuitive and easy to navigate?
- ⚡ How does the app perform on your machine?
- 🐛 Did you encounter any bugs or unexpected behavior?
- 💡 What features would you love to see added?

---

## 🐛 Reporting Bugs

Found a bug? Please [open an issue](../../issues/new) and include:
- Your operating system and version
- Steps to reproduce the problem
- What you expected to happen vs. what actually happened
- Screenshots if possible

---

## 🏢 About Enumera

**Enumera** is a solutions company being built from the ground up with one core belief:

> *Every problem has an optimal solution — you just have to enumerate every possibility to find it.*

We work across both **technology and non-technology** domains, applying structured thinking and innovative tools to deliver the best outcomes for our clients and users.

This Modeling App is our public debut — a signal to the market of the caliber of technology we are capable of creating.

Follow our journey:
- 🔗 *www.linkedin.com/in/tankala-azoasieh-manic*
- 📧 *tankalaazoasiehm@gmail.com*

---

## ⚖️ Legal

**© 2025 Enumera. All Rights Reserved.**

This software and all associated files are the exclusive intellectual property of Enumera. This repository is made publicly accessible for **evaluation and feedback purposes only.**

**You may NOT:**
- Redistribute, sell, or sublicense this software
- Modify, reverse-engineer, or decompile the application
- Use this software or any part of it in your own product or service
- Claim ownership or authorship of any part of this work

**You may:**
- Download and install the app on your personal device for testing
- Share the **link to this repository** with others who may be interested

> This software is provided "as is", without warranty of any kind. Use at your own risk.

---

*Built with ❤️ by Enumera*
