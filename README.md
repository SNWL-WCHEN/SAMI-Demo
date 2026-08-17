# SAMI — North-Star Interface

### ▶ [View the live prototype](https://snwl-wchen.github.io/SAMI_Demo/)

A north-star design for an AI assistant in a security operations platform, built to answer a hard question: what should it feel like when an autonomous system is doing real work on your behalf?

---

## The problem

Security teams and managed service providers handle an enormous volume of alerts, and most of them do not require human judgment. An AI assistant can absorb a lot of that work, but only if operators trust it. Trust in this context is a design problem as much as a model problem. People need to see what the system did, why it did it, and where they still need to weigh in.

## What this prototype explores

- **Autonomy made legible** — a clear split between what was resolved automatically and what needs human attention
- **Live activity stream** showing each action the system took, with the reasoning attached
- **Priority-tagged action queue** so the items requiring judgment surface above the noise
- **Operational KPIs** including resolution time, issues handled autonomously, and revenue at risk
- **Escalation paths** that make it obvious when and why something came back to a person

## How I approached it

The design principle throughout was that a confident wrong answer is worse than no answer. In a security context, an assistant that quietly does the wrong thing is a liability, so the interface is built to expose its own work rather than hide it behind a chat window.

I built this as a working prototype to pressure-test the interaction model before engineering committed time, and to give leadership something concrete to react to rather than a description.

---

**Stack:** HTML, CSS, JavaScript

**Note:** Design prototype for demonstration purposes. Data shown is illustrative.

---

### Other work

- [Unified API Hub](https://snwl-wchen.github.io/API-hub/) — developer portal for partner API access
- [Claude Skills Library](https://snwl-wchen.github.io/Skills-Library/) — AI instruction library for product teams
- [Dark Mode UUIF](https://snwl-wchen.github.io/UM-Dark-Mode/) — design system dark mode implementation
