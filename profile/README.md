# ☂️ Umbrella Infrastructure


> *"Infrastructure for a self-sustaining digital community, built on privacy, open source, and resilience."*

---

## What is Umbrella?

Umbrella is not a single project — it is an **umbrella** for a set of interconnected initiatives by [Arkan Fakoseh (@2kfi)](https://github.com/2kfi), a 17-year-old developer from Al-Karak, Jordan.

The vision is simple but ambitious: build technology and physical infrastructure that gives people **real ownership** of their digital and physical lives — locally hosted, privacy-first, resilient even when the internet goes down, and affordable enough to be used by real families in Jordan and beyond.

---

## Projects

### 🐧 Mada Linux — مدى لينكس

An Arch Linux-based distribution designed to make Linux accessible to Arabic-speaking users and anyone transitioning from Windows.

**Five flavours:**
- `KDE` — Full-featured desktop for power users
- `GNOME` — Clean and modern
- `Hyprland` — Tiling WM for minimalists
- `Cinnamon` — Familiar feel for Windows switchers
- `Base` — Bare-bones for those who know what they're doing

**Key goals:**
- Best-in-class Arabic language support (fonts, RTL, input methods)
- Easy out-of-the-box experience — no terminal required for everyday use
- Built on Arch's rolling release model for up-to-date software

→ [Mada-Linux Github Page](https://github.com/2kfi/Mada-Linux)

---

### 🩺 Hakeem — حكيم

A local-first AI health system in two editions:

#### Hakeem Home
A personal health and wellness AI assistant for everyday users.
- Tracks health metrics, habits, and wellbeing
- Web UI for easy access from any device on your local network
- Integrates with [Home Assistant](https://www.home-assistant.io/) for smart home health automation
- Runs entirely on your own hardware — no cloud, no subscriptions

#### Hakeem Enterprise
A clinical-grade AI system built for healthcare professionals in Jordan and the region.
- Assists doctors, pharmacists, and medical students in diagnosing and treating patients
- Specialized in rare disease identification
- Integrates with **Jordan's Ministry of Health Hakeem database** for verified patient records
- Ships with an approved medical knowledge base
- Designed to run air-gapped in hospitals and clinics

**Core principle:** Local first. Works in a blackout. Works without the internet. Works when it matters most.

→ [Hakeem Github Page](https://github.com/2kfi/Hakeem)

---

### ⭐ Najim — نجم

Your private, local AI assistant for the home — and eventually the main AI brain of the Umbrella ecosystem.

Think: Alexa or Google Home, but you own it completely.

- Runs 100% locally on affordable hardware (target: ~$20 one-time setup cost beyond hardware)
- Privacy-first by design — no data ever leaves your home
- Thin client apps for all operating systems
- Integrates deeply with Home Assistant
- Helps you manage your digital life: calendar, reminders, home automation, knowledge base
- Free forever after first setup — no recurring fees, no subscriptions

Najm may eventually evolve into the unified AI layer powering both Hakeem Home and the Umbrella neighborhood infrastructure.

→ *(Coming soon)*

---

### 🏘️ Umbrella Neighborhood — حي أمبريلا

The most ambitious project of all: a **real, physical neighborhood** in Al-Karak, Jordan.

#### The Land
200 dunums (about 50 acres or 20000 square meters) of land, with 60 dunums dedicated to shared infrastructure:
- Underground electrical cables
- Underground water pipes and sewage systems
- Underground fiber optic internet backbone

This is infrastructure that simply doesn't exist in most of Al-Karak today — built right, built to last.

#### The Community
- Selective residency — only vetted, approved residents
- Every home has its own small farm for food self-sufficiency
- Shared community services and common spaces
- Intentional, close-knit community design

#### The Network
- Affordable internet: target **22 JD/month** for 500 Mbps (vs. the current ~30 JD market rate)
- Optional extra services bundle for 2 JD/month
- Neighborhood-wide local network with full Umbrella AI and services stack
- **Fully air-gappable** — the entire network can be disconnected from the internet and the community continues to function normally

#### The Philosophy
> This isn't a smart city. It's a **resilient community** — one that could survive World War 3 as long as the electricity is on.

---

## Utilities & Tools

### 📦 pacman-local-mirror
A lightweight local repository manager for Arch Linux. Perfect for air-gapped setups or slow connections.

→ [pacman-local-mirror Github Page](https://github.com/2kfi/pacman-local-mirror)

---

## The Stack

| Layer | Technology |
|---|---|
| OS Base | Arch Linux |
| Containerization | Docker / Podman |
| Home Automation | Home Assistant |
| AI Runtime | Local LLMs (Ollama / Llama.CPP / custom) |
| Frontend | TypeScript / Web UI |
| Scripting | Bash / Python |
| Game Engine | Godot |
| Networking | OpenWrt, managed switches |

---

## Principles

1. **Local first** — if it needs the cloud to work, it doesn't belong here
2. **Privacy by design** — your data stays on your hardware
3. **Affordable** — built for real people in Jordan, not Silicon Valley budgets
4. **Resilient** — works when the power grid fluctuates, the internet cuts out, or worse
5. **Arabic-native** — not an afterthought, built in from day one
6. **Legacy** — built to last beyond its creator

---

## About the Builder

**Arkan Fakoseh** — 17 years old, Al-Karak, Jordan.

Homelabber, overthinker, FOSS advocate. Started using Linux at 14, and too many side projects for a Tawjihi student.

- GitHub: [@2kfi](https://github.com/2kfi)
- Hugging Face: [huggingface.co/2kfi](https://huggingface.co/2kfi)
- Email: arkanpers2@gmail.com
- Instagram: [@2k.fii](https://instagram.com/2k.fii)

---
