# Agenda Espiritual ✦

A management app for spiritual service professionals — client control, appointments, spiritual works, finances, and debt tracking.

Built as a real-world project for professional use.

---

## How to run

No installation or server needed. Just download and open:

```
index.html  →  open directly in the browser
```

All data is saved in the browser's `localStorage`.

---

## Features

- **Clients** — registration with photo, nickname, automatic zodiac sign from birthdate, full history, and real-time duplicate detection while typing
- **Appointments** — by service type (Tarot, Búzios, Mesa Radiônica), with payment control: paid on the spot, partial, or deferred
- **Spiritual Works** — track start date, end date, and result; filter by type and status
- **Finance** — monthly revenue split by currency (BRL/EUR), years generated dynamically from real data
- **Debts** — auto-created when saving with pending payment, partial payments linked directly to the source appointment or work
- **Global search** — find clients, appointments, and works from any screen

---

## Tech stack

| | |
|---|---|
| React 18 | UI and state management |
| Babel Standalone | JSX transpiled in the browser, no build step |
| localStorage | Client-side data persistence |
| Custom CSS | Dark theme with CSS variables, responsive layout |

---

## Project structure

```
agenda-espiritual/
├── index.html   ← full app (HTML + CSS + React in a single file)
└── README.md
```
