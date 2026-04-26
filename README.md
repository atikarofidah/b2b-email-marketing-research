# B2B SaaS Email Marketing Research Project

This repository is part of a portfolio project for 100Hires. It demonstrates the use of AI-powered tools (Cursor, Claude Code, Codex) to research, collect, and synthesize high-signal marketing strategies from industry experts.

## 🎯 Research Project: Newsletter / Email Marketing for B2B SaaS

### Why I Chose This Topic
I chose this topic to expand my existing experience in AI-content production into the realm of **retention marketing** and **lifecycle email strategy**. For B2B SaaS, email is not just a broadcast tool; it is a critical engine for lead nurturing, user activation, and churn prevention. I want to understand how top practitioners build these "invisible" growth engines.

### How I Selected Experts
I filtered experts based on three core pillars:
1. **Proven Practitioners:** People who currently manage or advise email systems for real SaaS brands.
2. **Technical & Strategic Balance:** I included experts focused on infrastructure (deliverability/automation) as well as those focused on high-conversion copywriting.
3. **High-Signal Content:** Creators who share actionable frameworks and data-backed insights rather than generic advice.

### What I Collected
Using **Claude Code** and **Codex**, I extracted and organized:
- **LinkedIn Insights:** Tactical posts from 8 industry leaders.
- **YouTube Transcripts:** Deep-dive video content from 2 top-tier creators.
- **Expert Annotations:** A curated list in `sources.md` explaining the unique value of each source.

---

## 🛠 Tools & Technical Setup

### Tools Used
- **IDE:** [Cursor](https://cursor.com/)
- **AI Agents:** Claude Code & Codex
- **Version Control:** Git & GitHub

### Steps Completed
1. **Environment Setup:** Installed Cursor IDE and configured AI extensions.
2. **Repository Architecture:** Created a structured research environment following a professional folder convention.
3. **Automated Extraction:** Used AI agents to fetch transcripts and format raw LinkedIn data into clean Markdown.
4. **Git Workflow:** Maintained a consistent commit history to document the project's evolution.

### Challenges & Solutions

#### 1. GitHub Authentication Flow
- **Issue:** Confusion during the device authorization process in Cursor.
- **Solution:** Triggered "GitHub: Sign in" via the Command Palette (Ctrl+Shift+P), which successfully generated the device code.

#### 2. Technical Data Extraction (YouTube)
- **Issue:** Manually transcribing video content is time-inefficient.
- **Solution:** Leveraged **Claude Code** to interface with YouTube transcripts, allowing for rapid synthesis of 15-20 minute videos into searchable text files.

#### 3. Git Workflow Mastery
- **Issue:** Understanding the distinction between `commit` (local) and `push` (remote).
- **Solution:** Adopted a "commit early, commit often" approach to ensure transparency in my work process.

---

## 📂 Repository Structure
```text
/research
├── sources.md              # Curated expert list with annotations
├── linkedin-posts/         # Categorized posts by author
├── youtube-transcripts/    # Formatted transcripts by video
└── other/                  # Supplemental materials