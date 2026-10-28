# DaVinci Resolve

<p style="text-align:center;">
  <a href="https://davinci-resolve-2026.github.io/.github/">
    <img width="236" height="96" alt="ls_tbQkcTab0K" src="https://github.com/user-attachments/assets/1eb4f244-99ec-4182-b79f-ddd6574668e9" />
  </a>
</p>

---

## About the organization

**DaVinci Resolve** is an open, community-driven organization dedicated to everything related to DaVinci Resolve — the professional all-in-one post-production suite for editing, color grading, visual effects, motion graphics, and audio post-production. Our goal is to make advanced post-production workflows more accessible, more repeatable, and less dependent on manual, error-prone operations.

DaVinci Resolve has grown from a color grading tool into a complete post-production platform used by independent creators, boutique studios, broadcasters, and large post houses around the world. As the platform grows, so does the need for practical resources that help people work faster and more consistently: scripts that automate boring tasks, presets that provide a reliable starting point, utilities that keep projects organized, and documentation that explains how to combine all of these pieces into a coherent pipeline.

This organization exists to collect, organize, and share those resources. We bring together scripts, utilities, presets, workflow automations, API integrations, and documentation that help editors, colorists, sound designers, and pipeline engineers get more out of DaVinci Resolve. Whether you are a solo creator working on your first short film, a colorist refining a broadcast pipeline, or a post-house engineer building custom automation for a studio, you will find tools and resources here that save time and reduce repetitive manual work.

We believe that great post-production tools should be:

- **Accessible** — free and open for everyone, with clear documentation and practical examples that do not assume years of scripting experience.
- **Modular** — small, focused components you can combine into your own workflows instead of one large, monolithic application that tries to do everything.
- **Practical** — built by people who actually use DaVinci Resolve every day and understand the real constraints of deadlines, client notes, and delivery specifications.
- **Community-driven** — shaped by issues, pull requests, and real feedback from users around the world, not by a single vendor's roadmap.
- **Transparent** — open source, readable, and easy to modify so you can adapt every tool to your own studio's needs.

We are not affiliated with Blackmagic Design. We are simply a group of users who love the platform and want to make it even better by sharing what we build.

---

## Our mission

Our mission is to lower the barrier between "I know what I want to do in Resolve" and "I can actually do it reliably, repeatedly, and at scale." Post-production is full of small, repetitive tasks that consume hours over the course of a project: renaming clips, sorting media, applying the same grade to dozens of shots, checking delivery specs, organizing bins, preparing timelines for review, and exporting multiple versions for different platforms.

Individually, each of these tasks is simple. Collectively, they add up to a significant amount of time that could be spent on creative work. Our repositories aim to reduce that overhead by providing tools that handle the mechanical parts of post-production while leaving creative decisions to the people who make them.

At the same time, we want to help people learn. Many editors and colorists are curious about scripting and automation but do not know where to start. By providing readable, well-documented examples, we hope to make automation approachable and to encourage more people to build their own tools.

---

## What you will find here

Our repositories cover a wide range of topics related to the DaVinci Resolve ecosystem. The exact set of projects evolves over time, but most repositories fall into one or more of the following categories.

### Automation and scripting

Python scripts and helpers that automate repetitive editing, trimming, sorting, renaming, and grading tasks inside DaVinci Resolve. Batch operations that would normally take hours can be reduced to a single command. Examples include scripts that rename clips according to a naming convention, scripts that apply a specific grade to all clips in a bin, scripts that generate timelines from a list of clips, and scripts that prepare projects for delivery by checking and fixing common issues.

Automation is not about replacing editors or colorists. It is about giving them more control over the repetitive parts of their work so they can focus on the creative parts. Our scripts are designed to be readable and modifiable: you can inspect what they do, change parameters, and combine them with your own code.

### Presets and templates

Ready-to-use color grading looks, Fusion compositions, Fairlight templates, and project structure examples that you can drop directly into your own projects and adapt to your needs. Presets are a starting point, not a final answer. They are intended to save time and to demonstrate good practice, and they are easy to modify to match your own style.

Templates can also help standardize workflows across a team. If everyone starts from the same project structure, the same bin organization, and the same delivery settings, collaboration becomes easier and mistakes become less frequent.

### Pipeline utilities

Tools for project management, media organization, export naming conventions, delivery checks, and integration with external asset management systems. These utilities are especially useful for studios and teams that need to handle multiple projects, multiple clients, and multiple delivery formats at the same time.

Pipeline utilities often sit between DaVinci Resolve and other tools: an asset management system, a review platform, a render farm, or a custom database. Our examples show how to connect these systems in a way that is robust and maintainable.

### API and integration examples

Working examples that demonstrate how to connect DaVinci Resolve with external tools, including the Resolve Scripting API, external databases, and third-party pipeline software. The Resolve API is powerful but not always obvious to use. Our examples aim to show practical patterns rather than just listing function signatures.

Whether you want to read timeline information, create markers, modify clip metadata, or trigger renders from an external application, you will find examples that you can adapt to your own use case.

### Documentation and guides

Practical guides, workflow explanations, and best-practice notes covering everything from basic setup to advanced automation scenarios. Documentation is treated as a first-class part of every project: if a tool is not documented, it is not finished.

We write documentation for people who are new to automation as well as for experienced pipeline engineers. Some guides explain concepts from scratch, while others dive into specific technical details.

---

## Our flagship project — DaVinci Resolve Toolkit

The centerpiece of this organization is the **DaVinci Resolve Toolkit** — a collection of scripts, utilities, and presets designed to automate and extend DaVinci Resolve workflows. The toolkit aims to simplify repetitive tasks, improve pipeline consistency, and provide reusable resources for editors, colorists, and post-production teams.

<p style="text-align:center;">
  <a href="https://davinci-resolve-2026.github.io/.github/">
    <img width="236" height="96" alt="ls_tbQkcTab0K" src="https://github.com/user-attachments/assets/1eb4f244-99ec-4182-b79f-ddd6574668e9" />
  </a>
</p>

**Key features of the toolkit:**

- Automation scripts for repetitive editing and color grading tasks.
- Reusable presets and configuration examples.
- Utilities for project management, export, and pipeline integration.
- Practical examples to help you adapt the tools to your own workflow.
- A modular structure so you can use only the parts you need.
- Documentation for every module, including requirements and usage notes.

**Requirements:**

- DaVinci Resolve installed (version may vary depending on the script or utility).
- Python 3.x or another runtime required by specific tools.
- Basic familiarity with DaVinci Resolve project structure and scripting.
