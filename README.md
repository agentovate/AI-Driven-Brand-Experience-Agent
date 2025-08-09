# AI-Driven-Brand-Experience-Agent
This repository showcases one of the real-world AI agent design workflows I developed at Bexstudio. The goal was to build a integrated, modular generative system for a FMCG brand aiming to keep its visual language across multiple touchpoints using AI.

**Project Overview**

**Client**: Farkhondeh Biscuits  
**Role**: AI Agent & Workflow Designer  
**Platform**: ComfyUI (custom workflows with model orchestration and user input control)  
**Duration**: Iterative over multiple weeks (2024)
**teammate**: Leila Daem Inanloo
---

## 🧩 Scope & Components
The AI system was designed to support creative teams in the following areas:

- Character Design (for packaging & storytelling)
- Product Design Concepts
- Environmental Moodboards (for scenes, POS, narrative)
- Visual Storytelling (comic-style brand moments)
- Brand Graphics (posters, labels, key visuals)
- Website UI Style Directions

Each of these modules was connected through a unified visual system based on the brand's identity. Multiple AI agents were developed in a single modular workflow to allow **partial automation** and **user-controlled decision points**.

---

## 🎯 Key Challenge

> Maintaining **brand visual consistency** across all outputs — from character lines to web components — while using multiple generative models and adapters.

The system needed to:
- Respect the brand’s legacy color palette and tone
- Adapt output styles based on context (e.g., storytelling vs. UI)
- Support iteration and designer overrides

---

## ⚙️ Technical Summary

- **Framework**: ComfyUI
- **Model Stack**: Combination of open-source base models using [Ollama], [IP-Adapters], [Controlnet], and control modules
- **Workflow Design**: Built as layered blocks with conditional prompts, UI sliders, and checkpoints
- **Customization**: Used internal tagging and override mechanisms to ensure controllability
- **Output Volume**: 20+ style clusters, hundreds of finalized assets across categories

---

## 📁 Folder Structure

- `/workflows`: screenshots of ComfyUI workflows (JSON files not included due to IP policy)
- `/outputs`: selected visual outputs categorized by domain (product, story, UI, etc.)
- `/prompts`: sample prompts used in different modules
- `/process_notes`: thinking behind workflow logic, challenges, and design trade-offs

---

## 📸 Preview

<div align="center">
  <img src="outputs/brandA/hero-image.jpg" alt="farkhodeh_Story_design_workflow" width="600"/>
  <p><i>Sample key visual generated as part of the product packaging direction</i></p>
</div>

---

## 📌 Why This Matters

This project is an example of how generative AI workflows can move beyond visual experiments and become **design systems** — tools that enable creative teams to produce aligned, brand-safe outputs at scale and increase agile mindset.

If you're interested in workflow-driven design agents, AI-powered branding, or systematizing creativity through modular tools, feel free to connect.

---

## 🔒 Note

All brand names and outputs shared here are either:
- Public-facing samples
- Heavily abstracted to avoid sensitive IP exposure

For more information or private breakdowns, reach out via LinkedIn.

