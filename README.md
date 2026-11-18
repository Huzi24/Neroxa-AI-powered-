# Neroxa-AI-powered-
# NEXORA — Your AI & Productivity Hub

> **Discover. Create. Learn. Achieve.**  
> Find the right AI tools, learn digital skills with original guides, and stay organised — all in one premium workspace.

---

## 🔗 Project Links

- **Live Website (GitHub Pages):** [https://Huzi24.github.io/nexora-ai-productivity-hub/](https://Huzi24.github.io/nexora-ai-productivity-hub/)
- **Original Prototype / Artifact:** [View Claude Artifact](https://claude.ai/code/artifact/59d6dc25-fa9f-4092-8508-fc4446358199) *(Requires active Claude session)*

---

## 📸 Screenshots

### 1. Home & Hero Section
![Hero Section](screenshots/1000399770.jpg)

### 2. Interactive AI Directory Search
![Directory Search](screenshots/1000399771.jpg)

### 3. Featured AI Tools Cards
![Featured Tools](screenshots/1000399772.jpg)

### 4. Popular Categories & Latest Guides
![Categories & Guides](screenshots/1000399773.jpg)

---

## ✨ Key Features & Modules

### 1. Curated AI Tools Directory (12 Featured Tools)
Browse, search in real-time, filter by category, and sort alphabetically (`A–Z` / `Z–A`) across **12 verified AI platforms** with official links:
- **AI Writing:** ChatGPT, Claude
- **AI Image Generation:** Midjourney
- **AI Video Generation:** Runway
- **AI Audio:** ElevenLabs
- **AI Coding:** GitHub Copilot
- **AI Research:** Perplexity
- **AI Productivity:** Notion AI
- **AI Design:** Canva
- **AI Automation:** Zapier
- **AI Education:** Khanmigo
- **AI Marketing:** Jasper
- *Note: Also includes **AI Business** in the 12 core directory categories.*

### 2. Built-in Productivity Workspace
- **Task Manager:** Create, check off, and delete daily tasks (persisted automatically via browser `localStorage`).
- **AI Summarizer (Demo Mode):** Rule-based extractive text summarizer for quick notes and paragraphs.
- **Blog Post Idea Generator:** Instant content topic ideas generated from any keyword.

### 3. Educational Guides & Articles
Original, structured guides with interactive Table of Contents and reading-time indicators:
- *How to start with AI tools without feeling lost* (AI Guides)
- *Building a freelance portfolio from zero* (Freelancing)
- *A simple weekly planning system for students* (Productivity)
- *Frontend basics: what to learn first* (Technology)

### 4. Personal Dashboard & Bookmarking
- **Favorites System:** Tap the heart icon (`♡` / `♥`) on any tool card to save it to your local favorites list.
- **Local Workspace Preview:** Track task completion percentage with a dynamic progress bar, write personal notes, and view saved tools without needing an external backend.

### 5. Premium Dark Glassmorphism UI
- Custom **3D rotating CSS cubes**, animated floating gradient blobs, and an HTML5 `<canvas>` particle background.
- Full keyboard accessibility, smooth scroll animations (`IntersectionObserver`), and mobile-first responsive navigation.

---

## 🛠️ Tech Stack

- **Core Framework:** React 18 (UMD) with `HTM` (Hyperscript Tagged Markup)
- **Styling:** Tailwind CSS 3.4 (CDN) & Custom CSS3 Glassmorphism / Keyframe Animations
- **Typography:** Google Fonts (`Space Grotesk` & `Inter`)
- **Storage:** Client-side `localStorage` (Zero external database required for preview)
- **Deployment:** GitHub Pages

---

## 📁 Repository Structure

```text
nexora-ai-productivity-hub/
│
├── index.html               # Complete Single-File React Application
├── README.md                # Project Documentation
└── screenshots/             # UI Preview Images
    ├── 1000399770.jpg       # Home & Hero Section
    ├── 1000399771.jpg       # Interactive Directory Search
    ├── 1000399772.jpg       # Featured AI Tools Cards
    └── 1000399773.jpg       # Popular Categories & Guides
git clone [https://github.com/Huzi24/nexora-ai-productivity-hub.git](https://github.com/Huzi24/nexora-ai-productivity-hub.git)

cd nexora-ai-productivity-hub

Launch the website:
Open index.html directly in any modern browser (Chrome, Edge, Safari, Firefox). No npm install or build step is needed.

📄 Disclaimer
This build is a frontend preview release. External backend integrations (Supabase authentication, newsletter API, and live LLM API keys for workspace helpers) are decoupled for safe static hosting on GitHub Pages.
👤 Author
Muhammad Huzaifa Mansha
GitHub: @Huzi24