# Habit Lab (aka HABITERM) 🔬📈

**Habit Lab** is a high-performance, zero-dependency, local-first habit tracker designed for people who want data-driven optimization, not just checkmarks. It pairs advanced behavioral analytics—like cross-habit correlation matrices—with real-time research integration to help you understand the *why* and *how* behind your routines.

Built entirely with plain vanilla web technologies (**HTML5, CSS3, JavaScript**), Habit Lab runs entirely in your browser. No accounts, no subscriptions, and zero tracking—your data never leaves your machine.

---

## 🌟 The Core Philosophy: Analytics + Context

Most habit trackers just count streaks. **Habit Lab** treats your habits as an interconnected ecosystem:

1. **Habit Synchronization & Synergy:** The engine calculates the **Phi Coefficient ($\phi$)** between your habits to discover hidden relationships. *("On days you meditate, your focus session success rate increases by 34%—consider stacking them.")*
2. **The Research Desk:** Fully integrated live-feed panels pull contextually relevant data based on your habits. It queries **PubMed** for medical/scientific literature, **Hacker News** for tech/productivity discussions, and **Wikipedia** for fundamental primers—cached efficiently to respect API rate limits.

---

## 🎨 Dual-Engine UI: Choose Your Interface

The project includes two completely distinct front-end interfaces powered by the exact same underlying state and data engine:

### 1. Habit Lab (Default UI)
A clean, modern, minimalist interface. It utilizes soft dark and light modes, human-readable metrics, structural habit stacks, and clear "Smart Nudges" to guide your day without cognitive overload.

### 2. The Terminal Edition (`terminal.html`)
For power users and data nerds, toggle into a fully immersive **Bloomberg Terminal** cosplay environment. 
* Every habit trades like a security with its own ticker (`MEDT`, `CODE`, `H2O`).
* Features a dynamic momentum pricing engine ($+1.8\%$ per fill, $-2.2\%$ per miss), a scrolling ticker tape, a global "HABIX" composite performance index, and four retro phosphor themes with CRT scanline toggles.
* Features a robust **Command Line Interface**—type `DONE MEDT 3` or use `F1–F10` hotkeys to jump panels instantly.

---

## 🛠️ Features At A Glance

* **Advanced Analytics Engine:** 7/30/90-day fill rates with deltas, weekday strength breakdowns, and a dynamic habit-pair correlation matrix.
* **The Grading Curve:** Automatic portfolio GPA calculation grading your consistency from `A+` down to `F` (using a customized square-root curve for fair scoring).
* **Flexible Scheduling:** Built-in support for daily or weekday-specific schedules, historical day-backfilling with edit warnings, and a customizable day-rollover hour for night owls.
* **Privacy & Portability:** Data persists reliably via `localStorage`. Features instant JSON import/export so you can back up or migrate your data at any time.
* **Robust & Lightweight:** ~3,800 lines of highly optimized, vanilla JavaScript spread across 17 modular files. Zero `npm install` required.

---

## 🚀 Quick Start

Because Habit Lab has zero external dependencies, getting started takes five seconds:

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/yourusername/habit-lab.git](https://github.com/yourusername/habit-lab.git)
